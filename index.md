# Tweaky Tool API Documentation

## Table of Contents
- [Authenticate](#Authenticate)
- [version](#version)
- [today](#today)
- [license-remaining](#license-remaining)
- [products](#products)
- [product-config](#product-config)
- [install-software](#install-software)
- [uninstall-software](#uninstall-software)
- [renew-now](#renew-now)

## authenticate

### Description
Authenticates the user.

### Request
- **Method:** GET
- **URL:** [https://www.tweakytools.com/api/authenticate](https://www.tweakytools.com/api/authenticate)
- **Headers:**
  - Authorization: 4903927f9a5d0fa8b4d817db1acae454

### Response
- No response defined

## version

### Description
Gets the version information.

### Request
- **Method:** GET
- **URL:** [https://www.tweakytools.com/api/version](https://www.tweakytools.com/api/version)
- **Headers:**
  - Authorization: 4903927f9a5d0fa8b4d817db1acae454

### Response
- No response defined

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

## license-remaining

### Description
Gets information about the remaining license.

### Request
- **Method:** GET
- **URL:** [https://www.tweakytools.com/api/license-remaining](https://www.tweakytools.com/api/license-remaining)
- **Headers:**
  - Authorization: 4903927f9a5d0fa8b4d817db1acae454

### Response
- No response defined

## products

### Description
Gets information about products.

### Request
- **Method:** GET
- **URL:** [https://www.tweakytools.com/api/products](https://www.tweakytools.com/api/products)
- **Headers:**
  - Authorization: 4903927f9a5d0fa8b4d817db1acae454

### Response
- No response defined

## product-config

### Description
Gets configuration information about a product.

### Request
- **Method:** GET
- **URL:** [https://www.tweakytools.com/api/product-config?id=1](https://www.tweakytools.com/api/product-config?id=1)
- **Headers:**
  - Authorization: 4903927f9a5d0fa8b4d817db1acae454
- **Body:**
- ```json
  {
      "id": 1
  }
```
---
