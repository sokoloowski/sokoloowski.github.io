# Ćwiczenia z Logiki

## Ćwiczenia 4 - zestaw A - Rachunek zdań. Dowodzenie twierdzeń. Logiczna konsekwencja.

### 1. Zbadać dowolną metodą, czy następujące formuły są spełnialne i czy są tautologiami:

1. ![(p => q) or r) and (not p => r)](<https://render.githubusercontent.com/render/math?math=((p\Rightarrow{q})\lor{r})\land(\lnot{p}\Rightarrow{r})>)

    | ![p](https://render.githubusercontent.com/render/math?math=p) | ![q](https://render.githubusercontent.com/render/math?math=q) | ![r](https://render.githubusercontent.com/render/math?math=r) | ![(p => q)](https://render.githubusercontent.com/render/math?math=p\Rightarrow{q}) | ![(p => q)](<https://render.githubusercontent.com/render/math?math=(p\Rightarrow{q})\lor{r}>) | ![not p => r](https://render.githubusercontent.com/render/math?math=\lnot{p}\Rightarrow{r}) | ![(p => q) or r) and (not p => r)](<https://render.githubusercontent.com/render/math?math=((p\Rightarrow{q})\lor{r})\land(\lnot{p}\Rightarrow{r})>) |
    | :-: | :-: | :-: | :-: | :-: | :-: | :-: |
    |  0  |  0  |  0  |  1  |  1  |  0  |  0  |
    |  0  |  0  |  1  |  1  |  1  |  1  |  1  |
    |  0  |  1  |  0  |  1  |  1  |  0  |  0  |
    |  0  |  1  |  1  |  1  |  1  |  1  |  1  |
    |  1  |  0  |  0  |  0  |  0  |  1  |  0  |
    |  1  |  0  |  1  |  0  |  1  |  1  |  1  |
    |  1  |  1  |  0  |  1  |  1  |  1  |  1  |
    |  1  |  1  |  1  |  1  |  1  |  1  |  1  |

2.
