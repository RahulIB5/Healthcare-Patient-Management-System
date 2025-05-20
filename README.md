# Healthcare-Patient-Management-System 

- **Type:** Web-based application

- **Purpose:**
  - Streamline patient care and hospital administration
  - Efficiently manage patient records, appointments, medical histories, and treatment plans

- **Tech Stack:**
  - **Frontend:** React (for a responsive UI)
  - **Backend:** FastAPI (high-performance and lightweight)
  - **ORM:** Prisma
  - **Database:** PostgreSQL (robust and reliable)

- **Key Features:**
  - Real-time appointment scheduling
  - Multi-channel patient notifications (via email and SMS)
  - Scalable and secure for small to medium-sized healthcare facilities

- **SDG Alignment:**
  - Supports **Sustainable Development Goal 3: Good Health and Well-being**
    - **Target 3.2:** Reducing preventable deaths
    - **Target 3.8:** Achieving universal health coverage

---


- Preliminary Steps
  - Make a neon.tech account , start a project and copy project url with and without pooling.
  - Make a Twilio account, and copy sid , auth token and sender phone number.
  - Obtain SendGrid api key and sender email.
  - Make  new file in Backend folder call .env and paste all of the above with names :
    - DATABASE_URL 
    - DIRECT_URL
    - TWILIO_ACCOUNT_SID
    - TWILIO_AUTH_TOKEN
    - TWILIO_PHONE_NUMBER
    - SENDGRID_API_KEY
    - SENDGRID_SENDER_EMAIL


- FrontEnd

```sh
cd Frontend
```

1. Install dependancies and assets
```
npm install
```

2. Start server
```
npm run dev
```

---

- Backend

```sh
cd Backend
```

1. Create virtual environment
```
python -m venv venv
```

2. Activate virtual environment
```
venv\Scripts\activate
```

3. Install requirements
```
pip install -r requirements.txt
```

4. Generate Prisma assets
```
prisma generate
```

5. Start uvicorn server
```
uvicorn app.main:app --reload
```


