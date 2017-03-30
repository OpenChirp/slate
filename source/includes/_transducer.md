
# Transducer

## Add a transducer to a device

> Example Request:

```http
POST /api/service HTTP/1.1
{
  "name":"InfluxDB Storage Service",
   
}
```

> Example Response:

```json

```

### HTTP Request

`POST /api/service`


### Request body

| Name | Type | Description | Required | Default|
|:----------|:-----|:------------|:----|:--------|
|name | String| Name of transducer , example : Temperature| Yes| - |
|unit|

## Get all transducers on a device

> Example Request :

```http
GET /api/device/582e2b2c065b2545ded3aabd/transducer HTTP/1.1

```
> Example Response :

```json


```
### HTTP Request
`GET /api/device/<ID>/transducer`

### Request Parameters
Parameter | Description
--------- | -----------
ID| ID of device

## Update a transducer
Updating a transducer is not supported.


## Publish to a transducer

## Delete a transducer


> Example Request:

```http
DELETE /api/device/582e2b2c065b2545ded3aabd HTTP/1.1
```

> Example Response :

```http
HTTP/1.1 200 OK
```
### HTTP Request
`DELETE /api/device/<ID>`

### Request Parameters
Parameter | Description
--------- | -----------
ID | ID of device to delete