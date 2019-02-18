# spring-cloud问题总结
## 问题一：springboot打包问题
Spring Boot Maven Plugin打包异常及三种解决方法：Unable to find main class</br>
参考网址：https://www.cnblogs.com/thinking-better/p/7827368.html</br>
 <plugins></br>
            <plugin></br>
                <groupId>org.springframework.boot</groupId></br>
                <artifactId>spring-boot-maven-plugin</artifactId></br>
                <configuration></br>
                    <mainClass>com.xx.webapps.api.main.WebappsApiBidMain</mainClass></br>
                </configuration></br>
                <executions></br>
                    <execution></br>
                        <goals></br>
                            <goal>repackage</goal></br>
                        </goals></br>
                    </execution></br>
                </executions></br>
            </plugin></br>
        </plugins></br>
## 问题二：
