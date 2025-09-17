# QA Engineer Challenges

This repository contains a **take-home assignment** designed for **Junior QA candidates**.

The goal is to evaluate practical QA skills in writing test cases, reporting bugs, and suggesting improvements.

---

## 👩‍💻 Scenario

You have joined a **fast-food startup** as a QA Engineer.

The company is building a new **mobile ordering system**, but the app is not ready yet.

Your job is to **test the system based only on the requirements below**.

### User Stories

1. As a user, I can order a burger with fries.
2. As a user, I can cancel my order before payment.
3. As a user, I receive a receipt after checkout.

---

## 📋 Your Tasks

1. **Write test cases** for each user story.
    - You can use any format (Excel, Word, Markdown, etc.).
    - Suggested fields: **Test ID, Title, Steps, Expected Result**.
2. **Suggest 2-3 improvement** to the system (something not in the requirements).

---

## 📡 Bonus Task — API Execution Report

The system exposes a **mock Order API** for manual testing on production:

**Production URL:** `https://qa-mock-food-api-production.up.railway.app`

**API Reference / Documentation:** [https://cymi7ri538.apidog.io](https://cymi7ri538.apidog.io/)

**Endpoints:**

```

GET /orders
POST /orders
GET /orders/:id
PATCH /orders/:id
DELETE /orders/:id
PATCH /orders/:id/cancel
```

> ⚠️ Note: The API contains 3 intentional bugs for you to identify.
> 

### Your Tasks

1. Perform **manual API requests** using Postman, cURL, or another tool.
2. Include **actual response** and **status (Pass/Fail)** in your execution report.
3. Identify and report **any bugs** observed while executing the API.
4. Suggest **2-3 improvements** for the API design or behavior.

---

## 📦 Deliverables

Submit **a single document** that contains:

- ✅ Test cases for the user stories
- ✅ API execution report (with actual responses and pass/fail status)
- ✅ Bug reports found while executing the API
- ✅ Improvement suggestions

---

## ✅ Evaluation Criteria

- Test cases are clear, logical, and cover all user stories.
- Bug reports include enough detail to reproduce the issue.
- API execution report demonstrates understanding of request/response behavior.
- Improvement suggestions show critical thinking beyond the given requirements.

---

## 🚀 How to Submit

You can submit your solution **in either of the following ways**:

1. **Forked repository URL**
    - Fork this repository.
    - Add your solution document and media files.
    - Send us the **URL of your forked repository**.
2. **Email**
    - Send your solution document as an attachment to: [**burhan.aghazada@acb.az**](mailto:burhan.aghazada@acb.az)
    - Include your **full name** in the email subject.

⚠️ **Deadline:** 24 September 2025, 12:00

---

## 💡 Notes

- There are no “perfect” answers — we want to see **how you think**.
- Include actual API responses in your execution report (copy JSON or screenshots).
- Use simple language and clear structure.
- If you’re new to API testing, you can install [Postman](https://www.postman.com/downloads/) (recommended).
- Use the [API Reference](https://cymi7ri538.apidog.io/) to understand request/response formats and endpoints.
