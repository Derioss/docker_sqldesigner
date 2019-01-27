# docker_sqldesigner

### usage

put you certificate in 

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
docker run --name=designer --restart always -v yourpath:/opt/web2py/applications/designer/databases -d -p 443:443 designer
```
 
https://yoururl/designer/

### 
