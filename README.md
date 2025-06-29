
# 🧠🎙️ Speech Transcriber & Synthesizer App
[![codecov](https://codecov.io/gh/PhillMckinnon/Flutter_Python_Speech_App/graph/badge.svg?token=816Z6C5L2U)](https://codecov.io/gh/PhillMckinnon/Flutter_Python_Speech_App)
[![Docker](https://img.shields.io/badge/docker-compose-blue?logo=docker)](https://docs.docker.com/compose/)
[![Python](https://img.shields.io/badge/python-3.10+-blue.svg?logo=python)](https://www.python.org/)
[![Flutter](https://img.shields.io/badge/flutter-ui-blue?logo=flutter)](https://flutter.dev/)
[![License: MIT](https://img.shields.io/badge/license-MIT-green.svg)](https://opensource.org/licenses/MIT)
[![Build](https://img.shields.io/badge/build-passing-brightgreen.svg)]()

> A Dockerized web app for transcribing speech to text and synthesizing multilingual speech responses.

---

## 🚀 Features

- 🎧 **Speech-to-Text** using [Whisper](https://github.com/openai/whisper)
- 🔊 **Text-to-Speech** with [Coqui TTS](https://github.com/coqui-ai/TTS)
- 🌍 Supports **multiple languages**
- 💻 **Frontend UI** built with Flutter Web
- 🐳 Seamless deployment using `docker-compose`
- 🔁 Configurable ports, IPs, and runtime behavior

---

## 📦 Tech Stack

- **Backend**: Python, [Sanic](https://sanic.dev/), Whisper, Coqui TTS
- **Frontend**: Flutter (Web)
- **Containerization**: Docker, Docker Compose
- **Web Server**: Nginx (templated via `nginx.conf.template`)

---

## 🧪 Getting Started

### 🔧 Prerequisites

- Git
- Docker
- Docker Compose

### 🏗️ Clone, Build and Run

```bash
git clone https://github.com/PhillMckinnon/Flutter_Python_Speech_App
cd Flutter_Python_Speech_App
docker-compose build
docker-compose up
````

Once running:

* Backend API: [http://localhost:5000](http://localhost:5000)
* Frontend UI: [http://localhost:8080](http://localhost:8080)

---

## ⚙️ Configuration

You can customize the behavior and ports by editing:

* 📄 `.env` – backend environment variables (e.g., model settings)
* 📄 `docker-compose.yaml` – adjust exposed ports or volumes
* 📄 `nginx.conf.template` – update fallback rules or paths
* 📄 `entrypoint.sh` – modify frontend routing or fallback logic

---

## 📫 Contact

Have questions, ideas, or feedback?

* ✉️ Email: [phillipmckinnonwork@proton.me](mailto:phillipmckinnonwork@proton.me)
* 💻 GitHub: [@PhillMckinnon](https://github.com/PhillMckinnon)

---

## 📝 License

This project is licensed under the [MIT License](https://opensource.org/licenses/MIT).

```


