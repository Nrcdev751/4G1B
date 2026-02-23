# Cyber Security

## Owner

- 6702041511209
- Narongchai Suratdarom
- s6702041511209@email.kmutnb.ac.th

- 6702041511152
- Kunjanapron Kaewtubtim
- s6702041511152@email.kmutnb.ac.th

- 6702041511021
- Boonyisa Aiamsamarng
- s6702041511021@email.kmutnb.ac.th

- 6702041511217
- Thanyaphon Nimnual
- s6702041511217@email.kmutnb.ac.th

- 6702041511144
- Jenjira Sripusit
- s6702041511144@email.kmutnb.ac.th

## Environment

```sh
cp env.simple .env
```

## Running services

### Database

```sh
docker compose -f db.yaml up # monitoring
docker compose -f db.yaml up -d #background
```

### Admin

```sh
docker compose -f admin.yaml up # monitoring
docker compose -f admin.yaml up -d #background
```

### Application

```sh
docker compose -f app.yaml up # monitoring
docker compose -f app.yaml up -d #background
```
### Run All

```sh
docker compose -f db.yaml -f admin.yaml -f app.yaml up -d
```
