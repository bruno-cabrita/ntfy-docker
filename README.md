# NTFY for Docker

## With Coolify

1. Start a project with **Docker Compose** and paste the contents of `docker-compose.yml`

2. Fill the **Environment Variables**

3. Goto **Service Stack > Service > Settings** set the **Domains** with: `<url in NTFY_BASE_URL>:8010`

4. Click the **Deploy** button

5. To add an admin, enter container terminal and run the command: `ntfy user add --role=admin <john>`

5. To add an anonymous account for webhooks, enter container terminal and run the command: `ntfy access everyone "webhooks" write` 

6. Browse to the url set in `NTFY_BASE_URL` environment variable.

## Documentation

- [NTFY](https://docs.ntfy.sh/config/)