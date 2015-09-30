

## Using Compose
### Staging
Run the staging environment
```
docker-compose -f staging.yml up -d
```
Validate that the environment is running
```
dc -f staging.yml ps
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
Validate that the environment is running
```
dc -f staging.yml ps
```
