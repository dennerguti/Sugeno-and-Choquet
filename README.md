Here are all the equations related to Sugeno and Choquet comparative models, emphasizing the importance of each variable and parameter for the work. The letter X represents the time measure conducted in sliding windows variations ranging from size 5 to 130, while the letter Y represents the weight values assigned to the mathematical models SMA, WMA, PMA, EMA, and HMA. These weights are distributed according to the window size to ensure that the sum always results in 1. This ensures that the analyses are concise and accurate. These fundamental equations are essential for understanding and analyzing the results; they provide a solid foundation for the comparative evaluation of the studied models.

Furthermore, the equations provide a quantitative framework for evaluating the effectiveness and performance of each model in various time scenarios. They provide a systematic way of understanding how variations in time windows impact the weighting of various mathematical models, providing valuable insights into their adaptability and robustness. These equations help ensure the transparency and replicability of the analyses performed by detailing each step of the analytical process, from data collection to model application. By using them, it's possible to thoroughly compare the Sugeno and Choquet models and determine their advantages and disadvantages in different usage contexts. Finally, the equations are essential for the theoretical grounding and practical application of this work, as they serve as the basis for researching and interpreting the results.


# T-norms

## Minimum  
<p align="center">$TM (x, y) = \min\{x, y\}$ </p>

## Algebraic Product  
<p align="center">$TP (x, y) = xy$ </p>

## Łukasiewicz 
<p align="center">$TL(x, y) = \max\{0, x + y - 1\}$ </p>

## Hamacher Product
$$
\ THP (x, y) =
  \begin{cases}
    0       & \quad \text{if x = y = 0} \\
    \frac{{xy}}{{x + y - xy}}  & \quad \text{otherwise} 
  \end{cases}
\$$

### Overlap functions
| Name/Reference  | Definition |
| ------------- | ------------- |
| (nome)  | OB (x, y) = min{x√y, y√x} |
| Cuadras-Augé copula   | OmM (x, y) = min{x, y} max{x2, y2}  |
| (nome) |  Oα (x, y) = xy(1 + α(1 − x)(1 − y)),  α ∈ [−1, 0[ ∪ ]0, 1] |
| (nome) | 
| Geometric Mean |
| Harmonic Mean |
| Sine |

### Copulas that are neither t-norms nor overlap functions
| Name/Reference  | Definition |
| ------------- | ------------- |
| FGL  |   |
| FBPC  |  |



### Left 0-absorbent (0, 1)-pre-aggregation functions
| Name/Reference  | Definition |
| ------------- | ------------- |
| FNA  |   |
| FNA2 |  |
