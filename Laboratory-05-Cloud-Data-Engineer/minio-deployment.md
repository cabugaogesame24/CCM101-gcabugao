# MinIO Deployment

## Docker Command Used

I deployed the MinIO server through Docker in the KillerCoda Playground. The command below was used to start the container and make the required ports available:

```bash
docker run -d -p 9000:9000 -p 9001:9001 \
--name minio-server \
-e "MINIO_ROOT_USER=cloudadmin" \
-e "MINIO_ROOT_PASSWORD=CloudNova2026!" \
minio/minio server /data --console-address ":9001"
```

## Web Console Access
```bash
The MinIO Web Console can be opened through port 9001. In KillerCoda, I used the Traffic/Ports option and entered port 9001 to access the MinIO interface. I then logged in using the credentials configured in the Docker command.
```

## Bucket Name
```bash
The bucket I created for the activity was named client-photos. It was used as the storage location for the sample file that I uploaded through the MinIO Web Console.
```

## Purpose of the -e Flags
```bash
The -e flags were used to provide the MinIO container with its administrator login credentials during startup.

MINIO_ROOT_USER=cloudadmin sets the administrator username.
MINIO_ROOT_PASSWORD=CloudNova2026! sets the administrator password.
```
These environment variables tell MinIO which credentials to use when accessing the Web Console.

