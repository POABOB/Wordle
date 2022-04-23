# Wordle

## Installation

1. 建立.env

```
NODE_ENV = 'development'

PORT = 3000
BASE_SERVER_URL = 'localhost'
JWT_SECRET = 'SECRET'
# Facebook app credentials
FACEBOOK_APP_ID = 'XXXXXXXXXX'
FACEBOOK_APP_SECRET = 'XXXXXXXXXX'

# Google app credentials
GOOGLE_CLIENT_ID='XXXXXXX'
GOOGLE_CLIENT_SECRET='XXXXXXXXXXX'


# MYSQL
MYSQL_CONF_HOST = 'mysql'
MYSQL_CONF_USER = 'root'
MYSQL_CONF_PASSWORD = ''
MYSQL_CONF_PORT = 3306
MYSQL_CONF_DATABASE = 'wordle'
MYSQL_CONF_waitForConnections = 'true'
MYSQL_CONF_connectionLimit = 10
MYSQL_CONF_acquireTimeout = 10000
```

2. 開啟DOCKER(MYSQL 服務)

```
docker-compose up -d
```

3. 開啟nodejs

```
// 建立LIB
npm i

// 開啟服務
npm run dev
```


## Document

* 請開啟 http://localhost:3000/doc

* 後端資料夾/api

* 前端資料夾/static