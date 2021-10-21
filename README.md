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
        - Portfolios 
        ```
        P= {
            'ME10': pd.DataFrame(),
            'FF25': pd.DataFrame(),
            ...
        }
        ```
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

## Miscilaneous

- Data download source: 
    -   [Ken French Website](http://mba.tuck.dartmouth.edu/pages/faculty/ken.french/data_library.html)
    -   [Q Factors Website](http://global-q.org/factors.html)