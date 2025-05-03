# React Form with Formik & Yup (Vite Project)

This project is a simple signup form built using **React**, **Formik**, and **Yup** in a **Vite** development environment. It demonstrates real-time form validation using Yup schemas.

## 🚀 Features

* Built with **React + Vite**
* Form state management using **Formik**
* Validation using **Yup**
* Real-time error feedback
* Fields:

  * **Name** – Required, 2-50 characters
  * **Email** – Required, valid format
  * **Password** – Required, minimum 8 characters, includes letters, numbers, and special characters

## 🛠 Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/yourusername/react-formik-form.git
   cd react-formik-form
   ```

2. Install dependencies:

   ```bash
   npm install
   ```

3. Start the development server:

   ```bash
   npm run dev
   ```

## 📂 File Structure

```
src/
│
├── components/
│   └── SignupForm.jsx   # Main form component
│
└── App.jsx              # Renders the form
```

## 🧪 Technologies Used

* React
* Vite
* Formik
* Yup

## ✅ Password Validation Rule

The password must match the following criteria:

* Minimum 8 characters
* At least one alphabet (`a-z` or `A-Z`)
* At least one number (`0-9`)
* At least one special character (`@, $, !, %, *, #, ?, &`)