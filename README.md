# BurpSuite Community 1.7.32 + VMWare Rest/JSON API

Docker image with BurpSuite Community edition and Rest/JSON API endpoint by [VMWare](https://github.com/vmware/burp-rest-api).

Note that you will still need to accept the license manually.

## How to use
``
docker build -t burpsuite-co-api .
``

``
docker run -p 8080:8080 -p 8090:8090 -it burpsuite-co-api
``

## Rest/JSON endpoints
Endpoints available from this image:
- [BurpSuite's Web UI](http://localhost:8080/)
- [API Docs](http://localhost:8090/v2/api-docs)
- [Swagger UI](http://localhost:8090/swagger-ui.html#/)