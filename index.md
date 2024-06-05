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

## License-remaining

### Description
Gets information about the remaining license.

### Request
- **Method:** GET
- **URL:** [https://www.tweakytools.com/api/license-remaining](https://www.tweakytools.com/api/license-remaining)
- **Headers:**
  - Authorization: 4903927f9a5d0fa8b4d817db1acae454

### Response
- No response defined

## Products

### Description
Gets information about products.

### Request
- **Method:** GET
- **URL:** [https://www.tweakytools.com/api/products](https://www.tweakytools.com/api/products)
- **Headers:**
  - Authorization: 4903927f9a5d0fa8b4d817db1acae454

### Response
- No response defined

## Product-config

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
# Software Management

## Install Software

### Description
Installs software via the Tweaky Tool API.

### Request
- **Method:** POST
- **URL:** https://www.tweakytools.com/api/install-software
- **Headers:**
  - Authorization: 4903927f9a5d0fa8b4d817db1acae454

### Response
- No response defined

## Uninstall Software

### Description
Uninstalls software via the Tweaky Tool API.

### Request
- **Method:** POST
- **URL:** https://www.tweakytools.com/api/uninstall-software
- **Headers:**
  - Authorization: 4903927f9a5d0fa8b4d817db1acae454

### Response
- No response defined

## Renew Now

### Description
Renews the software license.

### Request
- **Method:** POST
- **URL:** https://www.tweakytools.com/api/renew-now
- **Headers:**
  - Authorization: 4903927f9a5d0fa8b4d817db1acae454

### Response
- No response defined

