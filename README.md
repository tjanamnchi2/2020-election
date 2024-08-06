# 2020 Election Results by Region

This project aims to predict voting behavior in the 2020 United States Presidential Election based on geographical location using data from the American National Election Studies (ANES). The data was sourced from the `nes` dataset provided by the `primer.data` R package. The analysis involved cleaning the data to focus on the year 2020, selecting relevant columns (`pres_vote`, `region`), and mutating the `pres_vote` column to show candidate names. A binomial logistic regression model was fitted using the `brm()` function from the `brms` package to predict voting behavior. Visualization of the predicted probabilities for each candidate across different regions was created using `ggplot2`. The results suggest that Joe Biden was favored across all regions. This project was created as part of [Kane’s Data Science Bootcamp](https://bootcamp.davidkane.info). For more details, visit the [repository](https://github.com/tjanamnchi2/2020-election) on GitHub. For inquiries, contact Tanay Janmanchi at janmanchit@gmail.com.

Sources

[https://electionstudies.org](https://electionstudies.org)

[https://electionstudies.org/data-center/anes-time-series-cumulative-data-file/](https://electionstudies.org/data-center/anes-time-series-cumulative-data-file/)
