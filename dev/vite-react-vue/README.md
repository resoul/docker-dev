docker compose
```bash
vite:
    image: airlance/vite-react-vue:dev
volumes:
    - ./your-vite-project:/app
ports:
    - "4008:4008"
environment:
    - PORT=4008
```
