# dsti-lab-12-secure-data-in-transit

Clone the project:

```bash
git clone https://github.com/EliottElek/dsti-lab-12-secure-data-in-transit.git
```

Copy .env files:


```bash
cd dsti-lab-12-secure-data-in-transit
cp .env.example ./traefik/.env && cp .env.example ./supabase/.env
```

Launch containers:

```bash
docker compose -f ./traefik/docker-compose.yml -f ./supabase/docker-compose.yml up -d
```
