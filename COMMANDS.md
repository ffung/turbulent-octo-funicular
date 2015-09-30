


### Staging
Run the staging environment
```
docker-compose -f staging.yml up -d
```

### Production
Run the production environment
```
docker-compose -f production.yml up -d
```
Scale the nodes in production
```
docker-compose -f production.yml scale web=3
```
