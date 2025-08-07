# Subgroup Analysis Report

---

# Question 1: How much do you trust current centralized systems (where companies store and manage your data) to protect your health information?

## Overall Distribution & Metrics

![Overall Distribution for Q1](../data/img/subgroup_ana/Q1_overall_dist.png)

### Key Metrics

- **Mean:** 2.67
- **Median:** 3.00
- **Std. Dev:** 1.07

### Overall Distribution Table

|   1 |   count |
|----:|--------:|
|   3 |     101 |
|   2 |      54 |
|   1 |      40 |
|   4 |      30 |
|   5 |      13 |

## Subgroup Distributions

### Distribution by Subgroup: `user_type`

![Distribution for Q1 by user_type](../data/img/subgroup_ana/Q1_by_user_type.png)

| user_type   |    1 |    2 |    3 |    4 |   5 |
|:------------|-----:|-----:|-----:|-----:|----:|
| Non-user    | 24.8 | 18.8 | 37.6 | 15.8 | 3   |
| User        | 10.9 | 25.5 | 46   | 10.2 | 7.3 |

### Distribution by Subgroup: `lang_group`

![Distribution for Q1 by lang_group](../data/img/subgroup_ana/Q1_by_lang_group.png)

| lang_group   |    1 |    2 |    3 |    4 |   5 |
|:-------------|-----:|-----:|-----:|-----:|----:|
| English      | 12.5 | 22.5 | 47.5 | 10   | 7.5 |
| French       | 14.2 | 23.6 | 45.7 | 13.4 | 3.1 |
| German       | 18.2 | 27.3 | 36.4 |  9.1 | 9.1 |
| Spanish      | 26.5 | 18.4 | 32.7 | 14.3 | 8.2 |

### Distribution by Subgroup: `privacy_concern_score`

![Distribution for Q1 by privacy_concern_score](../data/img/subgroup_ana/Q1_by_privacy_concern_score.png)

|   privacy_concern_score |     1 |    2 |    3 |    4 |     5 |
|------------------------:|------:|-----:|-----:|-----:|------:|
|                    1.5  |   0   |  0   |  0   |  0   | 100   |
|                    2    |   0   |  0   |  0   |  0   | 100   |
|                    2.25 |   0   |  0   |  0   | 33.3 |  66.7 |
|                    2.5  |   0   |  0   | 33.3 | 50   |  16.7 |
|                    2.75 |   0   |  0   | 12.5 | 50   |  37.5 |
|                    3    |   0   |  3.7 | 55.6 | 33.3 |   7.4 |
|                    3.25 |   0   | 19   | 52.4 | 28.6 |   0   |
|                    3.5  |   5.4 | 13.5 | 73   |  8.1 |   0   |
|                    3.75 |   3.7 | 22.2 | 70.4 |  3.7 |   0   |
|                    4    |  16.7 | 38.9 | 33.3 |  8.3 |   2.8 |
|                    4.25 |  25.9 | 40.7 | 33.3 |  0   |   0   |
|                    4.5  |  36.8 | 36.8 | 26.3 |  0   |   0   |
|                    4.75 |  53.8 | 46.2 |  0   |  0   |   0   |
|                    5    | 100   |  0   |  0   |  0   |   0   |

### Distribution by Subgroup: `privacy_concern_level`

![Distribution for Q1 by privacy_concern_level](../data/img/subgroup_ana/Q1_by_privacy_concern_level.png)

| privacy_concern_level   |    1 |    2 |    3 |    4 |     5 |
|:------------------------|-----:|-----:|-----:|-----:|------:|
| High                    |  7.4 | 24   | 57   | 10.7 |   0.8 |
| Low                     |  0   |  0   |  0   |  0   | 100   |
| Moderate                |  0   |  2.3 | 40.9 | 38.6 |  18.2 |
| Very High               | 44.9 | 34.8 | 20.3 |  0   |   0   |

### Distribution by Subgroup: `tech_trust_score`

![Distribution for Q1 by tech_trust_score](../data/img/subgroup_ana/Q1_by_tech_trust_score.png)

|   tech_trust_score |    1 |    2 |    3 |    4 |    5 |
|-------------------:|-----:|-----:|-----:|-----:|-----:|
|                  1 | 71.4 |  9.5 | 19   |  0   |  0   |
|                  2 | 23.3 | 37.2 | 34.9 |  4.7 |  0   |
|                  3 |  9.3 | 20.6 | 54.6 | 13.4 |  2.1 |
|                  4 |  7.6 | 22.7 | 39.4 | 21.2 |  9.1 |
|                  5 |  9.1 |  9.1 | 27.3 |  9.1 | 45.5 |

### Distribution by Subgroup: `control_preference_score`

![Distribution for Q1 by control_preference_score](../data/img/subgroup_ana/Q1_by_control_preference_score.png)

|   control_preference_score |     1 |    2 |    3 |    4 |    5 |
|---------------------------:|------:|-----:|-----:|-----:|-----:|
|                    1.66667 | 100   |  0   |  0   |  0   |  0   |
|                    2       |  25   |  0   | 25   | 25   | 25   |
|                    2.33333 |  50   |  0   | 30   | 10   | 10   |
|                    2.66667 |  18.2 | 27.3 | 36.4 |  9.1 |  9.1 |
|                    3       |  27.6 | 20.7 | 37.9 | 13.8 |  0   |
|                    3.33333 |   6.2 | 25   | 56.2 | 12.5 |  0   |
|                    3.66667 |   8.9 | 26.7 | 51.1 |  4.4 |  8.9 |
|                    4       |  13.5 | 21.6 | 40.5 | 21.6 |  2.7 |
|                    4.33333 |  10.5 | 23.7 | 42.1 | 13.2 | 10.5 |
|                    4.66667 |  29.4 | 29.4 | 35.3 |  5.9 |  0   |
|                    5       |  33.3 |  0   |  0   | 66.7 |  0   |

### Distribution by Subgroup: `data_ownership_belief`

![Distribution for Q1 by data_ownership_belief](../data/img/subgroup_ana/Q1_by_data_ownership_belief.png)

|   data_ownership_belief |    1 |    2 |    3 |    4 |    5 |
|------------------------:|-----:|-----:|-----:|-----:|-----:|
|                       1 | 15.9 | 25   | 38.6 | 15.9 |  4.5 |
|                       2 |  4.3 | 21.7 | 34.8 | 39.1 |  0   |
|                       3 |  5   | 35   | 45   | 15   |  0   |
|                       4 |  3.6 | 17.9 | 50   | 17.9 | 10.7 |
|                       5 | 24.4 | 21.1 | 43.1 |  4.9 |  6.5 |

### Distribution by Subgroup: `response_completeness`

![Distribution for Q1 by response_completeness](../data/img/subgroup_ana/Q1_by_response_completeness.png)

|   response_completeness |    1 |    2 |    3 |    4 |   5 |
|------------------------:|-----:|-----:|-----:|-----:|----:|
|                     100 | 16.8 | 22.7 | 42.4 | 12.6 | 5.5 |

### Distribution by Subgroup: `Age group`

![Distribution for Q1 by Age group](../data/img/subgroup_ana/Q1_by_Age_group.png)

| Age group   |    1 |    2 |    3 |    4 |    5 |
|:------------|-----:|-----:|-----:|-----:|-----:|
| 18-24       |  8.8 | 11.8 | 67.6 |  5.9 |  5.9 |
| 25-34       | 15.1 | 24.6 | 42.1 | 14.3 |  4   |
| 35-44       | 17.6 | 29.4 | 23.5 | 29.4 |  0   |
| 45-54       | 20.8 | 25   | 33.3 |  8.3 | 12.5 |
| 55-64       | 23.1 | 23.1 | 34.6 |  7.7 | 11.5 |
| 65+         | 44.4 | 22.2 | 33.3 |  0   |  0   |
| <=17        |  0   |  0   | 50   | 50   |  0   |

### Distribution by Subgroup: `Education level`

![Distribution for Q1 by Education level](../data/img/subgroup_ana/Q1_by_Education_level.png)

| Education level                              |    1 |    2 |    3 |    4 |   5 |
|:---------------------------------------------|-----:|-----:|-----:|-----:|----:|
| Bachelor's degree or equivalent              | 16.8 | 21.8 | 48.5 |  8.9 | 4   |
| Doctorate (PhD) or higher                    | 40   | 20   | 40   |  0   | 0   |
| Master's degree or equivalent                | 13.9 | 30.6 | 30.6 | 18.1 | 6.9 |
| Upper Secondary / High School or equivalent  | 23.1 |  7.7 | 46.2 | 15.4 | 7.7 |
| Vocational/Technical training or certificate | 17   | 17   | 46.8 | 12.8 | 6.4 |

### Distribution by Subgroup: `Occupation`

![Distribution for Q1 by Occupation](../data/img/subgroup_ana/Q1_by_Occupation.png)

| Occupation    |    1 |    2 |     3 |    4 |    5 |
|:--------------|-----:|-----:|------:|-----:|-----:|
| Employed      | 18   | 27.1 |  36.1 | 15   |  3.8 |
| Retired       | 20   | 10   |  50   |  0   | 20   |
| Self-employed | 32.1 | 10.7 |  39.3 | 10.7 |  7.1 |
| Student       |  7.9 | 22.2 |  52.4 | 11.1 |  6.3 |
| Unemployed    |  0   |  0   | 100   |  0   |  0   |

### Distribution by Subgroup: `Country`

![Distribution for Q1 by Country](../data/img/subgroup_ana/Q1_by_Country.png)

| Country        |     1 |     2 |     3 |     4 |     5 |
|:---------------|------:|------:|------:|------:|------:|
| Albania        |   0   |   0   |   0   | 100   |   0   |
| Angola         |   0   |   0   | 100   |   0   |   0   |
| Argentina      |  33.3 |   0   |  66.7 |   0   |   0   |
| Brazil         |   0   |   0   | 100   |   0   |   0   |
| Canada         |   0   |  25   |  50   |  25   |   0   |
| Colombia       |   0   |   0   | 100   |   0   |   0   |
| Denmark        |   0   |   0   | 100   |   0   |   0   |
| France         |  10   |  10   |  80   |   0   |   0   |
| Italy          |   0   |  50   |  50   |   0   |   0   |
| Korea          |   0   | 100   |   0   |   0   |   0   |
| Mexico         |  26.7 |  13.3 |  37.8 |  13.3 |   8.9 |
| Moldova        |   0   |   0   |   0   |   0   | 100   |
| Peru           |   0   | 100   |   0   |   0   |   0   |
| Poland         |   0   |   0   |   0   |   0   | 100   |
| Portugal       |   0   |   0   |  33.3 |  66.7 |   0   |
| Serbia         |   0   |   0   | 100   |   0   |   0   |
| Switzerland    |  15.4 |  26.9 |  41   |  12.8 |   3.8 |
| Tunisia        | 100   |   0   |   0   |   0   |   0   |
| United Kingdom |   0   |   0   |   0   |   0   | 100   |
| United States  |  33.3 |  33.3 |  33.3 |   0   |   0   |

### Distribution by Subgroup: `cluster_profile`

![Distribution for Q1 by cluster_profile](../data/img/subgroup_ana/Q1_by_cluster_profile.png)

| cluster_profile     |    1 |    2 |    3 |    4 |   5 |
|:--------------------|-----:|-----:|-----:|-----:|----:|
| Pragmatic Sharers   | 41.8 | 27.3 | 29.1 |  1.8 | 0   |
| Privacy Maximalists | 10   | 18.3 | 51.7 | 10.8 | 9.2 |
| Tech Optimists      |  7.9 | 27   | 36.5 | 25.4 | 3.2 |

