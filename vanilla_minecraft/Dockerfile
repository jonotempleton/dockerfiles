FROM amazoncorretto:17-alpine3.15
RUN addgroup -S -g 1002 minecraftgroup && adduser -S minecraft -G minecraftgroup
USER minecraft
WORKDIR /home/minecraft/server
CMD ["java", "-Xms4G", "-Xmx8G", "-jar", "paper-1.18-16.jar", "--nogui"]
