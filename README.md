# Influenza Vaccine Predictions
**Leveraging Pre-Vaccination Antibody Titers across Multiple Influenza H3N2 Variants to Forecast the Post-Vaccination Response**<br/>
*Authors*: Hannah Stacey, Michael A. Carlock, James D. Allen, Hannah B. Hanley, Shane Crotty, Ted M. Ross, and Tal Einav<br/>
https://doi.org/10.1101/2024.08.01.24311325<br/>


In this work, we present an algorithm that uses an individual's pre-vaccination antibody titers against different influenza variants to predict their post-vaccination response. The repository is structured as follows:
* *Data*: The raw measurements and results from our analysis
  * **H3N2 HAI Data.csv** contains HAI measurements pre-vaccination (day 0) and post-vaccination (around day 28) from prior influenza vaccine studies as well as from four new studies presented in this work. Predictions of the post-vaccination responses are provided whenever they were made (which requires sufficient variant overlap with prior studies). The exact date of the post-vaccination blood draw is supplied when available, as is age, sex, BMI, the day of vaccination, and the vaccine dose (for the UGA Fluzone studies).
  * **2023 Crotty - Afluria and FluMist.csv** is a separate standalone file for the two 2023 Crotty vaccine studies introduced in this work. They contain additional metadata describing each person's self reported vaccination history from the past there seasons as well as the time of day they were given their influenza vaccine.
* *Code*: A Mathematica notebook that contains the full analysis and reproduces all plots from this work.
  * All methods and results in the notebook are extensively annotated, and all code should run within less than a minute.
  * Analysis was performed using Mathematica version 14.0 for Windows, but should run on any platform and with any later version. There is no need for any installation beyond the standard Mathematica programming language.