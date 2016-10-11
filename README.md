command:
```bash
$ docker-compose up -d
$ docker exec -it selenium_test bash
$ java -Dfile.encoding=ISO-8859-1 -jar /opt/selenium/selenium-server-standalone.jar -port 4447 -htmlSuite "*firefox" http://web:8080/ /opt/files/test_suite.html /opt/output/test_result.html
```

test url:<br />
http://127.0.0.1:8888/

vnc url:<br />
127.0.0.1:5900

vnc password:secret

check test result report:<br />
./test/output/result.html
