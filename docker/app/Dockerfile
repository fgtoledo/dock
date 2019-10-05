FROM java:8

ADD ./ Cadastro.jar
EXPOSE 8080
CMD java -jar Cadastro.jar
CMD ["java", "-classpath" "mysql-connector-java-8.0.17.jar:.", "Cadastro.jar"]


