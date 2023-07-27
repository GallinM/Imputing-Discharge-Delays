# Imputing-Discharge-Delays
## Important
This uses dummy data for illustration purposes.

## Introduction
This script demonstrates the removal of outliers and multiple imputation of missing data for patient discharge delays across multiple hospital sites.

## Aim
The aim of this project was to remove extreme outliers and impute missing data from patient discharge delays. **This can be potentially applied to any missing data with outliers**.

## Prerequisites
- Access to RStudio

## Methods
This project was designed in RStudio. Dummy patient discharge data are read into the script from multiple fictional hospital sites.
Extreme outliers are identified and removed from the data.
Missing values are imputed to provide an estimate of the values that are missing.
Data are visualised for fictional hospital sites to compare original data vs outlier removed and imputed data.
Data are exported into .csv files

### Built With
- R Markdown

### Strengths
This can be adapted for any missing data that contain outliers.

### Limitations
The identification of outliers is based on a cut-off value, this can be adjusted to suit however.

This process relies on a limited amount of data being missing. The greater the amount of missing data, the less reliable the imputation process.

The multivariate imputation by chained equations process can take a long time.

## Contributing
Contributions are greatly appreciated.

If you have a suggestion that would make this better, please fork the repo and create a pull request. You can also simply open an issue with the tag "enhancement". Don't forget to give the project a star! Thanks again!

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License
Distributed under the MIT License. See LICENSE.md for more information.

## Contact
Project contact email: gallin.montgomery@nhs.net

## Acknowledgements
- https://www.rdocumentation.org/packages/EnvStats/versions/2.3.1/topics/rosnerTest
- https://www.rdocumentation.org/packages/mice/versions/3.16.0/topics/mice 
