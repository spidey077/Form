# 🏆 Futsal Winner Prediction Form

A stylish and responsive web form for collecting Futsal winner predictions from students.  
Submissions are securely sent to a connected **Google Form**, and repeat submissions are prevented using `localStorage`.

🔗 **Live Demo:** (https://spidey077.github.io/Form/)

---

## 📌 Overview

This web form allows students to enter their **name**, **class**, and **predicted winning department**.  
Once submitted, the form sends the data to a Google Form endpoint using the `fetch` API and disables the form from being used again on the same browser by storing a flag in `localStorage`.

---

## 🛠️ Technologies Used

- HTML5  
- CSS3  
- JavaScript (ES6)  
- Google Forms (for backend submission)  
- localStorage (to prevent duplicate entries)

---

## 💡 Features

- 🧾 Input fields: Name, Class, and Winner (textarea)  
- 🧠 Smart duplicate submission prevention using localStorage  
- 📤 Google Form integration via fetch and `FormData`  
- 📱 Mobile-friendly responsive layout  
- ✨ Clean gradient background with modern UI  
- 🟢 Success message shown after submission  
- 🔒 Button disabled after submission to prevent resubmission

---

## 🖥️ How It Works

1. User fills in their name, class, and predicted winner.
2. When they click **Submit**, the form:
   - Sends data to a connected Google Form endpoint.
   - Stores a flag in `localStorage` (`formSubmitted = true`).
   - Disables the submit button and shows a confirmation message.
3. If the form has already been submitted (on the same browser), it shows a message and disables the form.

---

## 📬 Contact

For feedback or inquiries:

📧 **Email:** imdadullahchishti@gmail.com

---

> Created by **Imdadullah**
