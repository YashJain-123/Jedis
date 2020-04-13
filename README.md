# Jedis

A mini-project using Java to crawl a page containing a list of states which in turn extracts the information about all the states from Wikipedia and stores it in Redis database in the form of JSON.

#### Tools & Library used:

1. Jedis= It is a client library in Java for Redis – the popular in-memory data structure store. To use it in the project add the following code in pom.xml file-

```
        <dependency>
            <groupId>redis.clients</groupId>
            <artifactId>jedis</artifactId>
            <version>2.8.1</version>
        </dependency>
```
We also need a redis-server with which we can store the JSON key-value pair in the database. Also to have an interactive mode, we can install redis-cli as well. To do so follow the below steps:-

1.	wget http://download.redis.io/redis-stable.tar.gz
2.	tar xvzf redis-stable.tar.gz
3.	cd redis-stable
4.	make
5.	sudo cp src/redis-server /usr/local/bin/
6.	sudo cp src/redis-cli /usr/local/bin/
7.	sudo make install
8. 	To run redis server= 
		  >> redis-server
9.	To go in the interactive mode=
		  >>redis-cli
10. Step 9 won't work if redis server is not working.

### OUTPUT

![image](https://user-images.githubusercontent.com/63559607/79117703-79862180-7da9-11ea-9b1c-e46030fb45a4.png)


![image](https://user-images.githubusercontent.com/63559607/79117756-9c183a80-7da9-11ea-838d-19e368858540.png)

