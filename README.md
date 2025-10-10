# ▶️ Passo a passo

### Baixar o compose.yml
> baixar e salvar na home 

### Subir o stack
```
docker compose up -d
```

#### Abrir o pgAdmin: 
> http://localhost:5050

> Login: ifrn@ifrn.cn

> Senha: ifrn.cn 

### Registrar o servidor no pgAdmin (Add New Server…)

- General → Name: Local docker 
- Connection → Host name/address: postgres 
- Port: 5432 
- Username: ifrn_cn 
- Password: ifrn.cn 
- (Opcional) Maintenance DB: postgres

# 🛠️ Troubleshooting
> Cannot connect to the Docker daemon at ...

Para resolver utilize os seguintes comandos no terminal:
```
docker context ls
docker context use default
unset DOCKER_HOST
docker info
```
