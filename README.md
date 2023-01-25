# Workshop 14

## How to start redis

1. Start a redis server (1st tab)
```
redis-server
```

2. To connect to redis server (2nd tab)
```
redis-cli
```

3. Use maven to run app
```
mvn spring-boot:run
```

## How to deploy Railway

1. login to railway
```
railway login
railway login --browserless
```

2. initialize new project on railway
```
railway init
```

3. push project to railway
```
railway up
```

4. Once deployed
```
-> Settings -> Generate Domain -> Click on Domain
```

## How to use Railway redis database

1. After initializing Railway project with "railway init"
```
1. Add redis database
2. railway up 
3. Set application.properties e.g. spring-redis.host=${REDISHOST} ...
```

## REDISDOTCOM: How to check database on Terminal 

1. To connect
```
redis-cli -u redis://default:<your password>@<your redis hostname>:<redis port>
```

2. Once connected
```
ping -> server returns pong
```

## Branch

1. To branch out (change branch)
```
git checkout -b darryl
To work on a version while not touching the present version
```

2. To return to main
```
git checkout main
```

3. Check current branch
```
git branch
```