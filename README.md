# docker_sqldesigner

### description

Based on centos.

SQLdesigner provide by python's framework web2py.


you can try it on sqldesigner's developer webiste : http://ondras.zarovi.cz/sql/demo/?keyword=default 




### usage

put yours certificate in ./certificates with the same name (or modify dockerfile)

edit web2py/dockerfile and modify on line 28 "youradminpassword"

```
git clone https://github.com/Derioss/docker_sqldesigner.git

```

```
cd web2py 
```
```
docker build -t designer .
```
```
# /opt/web2py/applications/designer/databases is the path of sqllite
docker run --name=designer --restart always -v yourpath:/opt/web2py/applications/designer/databases -d -p 443:443 designer
```
```
docker start designer
```

 
https://yoururl/designer/

### software source

sqldesigner : https://github.com/ondras/wwwsqldesigner
web2py : http://www.web2py.com/

