# Predicting Body Fat Percentage Using Body Circumference Measurements

## Overview

This project aims to explore the effectiveness of using body circumference measurements as a method to predict body fat percentage. By applying multiple linear regression theories and techniques, we investigated the relationship between body fat percentage and various body measurements in men. This approach provides an accessible and inexpensive method for estimating body fat percentage, which is crucial for monitoring health and managing risks associated with excessive body fat.

## Team Members

- Daniel Alpizar
- Jocelyn Oja
- Khalil Nayef
- Jose Gabriel Abes

## Data Source

The dataset, obtained from Kaggle and originally compiled by Johnson (1996), includes body fat percentage as a function of age, weight, height, and various body circumference measurements for 252 men. The body density used to calculate body fat percentage was measured using an underwater weighing technique.

## Methodology

Our analysis involved:
1. Initial data exploration and preparation, including testing for multicollinearity among variables.
2. Model building, starting with a full additive model and progressively refining to include significant predictors and interactions.
3. Validation of model assumptions through diagnostic plots and formal testing.
4. Interpretation of the final model and its real-world applicability.

## Key Findings

- The variables age, neck circumference, abdomen circumference, and wrist circumference emerged as significant predictors of body fat percentage.
- Significant interactions were observed between neck and abdomen circumferences, as well as between age and wrist circumference, indicating complex relationships in predicting body fat percentage.
- Our final model, which includes main effects and interactions, satisfies the assumptions of multiple regression, supporting the validity of our findings.

## Conclusions

The study demonstrates the potential of simple body circumference measurements to predict body fat percentage accurately. This approach offers a practical alternative to more expensive and technically demanding methods, making it accessible for wider use in health monitoring and research.

## Future Directions

Future research could expand the analysis to include female participants and explore additional predictors and interactions. Further refinement of the model could enhance its accuracy and applicability to a broader population.

## References

Please refer to the project report for a comprehensive list of references.

## Appendix

The repository includes the following:
- Data preprocessing scripts
- Model building and evaluation notebooks
- Diagnostic plots and model validation outputs
- Project report in PDF format

For questions or contributions, please contact [@daniel-alpizar](https://github.com/daniel-alpizar) or submit an issue/pull request on this repository.
