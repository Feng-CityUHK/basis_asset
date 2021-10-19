# basis_asset

We try to replicate [Basis Assets](https://academic.oup.com/rfs/article/22/12/5133/1577250?login=true)

## What we do

We provided a toolkit to evaluate and compare two sets of portfolios, in asset pricing and investment research.

1.  Sharpe Ratio Simulation and Covatiance Matric Condition

2.  GRS Test

3.  Cross-Sectioal Regression

4.  Portfolio Spanning Test

## How to use the package

- Input:
    - pd.DataFrame(): 
        - A group of assets: P1
        - Another group of assets: P2
    - Dict{}
        - Factors Models
        ```
        F = {
            'CAPM': pd.DataFrame(),
            'FF3': pd.DataFrame(),
            ...
        }
        ```
- Output: Tables and Figures in the paper.