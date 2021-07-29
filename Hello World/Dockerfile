FROM java:8
WORKDIR /app
COPY src ./src
ENV CLASSPATH=./src
RUN javac ./src/MainApp.java
RUN dir ./src
CMD ["java", "MainApp"]