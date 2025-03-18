# Dark_OSINT

(위협 인텔리전스) 다크웹 유출 정보 알림 및 OSINT 수집 시스템 개발

### Usage

---

```
$docker-compose up --build -d
```

kibana : http://localhost:5601

The script in docker would run at 09:00 & 21:00 (TZ : America/New_York)

If you want to run the script follow below

```
$docker-compose up --build -d
$docker exec -it tor /bin/bash
$python3 main.py
```
