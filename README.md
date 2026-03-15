🌍 Afar Digital Health API (Mock)

Afar Digital Health API is an open‑source mock backend designed to help developers, students, and organizations prototype and test digital health solutions without relying on real patient data. It provides standardized RESTful endpoints for patients, facilities, appointments, and authentication, following clean architecture and modern backend best practices.

This project is safe for public use — all data is synthetic and anonymized.

---

🚀 Features

- Clean, modular RESTful API  
- Mock datasets for patients, facilities, and appointments  
- JWT‑based authentication  
- Pagination, filtering, and validation  
- Scalable folder structure  
- Fully documented endpoints  
- Easy to extend for real‑world digital health systems  
- Ideal for prototyping, demos, and educational use  

---

📁 Project Structure

`
afar-digital-health-api/
│
├── src/
│   ├── controllers/
│   ├── routes/
│   ├── data/
│   │   ├── patients.json
│   │   ├── facilities.json
│   │   └── appointments.json
│   ├── middleware/
│   ├── services/
│   └── utils/
│
├── docs/
│   ├── api-reference.md
│   ├── architecture.md
│   └── roadmap.md
│
├── tests/
│
├── .env.example
├── package.json
├── README.md
└── LICENSE
`

---

🧪 API Endpoints Overview

🔐 Authentication
| Method | Endpoint        | Description            |
|--------|------------------|------------------------|
| POST   | /auth/login    | Login and get JWT     |

👤 Patients
| Method | Endpoint            | Description               |
|--------|----------------------|---------------------------|
| GET    | /patients          | List all patients         |
| GET    | /patients/:id      | Get patient by ID         |

🏥 Facilities
| Method | Endpoint            | Description               |
|--------|----------------------|---------------------------|
| GET    | /facilities        | List all facilities       |

📅 Appointments
| Method | Endpoint              | Description               |
|--------|------------------------|---------------------------|
| GET    | /appointments        | List all appointments     |
| POST   | /appointments        | Create a new appointment  |

Full documentation is available in docs/api-reference.md.

---

🎯 Purpose

This project aims to support:

- Developers building health‑tech prototypes  
- Students learning backend engineering  
- NGOs and government teams testing digital workflows  
- Anyone needing a safe, realistic health API  
- Hackathons, demos, and training programs  

It is intentionally simple, extensible, and safe for public use.

---

🛠️ Tech Stack

- Node.js (Express) or Laravel (your choice)  
- JSON mock datasets  
- JWT authentication  
- Modular architecture  

---

📦 Installation

`
git clone https://github.com/yourusername/afar-digital-health-api
cd afar-digital-health-api
npm install
cp .env.example .env
npm start
`

---

🧭 Roadmap

- Add role‑based access control  
- Add more health modules (labs, referrals, vitals)  
- Add FHIR‑compatible endpoints  
- Add Docker support  
- Add Postman collection  
- Add frontend demo  

---

🤝 Contributing

Contributions are welcome.  
Please open an issue or submit a pull request.

---

📄 License

This project is licensed under the MIT License — free for personal and commercial use.
