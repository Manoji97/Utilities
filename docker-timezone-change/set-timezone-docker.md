#### In the Docker File add:

```Docker
    ENV TZ=Asia/Kolkata
    RUN ln -snf /usr/share/zoneinfo/$TZ /etc/localtime && echo $TZ > /etc/timezone
```