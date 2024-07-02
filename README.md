# Odoo 16 Docker Container

This is a repository to getting started with Odoo 16.

## Getting Started

Make sure you have the following prerequisite installed:

- Docker

Clone the repository:

```bash
git clone https://github.com/yahya6789/odoo16-container.git
```

Rename or copy `odoo.conf.example` file to `odoo.conf`.

Start the container by running the following command:

```bash
docker compose up -d
```

The command will pull the `odoo:16.0` and `postgres:14` image.

Open the url at `http://localhost:8069`.
