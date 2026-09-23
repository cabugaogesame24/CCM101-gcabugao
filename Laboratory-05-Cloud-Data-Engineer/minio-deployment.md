# MinIO Deployment

## Docker Command Used

I used Docker to start the MinIO server in the KillerCoda Playground. The command I used was:

```bash
docker run -d -p 9000:9000 -p 9001:9001 \
--name minio-server \
-e "MINIO_ROOT_USER=cloudadmin" \
-e "MINIO_ROOT_PASSWORD=CloudNova2026!" \
minio/minio server /data --console-address ":9001"
```

## Web Console Access

The MinIO Web Console was accessed using port 9001. I used the Traffic/Ports option in KillerCoda to open the web interface.

## Bucket Name

I created a storage bucket called client-photos. The bucket was used to store the sample file uploaded during the activity.

## Purpose of the -e Flags

The -e options were used to set environment variables when starting the MinIO container.

MINIO_ROOT_USER=cloudadmin provides the username for the MinIO root account.
MINIO_ROOT_PASSWORD=CloudNova2026! provides the password for the MinIO root account.

These values allow the MinIO server to use the specified credentials when logging in to the Web Console.
