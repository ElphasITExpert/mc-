# Mc'OCHALLY FLEXI CREDIT

**Flexible Loans. Real Solutions. Better Futures.**

## Project Description

Mc'OCHALLY FLEXI CREDIT is a simple web-based loan management application. It helps a small lending business manage borrowers, monitor loan due dates, calculate repayment amounts, and prepare customer messages for WhatsApp.

The application is built with HTML, CSS, and JavaScript. It uses the browser's local storage to save the owner's PIN and borrower records on the device.

## Features

- **Owner login:** The owner can create a four-digit PIN on first use and use it for later logins.
- **Customer loan application:** Customers can enter their name, phone number, requested loan amount, and repayment period.
- **Loan calculator:** Calculates an estimated repayment amount using the interest formula currently included in the application.
- **Borrower management:** The owner can add borrowers with their phone numbers, loan amounts, and due dates.
- **Borrower search and filters:** Search by borrower name or phone number and filter records by overdue, due soon, or not yet due status.
- **Loan dashboard:** Displays the total amount recorded as owed, the number of overdue loans, and loans due soon.
- **WhatsApp reminders:** Prepares reminder messages and opens WhatsApp so the owner can send them to borrowers.
- **Payment thank-you messages:** Prepares thank-you messages for customers who have paid.

## Technologies Used

- HTML5 — page structure and forms
- CSS3 — styling and layout
- JavaScript — calculations, login flow, borrower records, filtering, and message generation
- Browser Local Storage — saves the PIN and borrower records locally
- WhatsApp click-to-chat links — helps the owner send prepared messages

## Project Files

```text
programiz-html-css/
├── index.html
├── style.css
├── script.js
└── README.md
```

The current application contains most of its page styling and JavaScript inside `index.html`. The separate `style.css` and `script.js` files are present in the project but are not currently linked from the HTML page.

## How to Run the Project

1. Download or clone the project repository.
2. Extract the project folder if it is in a ZIP file.
3. Open the folder.
4. Open `index.html` in a modern web browser.
5. Use the owner login or select **I am a Customer - I want to Apply**.

No server or database installation is required for the current browser-based version.

## How Data Is Stored

The application uses browser Local Storage:

- `mcochally_pin` stores the owner's PIN.
- `mcochally_logged` stores the login status.
- `mcochally` stores borrower records.

Borrower records and the PIN are stored in the browser on the device being used. They are not automatically synchronized across devices.

## Important Notes and Limitations

- This is a front-end demonstration project; it does not currently use a server-side database.
- The login PIN is stored in browser Local Storage and is not secure authentication for a real financial application.
- The customer application form does not currently submit applications to a server or automatically save them to the owner's dashboard.
- The message-generation functions use predefined JavaScript templates. They do not connect to an external AI service.
- WhatsApp messages are prepared for the owner to review and send; the application does not send them automatically.
- The loan calculator uses the interest formula programmed in the application. Confirm that the formula and loan terms match the business's approved lending policy before using it with customers.
- The HTML refers to a `logo.jpg` image. Add that image to the project folder if you want the logo to display.

## Future Improvements

- Connect the application to a secure database.
- Add proper user authentication and password/PIN protection.
- Save customer loan applications and allow the owner to review them.
- Add payment tracking, repayment history, and downloadable reports.
- Support data backup and synchronization across devices.
- Improve mobile responsiveness and accessibility.

## Author

**Mc'OCHALLY FLEXI CREDIT**

Kisumu, Kenya

**Call / WhatsApp:** 0790 885 177

---

*This README describes the current project implementation and its existing limitations.*
# Mc'OCHALLY FLEXI CREDIT

**Flexible Loans. Real Solutions. Better Futures.**

## Project Description

Mc'OCHALLY FLEXI CREDIT is a simple web-based loan management application. It helps a small lending business manage borrowers, monitor loan due dates, calculate repayment amounts, and prepare customer messages for WhatsApp.

The application is built with HTML, CSS, and JavaScript. It uses the browser's local storage to save the owner's PIN and borrower records on the device.

## Features

- **Owner login:** The owner can create a four-digit PIN on first use and use it for later logins.
- **Customer loan application:** Customers can enter their name, phone number, requested loan amount, and repayment period.
- **Loan calculator:** Calculates an estimated repayment amount using the interest formula currently included in the application.
- **Borrower management:** The owner can add borrowers with their phone numbers, loan amounts, and due dates.
- **Borrower search and filters:** Search by borrower name or phone number and filter records by overdue, due soon, or not yet due status.
- **Loan dashboard:** Displays the total amount recorded as owed, the number of overdue loans, and loans due soon.
- **WhatsApp reminders:** Prepares reminder messages and opens WhatsApp so the owner can send them to borrowers.
- **Payment thank-you messages:** Prepares thank-you messages for customers who have paid.

## Technologies Used

- HTML5 — page structure and forms
- CSS3 — styling and layout
- JavaScript — calculations, login flow, borrower records, filtering, and message generation
- Browser Local Storage — saves the PIN and borrower records locally
- WhatsApp click-to-chat links — helps the owner send prepared messages

## Project Files

```text
programiz-html-css/
├── index.html
├── style.css
├── script.js
└── README.md
```

The current application contains most of its page styling and JavaScript inside `index.html`. The separate `style.css` and `script.js` files are present in the project but are not currently linked from the HTML page.

## How to Run the Project

1. Download or clone the project repository.
2. Extract the project folder if it is in a ZIP file.
3. Open the folder.
4. Open `index.html` in a modern web browser.
5. Use the owner login or select **I am a Customer - I want to Apply**.

No server or database installation is required for the current browser-based version.

## How Data Is Stored

The application uses browser Local Storage:

- `mcochally_pin` stores the owner's PIN.
- `mcochally_logged` stores the login status.
- `mcochally` stores borrower records.

Borrower records and the PIN are stored in the browser on the device being used. They are not automatically synchronized across devices.

## Important Notes and Limitations

- This is a front-end demonstration project; it does not currently use a server-side database.
- The login PIN is stored in browser Local Storage and is not secure authentication for a real financial application.
- The customer application form does not currently submit applications to a server or automatically save them to the owner's dashboard.
- The message-generation functions use predefined JavaScript templates. They do not connect to an external AI service.
- WhatsApp messages are prepared for the owner to review and send; the application does not send them automatically.
- The loan calculator uses the interest formula programmed in the application. Confirm that the formula and loan terms match the business's approved lending policy before using it with customers.
- The HTML refers to a `logo.jpg` image. Add that image to the project folder if you want the logo to display.

## Future Improvements

- Connect the application to a secure database.
- Add proper user authentication and password/PIN protection.
- Save customer loan applications and allow the owner to review them.
- Add payment tracking, repayment history, and downloadable reports.
- Support data backup and synchronization across devices.
- Improve mobile responsiveness and accessibility.

## Author

**Mc'OCHALLY FLEXI CREDIT**

Kisumu, Kenya

**Call / WhatsApp:** 0790 885 177

---

*This README describes the current project implementation and its existing limitations.*
