# DelMonte_Servers

## Development
```
- IP Address: 10.54.160.217
- Ubuntu: 24.04.4 LTS
```
## Installed Systems
```
- Docker Engine: 29.4.1
```
## Instalations
### Del Monte Atlas light version
```
dmfp-atlas  Port 8080:80
``` 
### Del Monte Atlas Full Version
```
NAME            IMAGE                COMMAND                  SERVICE   CREATED          STATUS                    PORTS
atlas-app-1     atlas-app:latest     "docker-entrypoint.s…"   app       31 minutes ago   Up 31 minutes             8080/tcp
atlas-db-1      postgres:16-alpine   "docker-entrypoint.s…"   db        31 minutes ago   Up 31 minutes (healthy)   127.0.0.1:5433->5432/tcp
atlas-nginx-1   nginx:alpine         "/docker-entrypoint.…"   nginx     31 minutes ago   Up 31 minutes             80/tcp, 0.0.0.0:2431->443/tcp, [::]:2431->443/tcp
```

## QA
```
- IP Address: 10.54.160.218
- Name: ustmrvmaiuat
```

## Installed Systems
```
- Docker Engine: 29.4.2
```
