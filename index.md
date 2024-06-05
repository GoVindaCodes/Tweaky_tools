# Tweaky Tool API Documentation

## Table of Contents
- [Authenticate](#authenticate)
- [Check Version](#version)
- [Check Today](#today)
- [License Remaining](#license-remaining)
- [Products](#products)
- [Product Config](#product-config)
- [Install Software](#install-software)
- [Uninstall Software](#uninstall-software)
- [Renew Now](#renew-now)

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

## Products

### Request

- Method: GET
- URL: [https://www.tweakytools.com/api/products](https://www.tweakytools.com/api/products)

## Product Config

### Request

- Method: GET
- URL: [https://registersmart.io/api/product-config?id=eyJpdiI6Ik1JYnpXSHZTNmVHYkczTER2YVpsaVE9PSIsInZhbHVlIjoiaXI0eW03TEU0c3FrM3BFUk9ZTnVmQT09IiwibWFjIjoiMjcyZDA5M2U2OGIxNWFjNTQzMDNjMTA1NGQyMDExYjBmMzBjYzgyYjZjMTU3ZDBjNzlkYzg4YTE0ZTRiMWE5YSIsInRhZyI6IiJ9](https://registersmart.io/api/product-config?id=eyJpdiI6Ik1JYnpXSHZTNmVHYkczTER2YVpsaVE9PSIsInZhbHVlIjoiaXI0eW03TEU0c3FrM3BFUk9ZTnVmQT09IiwibWFjIjoiMjcyZDA5M2U2OGIxNWFjNTQzMDNjMTA1NGQyMDExYjBmMzBjYzgyYjZjMTU3ZDBjNzlkYzg4YTE0ZTRiMWE5YSIsInRhZyI6IiJ9)

**Parameters**:

| Parameter  | Type   | Description                |
|------------|--------|----------------------------|
| id         | string | Config ID (Required)       |

## Version

### Request

- Method: GET
- URL: [https://registersmart.io/api/version?productid=eyJpdiI6IkRxbDc4UnlHbEM2S25oL2t1TGJyNmc9PSIsInZhbHVlIjoiMWxoR0RFQ2JsVDVhVndIQjBmekZadz09IiwibWFjIjoiNDQxNjM1ODhmZDdlZDRjYmM4NjQ5ZWQzZjhkOGRkMDI1MGNmNTNlNmMyOGRhYWJjNDkwY2ZjNTFmOTY5NzQwMyIsInRhZyI6IiJ9](https://registersmart.io/api/version?productid=eyJpdiI6IkRxbDc4UnlHbEM2S25oL2t1TGJyNmc9PSIsInZhbHVlIjoiMWxoR0RFQ2JsVDVhVndIQjBmekZadz09IiwibWFjIjoiNDQxNjM1ODhmZDdlZDRjYmM4NjQ5ZWQzZjhkOGRkMDI1MGNmNTNlNmMyOGRhYWJjNDkwY2ZjNTFmOTY5NzQwMyIsInRhZyI6IiJ9)

**Parameters**:

| Parameter  | Type   | Description                |
|------------|--------|----------------------------|
| productid  | string | Product ID (Required)      |

## Install Software

### Request

- Method: GET/POST/PUT/DELETE
- URL: [URL of the endpoint]

## Uninstall Software

### Request

- Method: GET/POST/PUT/DELETE
- URL: [URL of the endpoint]

## Renew Now

### Request

- Method: GET/POST/PUT/DELETE
- URL: [URL of the endpoint]
