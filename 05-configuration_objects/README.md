# 05-service ☸
Basic documentation about Configuration Objects of Kubernetes

### Short Description
-----------------
* CONFIG_MAP:

  Contains configuration data for the pods to consume.

* SECRET:

  Contains secret data of a certain type.

### Generate value for secrets
-----------------
* Execute command bellow:

  > echo "my_value_of_my_secret" | base64

    ```⚠️ base64 is not safe ```


