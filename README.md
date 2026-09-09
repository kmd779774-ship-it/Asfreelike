🚀 Free Fire Like API

<p align="center">
  <img src="./logo.png" width="140" alt="Aryan Shanto Logo">
</p><h1 align="center">FREE FIRE LIKE API</h1><p align="center">
  ⚡ Ultra Fast Async Like API Using Flask + AES + Protobuf
</p><p align="center">
  <a href="https://t.me/Aryan_owner99">
    <img src="https://img.shields.io/badge/Telegram-Aryan_owner99-2CA5E0?style=for-the-badge&logo=telegram&logoColor=white">
  </a>
</p>---

✨ Features

- ⚡ Ultra Fast Async Request System
- 🔐 AES CBC Encryption
- 📦 Protobuf Serialization
- 🌍 Multi Region Support
- 🧠 Smart Token Loader
- 🚀 Flask REST API
- 📊 Like Count Response
- 🛡 Full Error Handling
- ⚙️ VPS Optimized

---

🌍 Supported Regions

Region| Code
Bangladesh| BD
India| IND
Brazil| BR
United States| US
North America| NA
SAC| SAC

---

📂 Project Structure

project/
│
├── app.py
│
├── like_pb2.py
├── like_count_pb2.py
├── uid_generator_pb2.py
│
├── token_bd.json
├── token_br.json
├── token_ind.json
│
├── requirements.txt
├── LICENSE
├── logo.png
└── README.md

---

📦 Requirements

Install Packages

pip install -r requirements.txt

requirements.txt

flask
aiohttp
requests
pycryptodome
protobuf

---

📁 Token Files

«⚠️ Never upload real JWT tokens, passwords, or private credentials to GitHub.»

token_bd.json

[
  {
    "token": "YOUR_JWT_TOKEN"
  },
  {
    "token": "YOUR_JWT_TOKEN_2"
  }
]

token_br.json

[
  {
    "token": "YOUR_JWT_TOKEN"
  }
]

token_ind.json

[
  {
    "token": "YOUR_JWT_TOKEN"
  }
]

---

▶️ Run Server

python app.py

Local server:

http://127.0.0.1:5000

---

⚙️ Production Deployment

Gunicorn

gunicorn -w 4 -k gthread -b 0.0.0.0:5000 app:app

PM2

pm2 start app.py --interpreter python3 --name ff-like-api

Supervisor

sudo nano /etc/supervisor/conf.d/fflike.conf

Configuration

[program:fflike]
directory=/root/project
command=python3 app.py
autostart=true
autorestart=true
stderr_logfile=/var/log/fflike.err.log
stdout_logfile=/var/log/fflike.out.log

Restart Supervisor

sudo supervisorctl reread
sudo supervisorctl update
sudo supervisorctl restart fflike

---

📌 API Endpoint

GET /like?uid={uid}&server_name={region}

---

✅ Example Request

https://your-domain.com/like?uid=123456789&server_name=BD

---

✅ Example Response

{
  "LikesGivenByAPI": 154,
  "LikesafterCommand": 2034,
  "LikesbeforeCommand": 1880,
  "PlayerNickname": "Player",
  "UID": 123456789,
  "status": 1
}

---

📊 Response Explanation

Key| Description
LikesGivenByAPI| Total Likes Added
LikesafterCommand| Likes After Request
LikesbeforeCommand| Likes Before Request
PlayerNickname| Player Name
UID| Player UID
status| 1 = Success
status| 2 = Failed

---

🔥 Performance

- ⚡ Async Request Processing
- 🔄 Token Rotation
- 📉 Low RAM Usage
- 🚀 Fast Response
- ⚙️ VPS Optimized

---

🛠 Built With

- 🐍 Python
- 🌐 Flask
- ⚡ AsyncIO
- 🔗 AioHTTP
- 📡 Requests
- 🔐 PyCryptodome
- 📦 Protobuf

---

🧠 Encryption & Protocol

This project uses:

- AES CBC Encryption
- Protobuf Encoded Requests
- Bearer Token Authentication

---

👨‍💻 Developer

Aryan Shanto

<p align="left">
  <a href="https://t.me/Aryan_owner99">
    <img src="https://img.shields.io/badge/Telegram-@Aryan_owner99-2CA5E0?style=for-the-badge&logo=telegram&logoColor=white">
  </a>
</p>---

📄 License

This project is licensed under the MIT License.

See the ""LICENSE"" (LICENSE) file for details.

---

⚠️ Disclaimer

This project is provided for educational and development purposes.

The developer is not responsible for misuse of this project.

Use it responsibly and only with services/accounts you are authorized to access.

---

⭐ Support

If you find this project useful:

⭐ Star the Repository
🍴 Fork the Repository
📢 Share the Project

---

❤️ Thanks For Using

<p align="center">
  MADE WITH ❤️ BY ARYAN SHANTO
</p><p align="center">
  Telegram: @Aryan_owner99
</p>---

<p align="center">
  © 2026 Aryan Shanto. All Rights Reserved.
</p>