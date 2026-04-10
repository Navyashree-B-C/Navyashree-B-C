```
███╗   ██╗ █████╗ ██╗   ██╗██╗   ██╗ █████╗ ███████╗██╗  ██╗██████╗ ███████╗███████╗
████╗  ██║██╔══██╗██║   ██║╚██╗ ██╔╝██╔══██╗██╔════╝██║  ██║██╔══██╗██╔════╝██╔════╝
██╔██╗ ██║███████║██║   ██║ ╚████╔╝ ███████║███████╗███████║██████╔╝█████╗  █████╗  
██║╚██╗██║██╔══██║╚██╗ ██╔╝  ╚██╔╝  ██╔══██║╚════██║██╔══██║██╔══██╗██╔══╝  ██╔══╝  
██║ ╚████║██║  ██║ ╚████╔╝    ██║   ██║  ██║███████║██║  ██║██║  ██║███████╗███████╗
╚═╝  ╚═══╝╚═╝  ╚═╝  ╚═══╝     ╚═╝   ╚═╝  ╚═╝╚══════╝╚═╝  ╚═╝╚═╝  ╚═╝╚══════╝╚══════╝
```

```bash
navyashree@dev:~$ whoami
```
```
i build backends, ship AI into products, and manage the infra that keeps it running.
vibe coder. cursor addict. if it's broken i'll fix it, if it doesn't exist i'll build it.
```

---

```bash
navyashree@dev:~$ cat /etc/production.conf
```
```nginx
server {
    listen 443 ssl;

    ssl_certificate      /etc/letsencrypt/live/domain/fullchain.pem;
    ssl_certificate_key  /etc/letsencrypt/live/domain/privkey.pem;

    location /api/ {
        proxy_pass http://127.0.0.1:8000;   # FastAPI
    }

    location / {
        proxy_pass http://127.0.0.1:3000;   # frontend
    }
}
# + PostgreSQL · Nginx · SSL · deployments · VPS management
```

---

```bash
navyashree@dev:~$ ls -la ~/projects
```

| project | stack | status |
|---|---|---|
| [**SLOTH**](https://github.com/Navyashree-B-C/sloth) | React · FastAPI · Whisper STT · Coqui XTTS · Docker | `● live` |
| [**intelligent_inventory_system**](https://github.com/Navyashree-B-C/intelligent_inventory_system) | Python · SQLite · RBAC · Anomaly Detection | `● stable` |
| **AI Smart Mirror** | Python · OpenCV · Gemini LLM · Firebase · RPi | `⬤ proprietary` |
| **Academic Data Platform** | Flask · SQLAlchemy · Pandas · MySQL | `⬤ proprietary` |

---

```bash
navyashree@dev:~$ cat tech_stack.txt
```
```
LANGUAGES    →  Python   JavaScript   SQL
BACKEND      →  FastAPI  Flask  REST APIs  SQLAlchemy
FRONTEND     →  React  Vite  HTML5  CSS3
AI / CV      →  OpenCV  Whisper STT  Gemini  LLM Integration
DATABASES    →  PostgreSQL  MySQL  SQLite  Firebase
DEVOPS       →  Docker  Nginx  SSL  GitHub Actions
INFRA        →  Linux VPS  Raspberry Pi  SSH
```

---

```bash
navyashree@dev:~$ ping navyashreebc@gmail.com
PING navyashreebc@gmail.com — response time: fast
^C
--- navyashreebc@gmail.com ping statistics ---
packets transmitted: 1, received: 1, packet loss: 0%
```
