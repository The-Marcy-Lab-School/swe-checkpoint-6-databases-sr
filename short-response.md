# Short Response: Databases Checkpoint

Answer each question below in complete sentences. Aim for 3–5 sentences per answer — enough to show that you understand the concept, not just that you memorized a definition. Use the exact terms and concepts from the lessons, but write in your own words. Specific examples and analogies are encouraged.

---

## Question 1

What is the difference between **authentication** and **authorization**? Give a concrete example of each in the context of a fullstack web application.

**Your answer:**

---

## Question 2

Why should passwords **never** be stored as plaintext in a database? What technique do we use instead, and how does it allow a server to verify a password without ever storing the original?

**Your answer:**

---

## Question 3

What is a **session**? What is a **cookie**? How do they work together to keep a user "logged in" across multiple HTTP requests?

**Your answer:**

---

## Question 4

A frontend can hide a "Delete Account" button from users who aren't logged in. Why isn't that enough to protect the `DELETE /api/users/:id` route on the server? What does the backend do instead?

**Your answer:**

---

## Question 5

What is **SQL injection**? Explain what makes the code below unsafe, then describe how parameterized queries fix the problem.

```js
// Unsafe — never do this!
pool.query(`SELECT * FROM users WHERE username = '${username}'`);
```

**Your answer:**

---

## Question 6

When should a server respond with **`401 Unauthorized`** vs **`403 Forbidden`**? Describe the condition that triggers each and give an example scenario for each.

**Your answer:**

---

## Question 7

What is the **`/api/auth/me`** endpoint pattern? What does it return, when does the frontend call it, and what problem does it solve for single-page applications?

**Your answer:**

---

## Question 8

When you add a new **user-owned resource** (for example, bookmarks) to an existing fullstack application, which layers of the app need to change? List each layer and briefly describe what changes at that layer.

**Your answer:**
