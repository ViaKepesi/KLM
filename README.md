# README

## About the Assignment

We are asking you, a data scientist in the airline industry, to share and explain your solutions to the challenges in this assignment. The assignment consists of two parts:
1, Approach evaluation: Data science Usecases
2, Assignment: ESG - Gender Pay Gap

Your inputs will be used in our next (technical) interview, so it should be a good representation of how you work on a daily basis and it should display your ability. We are interested in your argumentation and the choices that you make. 

Try to time-box your effort to 2-4 hours. This can mean that you will not deliver fully complete answers to the challenges, due to the time constraints. 

Please let us know in case of questions. Enjoy taking the assignment! 

## Data science usecases
In the following slides we give three different business questions we are dealing with in our daily business. Pick one business question and explain how you would approach it. 

Think of questions to ask to the business, possible solutions to the question, data you would use, problems/challenges you might encounter, models/methods that you would consider, technology you would use, etc.

---
## Data Science Use Cases - Job evaluation and recruitment

In KLM we have many different jobs and every job should have a job description and a salary scale attached to it. Then if we would like to recruit someone for the specific job a vacancy text needs to be written by the hiring manager. This is currently all manual work:
1, Hiring manager creates new function with description
2, Job evaluation consultant evaluates function based on the description and attaches a salary scale
3, When there is an open vacancy for the job the hiring manager creates the vacancy text with the job role description, requirements, environment and benefits.
4, Candidates hand in resumes and motivation which are evaluated by the hiring manager.
This process takes a lot of time of our managers and a lot of them find it realy hard to come up with the right text that leads to the best hires.
Now the business has requested you to see how generative AI can help the managers and job evaluation consultants to do this job in a more efficient way and get support in the creation of these descriptions.

### Deliverables

- **PDF**: Covers the flow of working metodology, each step paired with the questions that need to be clarified in oder to outline the scope. 

---
## ESG: Gender Pay Gap

Soon we have to start reporting on ESG and one of the KPIs is the gender pay gap. The business came to us with the question to calculate the gender pay gap for our employees and study the reasons behind this possible gender pay gap.
They provided a dataset to us in the csv file that you found with this case description.
You can find the definitions of the data in the next slide. In your answers to the following questions provide the code you used and explain in detail the steps you took to come to this conclusion
- What are your general observations when looking into the data?
- Provide the solution and model(s) that answers this question.
- What is your suggestion to the business on the communication of these numbers?


### Provided Data

A CSV file with employee details:

- **Sex** (`Man` or `Vrouw`)  
- **Function** (employee’s role; not available for Ground CLA domain)  
- **Years of services** (how long they have been with the company)  
- **Km_transport** (distance from home to office in kilometers)  
- **Nationality** (`NL` or `not NL`)  
- **Contract percentage** (share of full-time hours)  
- **Base salary** (monthly salary)  
- **clob** (cluster line of business: grouping of departments)  
- **Nr_managers_above** (number of managers above the employee)  
- **Manager** (whether the employee is a manager)  
- **direct** (indirect (0) or direct (1) effect on operations)  
- **CLA domain** (collective labor agreement domain, each with its own salary rules)  
- **Grading** (salary scale)  
- **Martialstatus** (relationship/separated/single)


### Deliverables

- **Code**: Python scripts or notebooks showing data loading, cleaning, EDA, and modeling.  
- **Findings**: A concise summary of key results (e.g., raw vs. adjusted gap, top drivers of salary).  
- **Communication**: How you’d present your findings to business leaders, focusing on clarity and recommendations.

---

## How to Use / Run

1. **Clone or Download** this repository.  
2. **Install Requirements** (if a `requirements.txt` is provided):  
   ```bash
   pip install -r requirements.txt
