# Lab 02 – Volumes and Networks

```bash
docker volume create data
docker run -v data:/data busybox ls /data
