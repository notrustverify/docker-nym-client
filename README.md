# docker-nym-client

## Set the permissions 

`chown -R 10000:10000 nym-client/nym-data/`

## Environment variables

| Name                | Default     | Description                     |
|---------------------|-------------|---------------------------------|
| `NAME_CLIENT`       | `docker`    | Name to identify the nym-client |
| `LISTENING_ADDRESS` | `127.0.0.1` | Specify the listening interface |
