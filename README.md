# docker_sqldesigner

### usage

'''
git clone 

```
cd web2py 
```
```
docker build -t designer .
```
```
docker run --name=designer --restart always -v yourpath:/opt/web2py/applications/designer/databases -d -p 443:443 designer
```
