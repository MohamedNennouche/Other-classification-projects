## Classification of the state of the ionosphere
### Purpose of the project
The goal of this project is to detect through sonar data the state of the ionosphere: 
- Good  (g)
- Bad (b)

### Achieved performance 
#### Without resampling
|   Algorithm   |   Accuracy (%)|  F1 score (%) |
|---      |:-:        |:-:        |
|   KNN   |   93.4   |   92.23   |
|   SVM   |   95.28   |   94.45   |
|   Random Forrest   |   94.34   |   93.5   |
#### With resampling
By rebalancing classes: 

|   Classes   |   Before resampling |  After resampling |
|---      |:-:        |:-:        |
|   g   |   225   |   225   |
|   b   |   126   |   225   |

We then find the following results: 

|   Algorithm   |   Accuracy (%)|
|---      |:-:        |
|   KNN   |   98.52   |
|   SVM   |   96.3   |
|   Random Forrest   |   97.78  |