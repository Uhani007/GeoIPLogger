
# 🌍 GeoIPLogger

**GeoIPLogger** is a simple PHP + HTML project that records visitor details when they open a webpage and allow location access.  
The system automatically logs:

- 📍 Latitude & Longitude (Coordinates)  
- 🌐 Public IP Address  
- 💻 Operating System & Browser Info (via User-Agent)  
- 🕒 Date & Time of visit  

All information is stored in a file called `log.txt`.

---

## 🚀 Features
- Works **without any API key**  
- Collects **IP + Coordinates + OS/Browser info**  
- Can be tested locally (**localhost**)  
- Can be hosted on any **free/paid web hosting service** (InfinityFree, AwardSpace, 000webhost, etc.)  
- Auto-creates and updates `log.txt` with every new visitor  

---

## 📂 Project Files
public_html/
│── locate.html # Webpage (with geolocation + optional GIF)
│── store.php # PHP script to log data
│── log.txt # Visitor log file

---

## 🌐 Hosting & Sharing
- Works with **any free hosting site** (InfinityFree, AwardSpace, 000webhost, etc.).  
- Just upload the files into your hosting account’s `public_html` folder.  
- Your page will be available on a public link like:
- https://yourdomain.example/locate.html

---

## 🗒️ NOTE

### ✅ Local Testing

You can also test this project locally before uploading:

1. Open a terminal in the `public_html` folder.
2. Start a PHP server:
   cd public_html   # folder containing locate.html, store.php
   php -S 127.0.0.1:8000
   ```
3. Open in browser:
   http://127.0.0.1:8000/locate.html
   ```

### ✅ Additional Info

* No API key required.
* Works on both **PC and Mobile browsers**.
* Logs are stored in plain text (`log.txt`).

---



## ⚠️ Disclaimer
This project is for **educational and demo purposes only**.  
Do not use it for unauthorized tracking. Always obtain proper consent.



