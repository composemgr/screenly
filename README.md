## 👋 Welcome to screenly 🚀

Digital signage solution for displaying content on screens

## 📋 Description

Digital signage solution for displaying content on screens

## 🚀 Services

- **screenly**: screenly/screenly-ose:latest

## 📦 Installation

### Option 1: Quick Install
```bash
curl -q -LSsf "https://raw.githubusercontent.com/composemgr/screenly/main/docker-compose.yaml" -o compose.yml
```

### Option 2: Git Clone
```bash
git clone "https://github.com/composemgr/screenly" ~/.local/srv/docker/screenly
cd ~/.local/srv/docker/screenly
docker compose up -d
```

### Option 3: Using composemgr
```bash
composemgr install screenly
```

## 🔧 Configuration

### Environment Variables

```shell
TZ=America/New_York
```

See `docker-compose.yaml` for complete list of configurable options.

## 🌐 Access

- **Web Interface**: http://172.17.0.1:8093

## 📂 Volumes

- `./rootfs/config/screenly` - Data storage
- `./rootfs/data/screenly` - Data storage

## 🔍 Logging

```shell
docker compose logs -f screenly
```

## 🛠️ Management

```bash
# Start services
docker compose up -d

# Stop services
docker compose down

# Update to latest images
docker compose pull && docker compose up -d

# View logs
docker compose logs -f

# Restart services
docker compose restart
```

## 📋 Requirements

- Docker Engine 20.10+
- Docker Compose V2+

## 🤝 Author

🤖 casjay: [Github](https://github.com/casjay) 🤖  
🦄 composemgr: [Github](https://github.com/composemgr) 🦄
