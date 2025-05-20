# 🔗 DecentraChain – Full Stack Blockchain App

A full-stack blockchain project built from the ground up, demonstrating how cryptocurrency systems function—from block creation and transaction validation to mining and peer synchronization.


---

## 📚 Table of Contents

- [Overview](#overview)
- [Project Highlights](#project-highlights)
- [Future Enhancements](#future-enhancements)
- [Tech Stack](#tech-stack)
- [Contributing](#contributing)
- [Credits](#credits)

---

## 📖 Overview

This project was developed to explore the fundamentals of blockchain by building an actual working model using only JavaScript and open-source web technologies. Rather than relying on pre-existing frameworks like Ethereum or Bitcoin libraries, every key element was coded manually to deeply understand how blockchains work behind the scenes.

The app features:

- A custom-built blockchain backend
- A transaction system with wallet signing
- Mining through proof-of-work
- Real-time peer syncing via publish/subscribe
- A modern web frontend using React
- Deployment on Heroku for public access

  ## Front End Interface
<img width="661" alt="Screenshot 2025-05-20 at 2 01 02 PM" src="https://github.com/user-attachments/assets/4c46de8e-9a0e-4994-a756-d6f0556b08cc" />


> Screenshot of the app UI:
> <img width="602" alt="Screenshot 2025-05-20 at 2 02 05 PM" src="https://github.com/user-attachments/assets/cb290ae0-3d4b-459e-b2bd-2ca2ef90c8b1" />
<img width="598" alt="Screenshot 2025-05-20 at 2 02 26 PM" src="https://github.com/user-attachments/assets/14305749-728c-4198-9362-8f25a117517c" />
<img width="579" alt="Screenshot 2025-05-20 at 2 02 50 PM" src="https://github.com/user-attachments/assets/ff983839-caf2-463e-a21f-6d549caf8537" />
<img width="598" alt="Screenshot 2025-05-20 at 2 03 10 PM" src="https://github.com/user-attachments/assets/251e1e10-6c38-47b6-8f0c-51daf1e01aab" />





## 🌟 Project Highlights

- 💻 Custom-built backend for block and transaction logic
- 🔐 Transactions are signed using digital cryptography
- 🧠 Test-driven approach with unit and integration tests using Jest
- 🔗 Real-time peer-to-peer communication using Redis Pub/Sub
- ⚙️ Mining engine with adjustable proof-of-work difficulty
- 🌍 Interactive React frontend with routing and dynamic data
- 🧪 REST APIs for wallet info, mining, chain exploration, and transaction submission

---

## 🚀 Future Enhancements

Here are some ideas to make the app more scalable and production-ready:

- 💾 Save blockchain data to the local file system or persistent database
- 📥 Reload the chain from JSON to resume previous states
- 🔁 Switch from polling to WebSocket for live transaction updates
- 📦 State management using Redux for better frontend performance
- 🔑 Generate fresh key pairs per transaction for better privacy
- 🔍 Show mining progress in real-time on the frontend
- 🛂 Secure the frontend with authentication & role-based access
- 🧩 Implement permissioned chains with limited user access
- 🧠 Use AI models for anomaly detection in transactions
- 🌱 Explore Proof-of-Stake implementation for eco-friendliness

---

## 🧰 Tech Stack

| Layer      | Technology           |
|------------|----------------------|
| Frontend   | React.js, React Router |
| Backend    | Node.js, Express.js  |
| Sync Layer | Redis (Pub/Sub)      |
| Testing    | Jest                 |
| Cryptography | elliptic, SHA-256  |
| Deployment | Heroku               |

---

## 🤝 Contributing

We welcome contributions from the community!  
Here’s how to contribute:

1. Fork this repository
2. Create a new branch  
   `git checkout -b feature/YourFeatureName`
3. Commit your changes  
   `git commit -m "Add Your Message"`
4. Push to your branch  
   `git push origin feature/YourFeatureName`
5. Create a Pull Request 🚀

---

## 🙏 Credits

Special thanks to the open-source community whose content and repos inspired parts of this build:

- [David Katz – CryptoChain](https://github.com/15Dkatz/cryptochain)
- [Awesome Blockchain Resources (GitHub)](https://github.com/yjjnls/awesome-blockchain#implementation-of-blockchain)
- [YouTube: Blockchain from Scratch Series](https://www.youtube.com/watch?v=zVqczFZr124)

---

> ⚠️ This project is for learning and demonstration purposes only. It is not intended to be used in production or for real financial transactions.

