#

##

Create a `zowe.config.user.json` with the host IP, user, and password using this template:

```jsonc
{
    "$schema": "./zowe.schema.json",
    "profiles": {
        "mtm": {
            "type": "zosmf",
            "properties": {
                "host": "xxx.xxx.xxx.xxx", // put MTM host IP address here without `http://` prefix
                "user": "xxxxxxx", // put your user ID here
                "password": "xxxxxxxx" // put your password here
                
            }
        }
    }
}
```
