# FDM Expenses Application Server

<details>
<summary>Screenshots</summary>
Login Page

Current Expenses and Status

View Expense Information

Create Expense

Review Expenses (Manager)

View Profile

Mobile View

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