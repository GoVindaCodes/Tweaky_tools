# Tweaky Tool API Documentation

## Table of Contents
- [Authenticate](#Authenticate)
- [Check version](#version)
- [Check today](#today)
- [License-remaining](#license-remaining)
- [Products](#products)
- [Product-config](#product-config)
- [Install-software](#install-software)
- [Uninstall-software](#uninstall-software)
- [Renew-now](#renew-now)

## Authenticate

### Request

- Method: GET
- URL: [https://www.tweakytools.com/api/authenticate?hash_key=79dbbcc50900fbd02b0ecbfec09adbb9c83b0e788bb1f83076a2c28e0c3e6730](https://www.tweakytools.com/api/authenticate?hash_key=79dbbcc50900fbd02b0ecbfec09adbb9c83b0e788bb1f83076a2c28e0c3e6730)

**Parameters**:

| Parameter  | Type   | Description                |
|------------|--------|----------------------------|
| hash_key   | string | Hash Key (Required)        |
| productid  | string | Product ID (Required)      |

## Today

### Request

- Method: GET
- URL: [https://www.tweakytools.com/api/today](https://www.tweakytools.com/api/today)

## License Remaining

### Request

- Method: GET
- URL: [https://www.tweakytools.com/api/license-remaining?hash_key=6e22fcce66c0968cd81a424fa3083873e83964c12ebb78e89a78ed4b8c0d9082](https://www.tweakytools.com/api/license-remaining?hash_key=6e22fcce66c0968cd81a424fa3083873e83964c12ebb78e89a78ed4b8c0d9082)

**Parameters**:

| Parameter  | Type   | Description                |
|------------|--------|----------------------------|
| hash_key   | string | Hash Key (Required)        |

## Product Config

### Request

- Method: GET
- URL: [https://www.tweakytools.com/api/products](https://www.tweakytools.com/api/products)

## Product Config

### Request

- Method: GET
- URL: [{{live_registermart}}/api/product-config?id=eyJpdiI6Ik1JYnpXSHZTNmVHYkczTER2YVpsaVE9PSIsInZhbHVlIjoiaXI0eW03TEU0c3FrM3BFUk9ZTnVmQT09IiwibWFjIjoiMjcyZDA5M2U2OGIxNWFjNTQzMDNjMTA1NGQyMDExYjBmMzBjYzgyYjZjMTU3ZDBjNzlkYzg4YTE0ZTRiMWE5YSIsInRhZyI6IiJ9](null)

## Version

### Request

- Method: GET
- URL: [{{live_registermart}}/api/version?productid=eyJpdiI6IkRxbDc4UnlHbEM2S25oL2t1TGJyNmc9PSIsInZhbHVlIjoiMWxoR0RFQ2JsVDVhVndIQjBmekZadz09IiwibWFjIjoiNDQxNjM1ODhmZDdlZDRjYmM4NjQ5ZWQzZjhkOGRkMDI1MGNmNTNlNmMyOGRhYWJjNDkwY2ZjNTFmOTY5NzQwMyIsInRhZyI6IiJ9](null)

**Parameters**:

| Parameter  | Type   | Description                |
|------------|--------|----------------------------|
| productid  | string | Product ID (Required)      |
## today

### Description
Gets information about today.

### Request
- **Method:** GET
- **URL:** [https://www.tweakytools.com/api/today](https://www.tweakytools.com/api/today)
- **Headers:**
  - Authorization: 4903927f9a5d0fa8b4d817db1acae454

### Response
- No response defined

## License-remaining

### Description
Gets information about the remaining license.

### Request
- **Method:** GET
- **URL:** [https://www.tweakytools.com/api/license-remaining?hash_key=6e22fcce66c0968cd81a424fa3083873e83964c12ebb78e89a78ed4b8c0d9082](https://www.tweakytools.com/api/license-remaining?hash_key=6e22fcce66c0968cd81a424fa3083873e83964c12ebb78e89a78ed4b8c0d9082)

### Response
- No response defined

## Products

### Description
Gets information about products.

### Request
- **Method:** GET
- **URL:** [https://www.tweakytools.com/api/products](https://www.tweakytools.com/api/products)

### Response
- No response defined

## Product-config

### Description
Gets configuration information about a product.

### Request
- **Method:** GET
- **URL:** [{{live_registermart}}/api/product-config?id=eyJpdiI6Ik1JYnpXSHZTNmVHYkczTER2YVpsaVE9PSIsInZhbHVlIjoiaXI0eW03TEU0c3FrM3BFUk9ZTnVmQT09IiwibWFjIjoiMjcyZDA5M2U2OGIxNWFjNTQzMDNjMTA1NGQyMDExYjBmMzBjYzgyYjZjMTU3ZDBjNzlkYzg4YTE0ZTRiMWE5YSIsInRhZyI6IiJ9](https://registersmart.io/api/product-config?id=eyJpdiI6Ik1JYnpXSHZTNmVHYkczTER2YVpsaVE9PSIsInZhbHVlIjoiaXI0eW03TEU0c3FrM3BFUk9ZTnVmQT09IiwibWFjIjoiMjcyZDA5M2U2OGIxNWFjNTQzMDNjMTA1NGQyMDExYjBmMzBjYzgyYjZjMTU3ZDBjNzlkYzg4YTE0ZTRiMWE5YSIsInRhZyI6IiJ9)
- **Headers:**
  - Authorization: 4903927f9a5d0fa8b4d817db1acae454

### Response
- No response defined
