# Aid-Ally-Donation-Management
Aid Ally is a web-based donation management platform designed to connect generous donors with people and organizations in need. It simplifies the product donation process through a structured system involving donors, agents, and admins, ensuring every contribution is tracked from pickup to delivery.
---   

##  Key Features

-  Donor dashboard to schedule pickups and track donations
-  Agents manage pickups and update status
-  Admins control accounts and monitor the entire donation flow
-  Reporting system for transparency and accountability
-  Live tracking system for donation progress (future work)
-  Anonymity option for donors (future work)

---

##  User Roles

| Role     | Responsibilities |
|----------|------------------|
| **Donor** | Browse requests, donate items, schedule pickup, track donations |
| **Agent** | Collect and deliver donations, update statuses |
| **Admin** | Manage users, routes, donations, and reports |

---

##  Tech Stack

| Technology | Description |
|------------|-------------|
| **Node.js** | Backend runtime |
| **Express.js** | Web framework |
| **MongoDB** | NoSQL database |
| **EJS / Handlebars** | Template engine |
| **dotenv** | Environment config |
| **CSS / Bootstrap** | Frontend styling |

---

##  Project Structure

```bash
Aid-Ally/
├── backend/
│   ├── routes/
│   ├── models/
│   ├── middleware/
│   ├── config/
│   └── app.js
├── views/
│   ├── donor/
│   ├── agent/
│   ├── admin/
├── assets/
│   └── style.css, scripts.js
├── .env
└── README.md
