# simple python server

a simple blog server base on python 

#### getting start:

	./src/pymonitor.py wsgiapp.py

##### todos:

* 页面构建
* markdown解析
* interceptor bug

## reference :
 [awesome-python-webapp](https://github.com/michaelliao/awesome-python-webapp)


## 学籍管理系统

功能： 
1. 学生【登陆】
2. 学生基本信息 【改】
3. 管理员【登陆】
4. 管理员对于获奖信息增删改查
5. 管理员【增删改查】学生

## USER表:

|----------------|------------|
|      id(int)        |   primary key |
|      name       |   varchar(50)    |
|      sno			|  int(10)       |
|      password     |   varchar(50)  |
|      email        |   varchar(50)  |
|      admin        |   1/0 (boolean) |
|     created_at    |   varchar(50) |


## award表：

|----------------|------------|
|    id    |  primary key          |
|   award_name| varchar(50)   |
|   award_content|   text        |
|   award_user_id|    int     |
| award_is_show|       boolean|
|created_at |  varchar(50)  |



