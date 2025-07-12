Perfect! Since your project is now **live at**:

🔗 [https://ca-ching-expenses-app.s3.ap-south-1.amazonaws.com/index.html](https://ca-ching-expenses-app.s3.ap-south-1.amazonaws.com/index.html)

Let me update the **`README.md` demo link** for you:

---

### ✅ Final `README.md` (clean version, no emojis):

```markdown
# Ca-ching Expenses — Serverless Expense Tracker

Ca-ching Expenses is a stylish, lightweight, serverless web application built to help users effortlessly track their spending across categories over time. Built with HTML/CSS/JS, powered by AWS Lambda, API Gateway, DynamoDB, and hosted via S3 + CloudFront.

---

## Live Demo

[Click here to try it out](https://ca-ching-expenses-app.s3.ap-south-1.amazonaws.com/index.html)

---

## Architecture Overview

```plaintext
Frontend (S3 + CloudFront)
        |
        ▼
JavaScript fetch()
        |
        ▼
API Gateway (HTTP API)
        |
        ▼
Lambda Function (Python)
        |
        ▼
DynamoDB (NoSQL DB)
```

---

## Features

- Add daily expenses by date, category, amount, and note
- Real-time summary dashboard
  - Total spent
  - Most spent category
  - Weekly expense
- Donut chart of category-wise spending
- Light/Dark mode toggle
- Fully serverless and scalable (no backend server required)

---

## Tech Stack

| Tech            | Used For             |
|----------------|----------------------|
| HTML/CSS/JS     | Frontend UI          |
| Chart.js        | Donut chart          |
| AWS S3          | Hosting static files |
| AWS API Gateway | HTTP API             |
| AWS Lambda      | Backend logic        |
| AWS DynamoDB    | NoSQL storage        |

---

## How it works

1. HTML file is hosted on AWS S3
2. JS sends a POST request with expense data to API Gateway
3. API Gateway triggers Lambda
4. Lambda stores data into DynamoDB
5. JS reads and updates UI from local data (can be extended to fetch from DB)

---

## Screenshots

| Summary | Add Expense |
|--------|-------------|
| ![summary](./screenshots/summary.png) | ![add](./screenshots/add.png) |

_(Upload your screenshots or remove this section)_

---

## Future Enhancements

- Show monthly/yearly expense trends
- Fetch historical data from DynamoDB
- Add user login (Cognito)
- Make it PWA and mobile-friendly

---

## Folder Structure

```
ca-ching-expenses
 ┣ index.html
 ┗ README.md
```

---

## Made by

**Ananya Soni**  
Building cloud-powered solutions with impact

---

## License

MIT License — Free to use and modify.
```

---

Let me know if you'd like this in a downloadable `.md` file or need a GitHub commit template.
