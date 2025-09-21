# Opening Range Breakout – First Intraday Strategy

This project is my **first attempt at building an intraday trading strategy**.  
The main goal is to practice **Git/GitHub** and get hands-on experience with **quantitative finance in Python**.

## Strategy
- Define the first 5 minutes after market open as the *opening range*  
- If price > daily open → go **long**  
- If price < daily open → go **short**  
- Stop-loss = opposite side of the range  
- Take-profit = 10 × risk distance  
- Close all positions before market close  

## How to Run
```bash
pip install -r requirements.txt
