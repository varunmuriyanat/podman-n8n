# Run n8n in podman locally

## Pull the n8n image
podman pull docker.io/n8nio/n8n

## run locally on port 5678
podman run -d --name n8n -p 5678:5678 n8nio/n8n

## Watch the continuous stream of logs from the n8n container
podman logs -f n8n

## stop after use
podman ps
podman stop n8n

