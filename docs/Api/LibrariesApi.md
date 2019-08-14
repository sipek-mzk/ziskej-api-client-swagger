# Mzk\ZiskejApiClientSwagger\LibrariesApi

All URIs are relative to *https://ziskej-test.techlib.cz:9080/api/v1*

Method | HTTP request | Description
------------- | ------------- | -------------
[**librariesGet**](LibrariesApi.md#librariesget) | **GET** /libraries | Libraries

# **librariesGet**
> string[] librariesGet()

Libraries

Knihovny description...

### Example
```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');

$apiInstance = new Mzk\ZiskejApiClientSwagger\Api\LibrariesApi(
    // If you want use custom http client, pass your client which implements `GuzzleHttp\ClientInterface`.
    // This is optional, `GuzzleHttp\Client` will be used as default.
    new GuzzleHttp\Client()
);

try {
    $result = $apiInstance->librariesGet();
    print_r($result);
} catch (Exception $e) {
    echo 'Exception when calling LibrariesApi->librariesGet: ', $e->getMessage(), PHP_EOL;
}
?>
```

### Parameters
This endpoint does not need any parameter.

### Return type

**string[]**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

