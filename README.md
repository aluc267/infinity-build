# make image

## non-proxy
```
$ docker build -t tagName .
```

## behind proxy
```
# ready company certification file as filename: `company.crt`
$ docker build -t tagName -f Dockerfile-behind-proxy --build-arg PROXY=http://1.2.3.4:8080 .
```
