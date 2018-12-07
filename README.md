docker-compose-sample



spring.datasource.url=jdbc:mysql://mysql:3306/one?serverTimezone=UTC&useUnicode=true&characterEncoding=utf-8


location /api/{
		#proxy_pass http://172.16.238.11:8080;
		proxy_pass http://java:8080;
	}
