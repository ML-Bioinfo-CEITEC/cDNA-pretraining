# Results

## Accuracy

| K   |      Stride 1     |  Stride K |
|----------|-------------:|------:|
| 3 | 0.875  |  0.867 |
| 4 | 0.887  | 0.871  |
| 5 |  0.890 |  0.854 |
| 6 |  0.898 |  0.827 |
| 7 | 0.938  | 0.847  |
| 8 | **0.947**  | 0.832  |
| 9 |  0.906 |  0.804 |
## F1

| K   |      Stride 1     |  Stride K |
|----------|-------------:|------:|
| 3 |  0.885 |  0.877 |
| 4 | 0.893  |  0.881 |
| 5 | 0.898  | 0.864  |
| 6 | 0.906  | 0.846  |
| 7 |  0.943 |  0.854 |
| 8 | **0.951**  | 0.840  |
| 9 |  0.916 |  0.802 |

Batch sizes needed to be modified for K=7,8,9. The experiment for K=9 was restarted due to disk issues (the model is so big you need to avoid saving it too often).