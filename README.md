# HealthID

Imagine having your personal medical history at your fingertips, available from anywhere in the world, at any time. Welcome to HealthID, the solution that is changing the way we store and share medical information.

# What is HealthID?

Is an innovative blockchain-based healthcare application that allows you to securely store your exam history, doctor's appointments and other medical data. Using blockchain technology, we ensure that your data is stored securely, transparently and accessible from anywhere in the world.

# Key Features:

1. Blockchain storage: we use it to store your medical data securely and immutably. This means that your records are protected against unauthorized changes and will remain intact over time.

2. Global Access: No matter where you are, HealthID allows you to access your medical history at any time. Traveling abroad? At a doctor's appointment? Your data is always at your fingertips.

3. Controlled Sharing: Share your medical information with ease. You decide who can access your medical records and can revoke access at any time.

4. Traceability and Transparency: The blockchain offers complete traceability of all changes to your medical records. You can see who has accessed your data and when.

5. Protected Privacy: Your sensitive personal information is protected. Only you have control over who sees this information. We are committed to maintaining our standards in compliance with data privacy regulations.

6. Ease of Use: Our app is designed to be intuitive and easy to use, so you can manage your medical data without complications.

Join us on this journey to a more accessible, secure and empowered future for your health. Take control of your medical history like never before.


## Installation

```bash
$ cd HealthIDBack/healthid-nest
$ yarn install
```

## Running the app

```bash
# development
$ yarn run start

# watch mode
$ yarn run start:dev

# production mode
$ yarn run start:prod
```

# Routes

| Method | Endpoint | Parameters |
|--------|----------|------------|
| POST | /StoreExams | Receive Wallet ID, pdf exams and metadata |
| GET  | /GetExams/ID | Receive Wallet ID and returns all exams from user |
| POST | /CreateHealthService | Create the Health Service and returns its ID |
| GET | /GetExamsEntity/ID | Generate QR Code with Service ID |
