# KrishiSeva

KrishiSeva is an online platform designed to bring farmers and buyers together for assured contract farming agreements. By ensuring secure contracts, transparent communication, and timely payments, KrishiSeva aims to provide farmers with a stable income and reduce the uncertainties of market access.

---

## Why KrishiSeva?

Farmers often face unpredictable market conditions, leading to fluctuating incomes. KrishiSeva was created to:

- **Ensure Stability:** Provide farmers with reliable buyers through contract farming.
- **Enhance Transparency:** Facilitate open communication between farmers and buyers.
- **Simplify Processes:** Offer tools for managing contracts, price negotiations, and secure payments.

---

## Key Features

- **Contract Farming Agreements:** Streamlined tools to establish secure contracts between farmers and buyers.
- **Transparent Communication:** A platform that fosters open dialogue for mutual trust usng chat features.
- **Secure Payments:** Reliable payment processing to protect both parties with support from *MetaMask* and *Stripe*.
- **Marketplace Tools:** Features for price negotiation and contract management along with *speech-to-text* functionality.

---

## Contributors

- [**Supreeth C**](https://github.com/ShinichiShi)
- [**Vaibhav Garg**](https://github.com/vaibhavgarg25)
- [**Samyak SH**](https://github.com/Samyak-SH)
- [**Lavi**](https://github.com/Nexusrex18)
- [**Dilip SC**](https://github.com/DilipSC)
- [**Isha Rajmohan**](https://github.com/IshaRajmohan)
---

## Tech Stack

- **Frontend:** Vite Framework using React
- **Backend:** ExpressJS
- **Database:** Firebase
- **Blockchain:** MetaMask, Solidity, Truffle framework
- **Speech-to-text:** Gemini Api
---

## How to Run Locally

### Clone the repository:
```bash
git clone https://github.com/ShinichiShi/KrishiSeva.git
cd KrishiSeva
```
2. Create a env.local in client repository accordingly:
```bash
VITE_FIREBASE_API_KEY=xxx
VITE_FIREBASE_AUTH_DOMAIN=xxx
VITE_FIREBASE_PROJECT_ID=xxx
VITE_FIREBASE_STORAGE_BUCKET=xxx
VITE_FIREBASE_MESSAGING_SENDER_ID=xxx
VITE_FIREBASE_APP_ID=xxx
```
Contact any of the maintainers for the contents of the `.env.local` file

Then, run in the client folder terminal:
```bash
cd client
npm install
npm run dev
```
and along with that: 
```bash
cd server
npm install
npm run dev
```
Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

# Contributing

We welcome contributions to KrishiSeva! Here’s how you can help:

1. Fork the repository.
2. Raise any issue
3. Create a feature branch:
   ```bash
   git checkout -b feature-name
   ```
4. Commit your changes:
   ```bash
   git commit -m 'Add feature-name'
   ```
5. Push to the branch:
   ```bash
   git push origin feature-name
   ```
6. Open a pull request.

---

# License

This project is licensed under the [MIT License](LICENSE).
