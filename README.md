# python-instant-client12c

1. create folder ./oracle-instantclient
2. download Oracle instant Client for Linux x86-64 version 12.2.0.1.0 https://www.oracle.com/technetwork/topics/linuxx86-64soft-092277.html
    - instantclient-basic-linux.x64-12.2.0.1.0.zip
    - instantclient-sdk-linux.x64-12.2.0.1.0.zip
    - instantclient-sqlplus-linux.x64-12.2.0.1.0.zip
3. copy *.zip to ./oracle-instantclient


__Build:__

```docker build -t . temp-images```


__RUN:__ 

- Golang
    - ```docker build . -t img-golang -f Dockerfile.golang```

- NodeJS
    - ```docker build . -t img-nodejs -f Dockerfile.nodejs```

- Python
    - ```docker build . -t img-python -f Dockerfile.python```


