# 🎾 RM Tennis Booking System

A web-based tennis lesson booking and confirmation system designed to simplify communication between a tennis coach and their clients. The project was developed from a real-world need: as a tennis coach, I wanted a simple way to propose lesson dates and times, allow clients to confirm their lesson using a unique booking code, and maintain an organised coaching schedule.

## 🌐 Live Demo
[View the RM Tennis Booking System](https://rangelmeto02.github.io/rm-tennis-booking-system/)

### Demo Access
To explore the customer booking experience:
**Booking code:** `DEMO02`
To explore the coach dashboard:
**Demo PIN:** `1234`
> The public portfolio version uses fictional demonstration data and does not connect to the live customer database.
> 
## ✨ Features

### Customer Booking
Clients roles include:

- Enter a unique six-character booking code
- View their proposed lesson date and time
- View the price of their lesson
- Confirm the lesson
- See the confirmation status
- View lesson notes from the coach

### Coach Dashboard
The coach can:

- Access a dedicated schedule area
- Create new lesson bookings
- Specify the customer, date, time, price and optional notes
- Generate unique booking codes
- View upcoming lessons grouped by date
- View lessons in chronological order
- See **TODAY** and **TOMORROW** indicators
- Track pending and confirmed lessons
- Mark lessons as paid or unpaid
- Copy booking codes
- Cancel lessons
- View past and cancelled bookings

## 🛠 Technologies Used

- **HTML5** — page structure and application interface
- **CSS3** — responsive layout, custom styling and RM Tennis branding
- **JavaScript** — booking logic, interface rendering and user interactions
- **Firebase Firestore** — database used by the private working version to persist lesson information
- **GitHub** — source control and project hosting
- **GitHub Pages** — deployment of the public portfolio demonstration

The application was intentionally built without a front-end framework to strengthen my understanding of core HTML, CSS and JavaScript concepts.

## 🔥 Firebase Integration
The private working version of the application integrates with **Firebase Firestore**.
Firestore allows lesson information to persist across devices rather than existing only within the browser.
Lesson records can contain information such as:

- Booking code
- Customer name
- Date
- Time
- Price
- Lesson notes
- Confirmation status
- Payment status

For security and privacy, the version published in this repository is a **portfolio demonstration** and does not connect to the live Firestore database. Instead, it contains fictional sample lessons that allow employers and other visitors to explore the application's functionality safely.

## 🔐 Security Considerations
The current coach PIN system is a client-side demonstration and should not be considered production authentication. A production version would replace this with a proper authentication system such as **Firebase Authentication**, together with appropriately restricted **Firestore Security Rules**. Real customer information and live Firebase project configuration are intentionally excluded from this public repository. This separation allows the application's functionality to be demonstrated without exposing private customer data or the working database.

## 🎨 Design
I designed the interface around an **RM Tennis** visual identity using a navy and cream colour palette.
The interface includes:

- RM Tennis branding
- Tennis-inspired visual elements
- Responsive booking cards
- Clear date, time and price presentation
- Status badges
- A tennis-court-inspired header motif
- Mobile-friendly layouts

The aim was to keep the interface simple enough for clients to use quickly on their phones while giving the coach a practical schedule-management interface.

## 💡 What I Learned

Building this project gave me practical experience turning a real-world problem into a working software solution.
In particular, I developed my understanding of:

- Structuring a complete front-end application
- Manipulating the DOM with JavaScript
- Handling application state
- Generating and validating booking codes
- Rendering data dynamically
- Sorting and grouping records by date and time
- Connecting a front-end application to a cloud database
- Reading and writing Firestore documents
- Separating development, private and public demonstration environments
- Considering authentication and database security
- Debugging UI and JavaScript issues
- Iteratively improving an application based on actual usage requirements
- Deploying a web application using GitHub Pages

One of the most valuable aspects of the project was developing it iteratively. Features such as lesson pricing, customer confirmation, chronological schedule grouping and date indicators were introduced as the requirements became clearer.

## 🚀 Potential Future Improvements
Possible future development includes:

- Firebase Authentication for secure coach access
- More restrictive Firestore Security Rules
- Online payments
- Lesson duration
- Court/location information
- Booking editing and rescheduling
- Automated WhatsApp or email confirmation messages
- Calendar integration
- Customer cancellation/rescheduling requests
- Improved mobile dashboard functionality

## 📁 Project Structure
```text
rm-tennis-booking-system/
│
├── index.html
└── README.md
```

The application currently uses a single-page architecture, with the HTML structure, CSS styling and JavaScript application logic contained within `index.html`.

## 👤 Author
**Rangel Metodiev (ME)**

Graduate student and tennis coach interested in software development, technology and building practical digital solutions to real-world problems. Completed undergraduate degree in Computer Science and Maths, as well as a Masters in Cyber Security.


## 📄 Project Status
The core booking and scheduling functionality is complete.
The GitHub Pages deployment is a portfolio demonstration using fictional data. A separate private version integrates with Firebase Firestore for persistent lesson storage.
