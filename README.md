## Access-the-value-of-key2-from-the-following-JSON
## Sample code to check the access value
```sh
import json

sampleJson = """{"key1": "value1", "key2": "value2"}"""

data = json.loads(sampleJson)
print(data['key2'])
```
## Expected output
value2
