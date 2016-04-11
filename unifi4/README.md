#docker UniFi

## Supported tags and respective `Dockerfile` links

[`unifi3`, `oldstable` (*unifi3/Dockerfile*)](https://github.com/top-cg/unifi/blob/master/unifi3/Dockerfile)

[`unifi4`, `stable`, `latest` (*unifi4/Dockerfile*)](https://github.com/top-cg/unifi/blob/master/unifi4/Dockerfile)

[`beta` (*unifibeta/Dockerfile*)](https://github.com/top-cg/unifi/blob/master/unifi4/Dockerfile)

## Description 
This is a containerized version of the Unifi Access Point controller.

## Volumes:

### `/var/lib/unifi`
Configuration data

### `/var/log/unifi`
Log Files

### `/var/run/unifi`
Run Information

## Environment Variables:
### `TZ`
TimeZone. (i.e America/Chicago)

## Expose:
### 8080/tcp
### 8081/tcp
### 8443/tcp
### 8843/tcp
### 8880/tcp
### 3478/udp
