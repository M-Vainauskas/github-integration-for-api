# SwaggerPetstore.KaliauseApi

All URIs are relative to *https://dev-virtserver.swaggerhub.com/mvtest1/privateAPImvt11/1.0.0*

Method | HTTP request | Description
------------- | ------------- | -------------
[**kalKaliause**](KaliauseApi.md#kalKaliause) | **POST** /kaliause | Kaliause sedi viduryje lauko
[**kaliausePut**](KaliauseApi.md#kaliausePut) | **PUT** /kaliause | Idejom kaliause


<a name="kalKaliause"></a>
# **kalKaliause**
> kalKaliause()

Kaliause sedi viduryje lauko

Kaliause yra kaliause

### Example
```javascript
var SwaggerPetstore = require('swagger_petstore');

var apiInstance = new SwaggerPetstore.KaliauseApi();

var callback = function(error, data, response) {
  if (error) {
    console.error(error);
  } else {
    console.log('API called successfully.');
  }
};
apiInstance.kalKaliause(callback);
```

### Parameters
This endpoint does not need any parameter.

### Return type

null (empty response body)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: Not defined

<a name="kaliausePut"></a>
# **kaliausePut**
> kaliausePut()

Idejom kaliause

### Example
```javascript
var SwaggerPetstore = require('swagger_petstore');

var apiInstance = new SwaggerPetstore.KaliauseApi();

var callback = function(error, data, response) {
  if (error) {
    console.error(error);
  } else {
    console.log('API called successfully.');
  }
};
apiInstance.kaliausePut(callback);
```

### Parameters
This endpoint does not need any parameter.

### Return type

null (empty response body)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: Not defined

