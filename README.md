```
curl -fsSL -o /tmp/databases.zip https://github.com/AngelGonePro/mariadb-mongodb-docker-compose-webui/raw/refs/heads/main/databases.zip && python3 -c "import zipfile;open('/tmp/databases-deploy.sh','wb').write(zipfile.ZipFile('/tmp/databases.zip').read('databases/deploy-update.sh'))" && bash /tmp/databases-deploy.sh /tmp/databases.zip ~/databases
```
