# Wiremock Stub Server

This project includes the files for mocking requests using wiremock.

```shell
docker pull wiremock/wiremock
```

```shell
docker build -t hastiserver -f Dockerfile .
```

Run image with:

```shell
docker run -p 8080:8080 hastiserver   
```
## Hasti Api Request examples

Add order

```shell
curl --location --request POST 'localhost:8080/api/v1/VendorAgent/AddOrder' \
--header 'Content-type: application/json' \
--data ''
```
