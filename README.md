# Resume

Static HTML resume site.

## Usage

Start the server on default port 8080:

```bash
docker compose up -d
```

Start the server on custom port:

```bash
PORT=3000 docker compose up -d
```

(or set PORT=3000 in .env)

Stop the server:

```bash
docker compose down
```

Access at `http://localhost:8080` (or your custom port).
