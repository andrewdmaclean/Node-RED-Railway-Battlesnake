Node-RED Battlesnake
================

A wrapper for deploying a [Node-RED](http://nodered.org) based [Battlesnake](https://play.battlesnake.com) into [Railway](https://railway.app.).

[![Deploy on Railway](https://railway.app/button.svg)](https://railway.app/new/template/IaInHw?referralCode=h8bD3s)

## ✨ Features
- Node-RED accessible on HTTPS
- Password Authentication (Set username & password in environment variables)
- Persistent PostgreSQL

##  How to Deploy
1. Click Deploy on Railway
2. Wait for Build & Deployment to Finish
3. Refresh the Web Server x2 (See notes below)
4. Login with credentials (**Username:** Battle & **Password:** Snake)

## 📝 Notes
- If you wish to change any of the default settings it can be done at deploy OR later in the server variables
- Railway server currently requires 2x refreshes to successfully seed the database due to a 🐛 (PRs for fixes welcome 🙏)

