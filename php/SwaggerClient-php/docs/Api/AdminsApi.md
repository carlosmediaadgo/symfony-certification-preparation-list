# Swagger\Client\AdminsApi

All URIs are relative to *https://virtserver.swaggerhub.com/carlosmediaadgo/leadsender/1.0.0*

Method | HTTP request | Description
------------- | ------------- | -------------
[**addInventory**](AdminsApi.md#addInventory) | **POST** /inventory | adds an inventory item


# **addInventory**
> addInventory($inventory_item)

adds an inventory item

Adds an item to the system

### Example
```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');

$apiInstance = new Swagger\Client\Api\AdminsApi(
    // If you want use custom http client, pass your client which implements `GuzzleHttp\ClientInterface`.
    // This is optional, `GuzzleHttp\Client` will be used as default.
    new GuzzleHttp\Client()
);
$inventory_item = new \Swagger\Client\Model\InventoryItem(); // \Swagger\Client\Model\InventoryItem | Inventory item to add

try {
    $apiInstance->addInventory($inventory_item);
} catch (Exception $e) {
    echo 'Exception when calling AdminsApi->addInventory: ', $e->getMessage(), PHP_EOL;
}
?>
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **inventory_item** | [**\Swagger\Client\Model\InventoryItem**](../Model/InventoryItem.md)| Inventory item to add | [optional]

### Return type

void (empty response body)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

