# Task-7-Netdata

## Quick Start

Run Netdata with Docker:
```bash
docker run -d --name=netdata -p 19999:19999 netdata/netdata
```

Access at: http://localhost:19999

## Screenshots
![Netdata Dashboard](images/Screenshot 2025-08-15 at 9.13.29 PM.png)
![Netdata Monitoring](images/Screenshot 2025-08-15 at 9.14.23 PM.png)

## Features
- CPU monitoring
- Memory monitoring  
- Disk monitoring
- Docker container monitoring
- Alerts and chart panels
- Logs in `/var/log/netdata`