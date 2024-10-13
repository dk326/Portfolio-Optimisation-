# Portfolio-Optimisation-

**About Project**

This project was done as an assessment for the unit Decision modelling. The excel spreadsheet was developed to build and optimisation model subject to certain criteria. The optimization techniques used are Linear Programming and sensitivity analysis, Integer Linear Programming and Non-Linear Programming. The project also uses real historic data sourced from https://au.finance.yahoo.com. 

**Linear Programming Model**

<img width="576" alt="Screenshot 2024-10-13 at 2 25 33 PM" src="https://github.com/user-attachments/assets/6b98242c-bcbf-4df3-965f-680fa53c100f">

Conceptual model of the problem 

<img width="671" alt="Screenshot 2024-10-13 at 2 50 26 PM" src="https://github.com/user-attachments/assets/66bc4c04-ab17-4b3d-b917-a685a426d9a9">


The portfolio is subject to constraints of having certain weights in certain risk categories. Further, the risk of a portfolio is calculated based on the standard deviation of monthly returns for 36 months. 

The excel spreadsheet was developed with solver. 

<img width="634" alt="Screenshot 2024-10-13 at 2 28 25 PM" src="https://github.com/user-attachments/assets/777a915f-b6da-4cc6-8325-cb3115ca2b76">

- A maximum return of 0.38% is the optimum solution from this portfolio. 

- The solution satisfies all the constraints and the total portfolio risk is 4.46%

**Integer Linear Programming Model**

<img width="549" alt="Screenshot 2024-10-13 at 2 31 24 PM" src="https://github.com/user-attachments/assets/227c7ffc-cb69-4e3f-978b-5f186d36fd78">

Conceptual model of the problem 

<img width="702" alt="Screenshot 2024-10-13 at 2 51 30 PM" src="https://github.com/user-attachments/assets/5921ccbf-496e-4ff5-b189-5d550da28835">


This portfolio is an integer linear programming model where the model will solve what portfolios should be invested based on the mentioned restrictions. In this problem, the required amount of stock options is 6.

The following is the excel spreadsheet which is built with solver.

<img width="694" alt="Screenshot 2024-10-13 at 2 35 20 PM" src="https://github.com/user-attachments/assets/fcb652ff-11be-4112-8b90-d36797be5976">


- If the company decides to invest equal weights in only 6 portfolios while satisfying the given constraints the maximum portfolio return would be 1.54%.
- To achieve this optimal solution, it would invest in stocks AMC, ALU, LLC, MGR, APA and TLS.

**Maximising returns subject to a given risk**

This model is built with the objective of maximising returns subject to 9% risk. Therefore, the model will provide the weights of investment in each stock which will provide the greatest returns subject to 9% risk. 

<img width="569" alt="Screenshot 2024-10-13 at 2 41 40 PM" src="https://github.com/user-attachments/assets/d030abb5-8031-4561-bf0a-72cda4df96ad">

Conceptual model of the problem

<img width="594" alt="Screenshot 2024-10-13 at 2 52 37 PM" src="https://github.com/user-attachments/assets/e5e594d7-d812-4773-86a6-eac775e056a6">


The following excel spreadsheet was developed with the use of solver.

<img width="745" alt="Screenshot 2024-10-13 at 2 42 20 PM" src="https://github.com/user-attachments/assets/38a6c84f-6b71-4979-89c4-7a576fa665c4">

- If the company decides maximize portfolio returns subject to a 9% risk constraint, the optimal solution will be to invest 99.55% in LLC stocks and 0.45% in APA stocks. 
- The maximum portfolio return will be 1.75% and the portfolio will have 9.00% risk.


**Minimizing the portflio risk subject to a given return**

This portfolio is developed with the objective of minimizing the portflio risk subject to a given return. The selected return for this portfolio is 1%. 

<img width="592" alt="Screenshot 2024-10-13 at 2 43 37 PM" src="https://github.com/user-attachments/assets/a93a8566-89e0-4df1-90e0-bc8cb0e7745f">

Conceptual model of the problem 

<img width="674" alt="Screenshot 2024-10-13 at 2 53 20 PM" src="https://github.com/user-attachments/assets/eea4e781-090d-489a-9076-b0380f24f85d">


The excel spreadsheet is illustrated below. 

<img width="783" alt="Screenshot 2024-10-13 at 2 45 18 PM" src="https://github.com/user-attachments/assets/876b5f45-fdb5-427e-883d-ba7c39081697">


- If the company decides minimize portfolio risk subject to a 1% minimum returns constraint, the optimal solution will be to invest 34.43% in AMC, 49.79% in LLC and 15.78% in APA stocks.
- The maximum portfolio return will be 1.00% and the portfolio will have 5.31% risk.
- Interestingly, nearly half of the investment will be in LLC which is a high-risk stock.

**Please note that the excel spreadsheet and presentation will be made available upon request.*
