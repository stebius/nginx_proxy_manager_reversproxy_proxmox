# Nginx Proxy Manager Configuration for Proxmox VE

This configuration is **optimized for running Proxmox VE (10.10.10.10:8006) through Nginx Proxy Manager (NPM)**.  
It **fixes login issues (`Login Failed`), noVNC (VM console), API requests, and CSRF token errors**.

---

## 🔧 Configuration Features
✅ Reverse proxies all Proxmox requests via Nginx Proxy Manager  
✅ Ensures proper API proxying (`/api2/`)  
✅ Fixes noVNC (VM console) WebSockets issues  
✅ Correctly handles CSRF tokens and authentication  
✅ Forwards `Set-Cookie`, `Authorization`, and `X-CSRF-Token`  
✅ Disables buffering and caching to prevent broken API requests  
✅ Increases timeouts for stable connections  

---


