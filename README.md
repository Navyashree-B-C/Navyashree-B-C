```
███╗   ██╗ █████╗ ██╗   ██╗██╗   ██╗ █████╗ ███████╗██╗  ██╗██████╗ ███████╗███████╗
████╗  ██║██╔══██╗██║   ██║╚██╗ ██╔╝██╔══██╗██╔════╝██║  ██║██╔══██╗██╔════╝██╔════╝
██╔██╗ ██║███████║██║   ██║ ╚████╔╝ ███████║███████╗███████║██████╔╝█████╗  █████╗  
██║╚██╗██║██╔══██║╚██╗ ██╔╝  ╚██╔╝  ██╔══██║╚════██║██╔══██║██╔══██╗██╔══╝  ██╔══╝  
██║ ╚████║██║  ██║ ╚████╔╝    ██║   ██║  ██║███████║██║  ██║██║  ██║███████╗███████╗
╚═╝  ╚═══╝╚═╝  ╚═╝  ╚═══╝     ╚═╝   ╚═╝  ╚═╝╚══════╝╚═╝  ╚═╝╚═╝  ╚═╝╚══════╝╚══════╝
```

```bash
navyashree@bengaluru:~$ whoami
```
```
role      : Full Stack Developer + AI Engineer
location  : Bengaluru, India
current   : Veyon Ideations — sole backend dev + production DevOps
prev      : Research Intern, IISc Bangalore
education : M.Tech — Artificial Intelligence
contact   : navyashreebc@gmail.com
```

---

```bash
navyashree@bengaluru:~$ cat /etc/production.conf
```
```nginx
# what i run in production
server {
    listen 443 ssl;
    server_name veyon.app;

    ssl_certificate      /etc/letsencrypt/live/veyon.app/fullchain.pem;
    ssl_certificate_key  /etc/letsencrypt/live/veyon.app/privkey.pem;

    location /api/ {
        proxy_pass http://127.0.0.1:8000;   # FastAPI
    }

    location / {
        proxy_pass http://127.0.0.1:3000;   # React frontend
    }
}
# + PostgreSQL · backups · monitoring · systemd services
```

---

```bash
navyashree@bengaluru:~$ ls -la ~/projects
```

| project | stack | status |
|---|---|---|
| [**SLOTH**](https://github.com/Navyashree-B-C/sloth) | React · FastAPI · Whisper STT · Coqui XTTS · Docker | `● live` |
| [**intelligent_inventory_system**](https://github.com/Navyashree-B-C/intelligent_inventory_system) | Python · SQLite · RBAC · Anomaly Detection | `● stable` |
| **AI Smart Mirror** | Python · OpenCV · Gemini LLM · Firebase · RPi | `⬤ proprietary` |
| **Academic Data Platform** | Flask · SQLAlchemy · Pandas · MySQL | `⬤ proprietary` |

---

```bash
navyashree@bengaluru:~$ cat tech_stack.txt
```
```
LANGUAGES    →  Python   JavaScript   SQL
BACKEND      →  FastAPI  Flask  REST APIs  SQLAlchemy
FRONTEND     →  React  Vite  HTML5  CSS3
AI / CV      →  OpenCV  Whisper STT  Gemini  LLM Integration
DATABASES    →  PostgreSQL  MySQL  SQLite  Firebase
DEVOPS       →  Docker  Nginx  SSL  systemd  GitHub Actions
INFRA        →  Linux VPS (Hostinger)  Raspberry Pi  SSH
```

---

```bash
navyashree@bengaluru:~$ uptime
 09:41:23 up 847 days,  3:12,  1 user,  load average: 0.12, 0.08, 0.05
# production has been running. don't touch what works.
```

---

```bash
navyashree@bengaluru:~$ ping navyashreebc@gmail.com
PING navyashreebc@gmail.com — response time: fast
^C
--- navyashreebc@gmail.com ping statistics ---
packets transmitted: 1, received: 1, packet loss: 0%
```
