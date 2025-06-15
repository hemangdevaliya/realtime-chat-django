# Django Realtime Chat App 🚀

A real-time chat application built using **Django**, **Django Channels**, **Redis**, and **WebSockets**, with **Uvicorn** serving as the ASGI server.

## 🔧 Features

- Room-based chat communication  
- Real-time messaging via WebSockets  
- Redis used as the Channel Layer backend  
- Scalable architecture using ASGI and Uvicorn

## 📦 Tech Stack

- Django  
- Django Channels  
- Redis  
- Channels Redis  
- WebSockets  
- Uvicorn (ASGI server)

---

## 🚀 Running the Uvicorn Server

First start the redis server go to redis folder where you installed redis and execute redis-server.exe file.

Then start the Uvicorn server, run the following command:

```bash
uvicorn chatproject.asgi:application --host 127.0.0.1 --port 8000
