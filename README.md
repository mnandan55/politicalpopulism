# Political Economy Simulator  

An interactive **Python-based tool** to analyze political populism based on economic and institutional factors.  
It compares the **populist bias** of **honest vs. corrupt politicians** as a function of **voter preferences, interest group influence, and corruption costs**.

## Theory Behind the Model  
The model is based on strategic decision-making where:  

- **α (alpha)**: Weight on **voter’s benefit**  
- **β (beta)**: Weight on **interest group’s benefit**  
- **b**: Interest group's **bliss point**  
- **W**: Gain from **winning office**  
- **μ (mu)**: Proportion of **honest politicians**  
- **χ (chi)**: Bargaining power of **corrupt leaders**  
- **K**: Cost of **corruption**  

It solves for:  
- **p** → **Populist bias of an honest politician**  
- **q** → **Populist bias of a corrupt politician**  

This project is inspired by **Acemoglu, Egorov, and Sonin (2013)**,  
*"A Political Theory of Populism"*, published in **The Quarterly Journal of Economics**.  
[Read the full paper here](https://doi.org/10.1093/qje/qjs077).  

## How to Use  

### 1. Install Dependencies  
```bash
pip install numpy matplotlib seaborn scipy ipywidgets
