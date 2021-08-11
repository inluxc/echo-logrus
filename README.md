# echo-logrus
Middleware for [echo](https://github.com/labstack/echo) to use [logrus](https://github.com/sirupsen/logrus) as Logger

_This version only work in echo v4_

**Install**

```
go get -u github.com/inluxc/echo-logrus
```

**Usage**
```
echologrus "github.com/inluxc/echo-logrus"
```

**Init Logrus in Echo** 
```
echologrus.Logger = logrus.New()
e.Logger = echologrus.GetEchoLogger()
e.Use(echologrus.Hook())
```

Based from: [plutov/echo-logrus](https://github.com/plutov/echo-logrus)
