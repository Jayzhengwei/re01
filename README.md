[![CircleCI](https://circleci.com/bb/moveupwest/moveup-api.svg?style=svg)](https://circleci.com/bb/moveupwest/moveup-api)

# MoveUp #

MoveUp API & admin project.

### Summary ###
* MoveUp API
* MoveUp Admin

### What we use ###
* ## **java8.0**
* spring 4.3
* mysql8

### How to install ###
* Import as maven project
* Run 2 dumpSQL in moveup-db  to build DB
  * Dump20210119.sql
  * Dump20230130_batch.sql
* Run app with tomcat

### Tomcat Configutaion ###
Edit Tomcat configuration and Write VM Option

`-Dfile.encoding=UTF-8 -Duser.language=en -Duser.region=US`

### Trouble Shooting ###
* XXXXXX
* XXXXXX
* XXXXXX

### How to user MyBatis generator ###
Fix generatorConfig.xml to make sure your mysql connector is exist.

Add maven run like this.  
Working directory: /Users/xieyoujun/project/moveup-api  
Command line: mybatis-generator:generate -e  
Also you can see this: http://zhige.me/2017/04/13/2017/201704/mybatis-generator/

### Source comment ###
```
/**   
 * ${NAME}  
 * Created by ${USER}.  
 *  
 * DateTime: ${DATE} ${TIME}  
 * Copyright: sLab, Corp  
 */  
 ```
