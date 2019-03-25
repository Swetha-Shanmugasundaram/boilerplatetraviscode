all services running on docker using docker compose

logger present in Playerservice
---- used in --> /playerService/src/main/java/com/stackroute/playerservice/controller

zuul routing routes on :
---- :7788 for player service
---- :7789 for user service

Zuul gateway running on " https " !! run on a browser, doesn't run on postman !

Eureka configured for userservice and Player service ONLY

Config server properties present on github : https://github.com/Farhaan900/config-server-repo



Ports used for all the services :-

>> userService   :7788
>> playerService :7789
>> configServer  :8891
>> zuulGateway   :8000
>> eureka Server :9090
>> mongo server  :27017


[![Build Status](https://travis-ci.org/Swetha-Shanmugasundaram/boilerplatetraviscode.svg?branch=master)](https://travis-ci.org/Swetha-Shanmugasundaram/boilerplatetraviscode)
[![codecov](https://codecov.io/gh/Swetha-Shanmugasundaram/boilerplatetraviscode/branch/<branch_name>/graph/badge.svg)](https://codecov.io/gh/Swetha-Shanmugasundaram/boilerplatetraviscode)
![](https://img.shields.io/codecov/c/github/Swetha-Shanmugasundaram/boilerplatetraviscode.svg?style=flat)

![](https://img.shields.io/snyk/vulnerabilities/github/Swetha-Shanmugasundaram/boilerplatetraviscode.svg?style=popout)
![](https://img.shields.io/github/issues/Swetha-Shanmugasundaram/boilerplatetraviscode.svg?style=popout)

![](https://img.shields.io/github/contributors/Swetha-Shanmugasundaram/boilerplatetraviscode.svg?style=popout)
![](https://img.shields.io/github/last-commit/Swetha-Shanmugasundaram/boilerplatetraviscode.svg?style=popout)

![](https://img.shields.io/github/repo-size/Swetha-Shanmugasundaram/boilerplatetraviscode.svg?style=popout)
[![License](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](https://opensource.org/licenses/Apache-2.0)
