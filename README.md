build
```bash
docker build . -t ctnelson1997/cs571-s24-hw3-api
docker push ctnelson1997/cs571-s24-hw3-api
```

run
```bash
docker pull ctnelson1997/cs571-s24-hw3-api
docker run --name=cs571_s24_hw3_api -d --restart=always -p 58103:58103 -v /cs571/s24/hw3:/cs571 ctnelson1997/cs571-s24-hw3-api
```

run fa
```bash
docker pull ctnelson1997/cs571-s24-hw3-api
docker run --name=cs571_fa_s24_hw3_api -d --restart=always -p 59103:58103 -v /cs571_fa/s24/hw3:/cs571 ctnelson1997/cs571-s24-hw3-api
```
