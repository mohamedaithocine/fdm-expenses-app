# FDM Expenses Application
[![HTML](https://img.shields.io/badge/HTML-%23E34F26.svg?logo=html5&logoColor=white)](#)
[![CSS](https://img.shields.io/badge/CSS-639?logo=css&logoColor=fff)](#)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=000)](#)
[![Vite](https://img.shields.io/badge/Vite-646CFF?logo=vite&logoColor=fff)](#)
[![Postgres](https://img.shields.io/badge/Postgres-%23316192.svg?logo=postgresql&logoColor=white)](#)
[![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=fff)](#)
[![Flask](https://img.shields.io/badge/Flask-000?logo=flask&logoColor=fff)](#)
<details>
<summary>Screenshots</summary>
  
### Login Page
<img width="1919" height="936" alt="Expense-Login" src="https://github.com/user-attachments/assets/2d969c21-182c-43a5-bbd7-93befa3612e3" />

### View All Expenses
<img width="1909" height="944" alt="Expense-Tracker" src="https://github.com/user-attachments/assets/c981cd99-d239-422e-905d-010360714b55" />

### View Selected Expense Information
<img width="1918" height="941" alt="Expense-ViewExpense" src="https://github.com/user-attachments/assets/261f2e26-71ed-42e7-b0ef-d0fcffe795fd" />

### Create Expense
<img width="1918" height="943" alt="Expense-Form" src="https://github.com/user-attachments/assets/af6410a4-99ec-4458-aaaa-244f68d032f1" />

### Review Expenses (Manager)
<img width="1912" height="949" alt="Expense-ManagerReview" src="https://github.com/user-attachments/assets/4c01a2ad-170b-4b51-9373-b65f3970b7aa" />
<img width="1915" height="944" alt="Expense-MangerApproveDeny" src="https://github.com/user-attachments/assets/5281f45e-9746-4ece-a8f6-9be96a77d2c0" />

### View Profile
<img width="1917" height="943" alt="Expense-Profile" src="https://github.com/user-attachments/assets/d91aecff-51e3-408f-9403-038924ef77fb" />

### Mobile View
<img width="461" height="842" alt="Expense-PhoneVersion" src="https://github.com/user-attachments/assets/a682b93b-b8b3-4c18-8e9b-6409deb3ab00" />

</details>

## Installing dependencies
Clone the repository, then install the dependencies by running the following command:

### Frontend

- Run <code>npm install</code> in <code>/frontend/</code>
```
npm install
```

- In <code>/frontend/</code> run <code>npm run dev</code>
```
npm run dev
```

### Server
- Direct yourself to the directory <code> /backend/ </code>
- Install the requirements

```
$ pip install -r requirements.txt
```

### Usage

Enter your PostgreSQL database URI in a .env file in the following format:

```env
DATABASE_URI=postgresql+psycopg://user:password@host:port/database_name
```

Also, enter a mail username and password in the .env file in the following format:

```env
MAIL_USERNAME=YOUR_EMAIL_ADDRESS
MAIL_PASSWORD=YOUR_EMAIL_PASSWORD
```

Run the following to start the application:

```
$ flask run
```

Use the ```--debug``` flag for debugging mode.

## Members
- Aivaras Barcys (a.barcys@se22.qmul.ac.uk)
- Armin Shahnami (a.shahnami@se22.qmul.ac.uk)
- Ayotunde Ogunnaiya (a.ogunnaiya@se22.qmul.ac.uk)
- Chee-Ho Nim (c.nim@se22.qmul.ac.uk)
- Konrad Vincler (k.d.vincler@se22.qmul.ac.uk)
- Mohamed Ait-Hocine (m.ait-hocine@se22.qmul.ac.uk)
- Sefa Yildirim (s.a.yildirim@se22.qmul.ac.uk)
