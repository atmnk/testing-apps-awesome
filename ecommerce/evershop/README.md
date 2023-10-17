# Starting
`docker compose up -d`
# Creating Admin User
1. `docker exec -it evershop-app-1 sh`
2. `npm run user:create -- --email "Your email" --password "Your password" --name "Your name"`
# Login to admin panel
http://localhost:3000/admon/login
