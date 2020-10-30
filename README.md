## PrettyPrint-following-JSON-data
## Sample code to check the json data
```sh
sampleJson = {"key1" : "value2", "key2" : "value2", "key3" : "value3"}
prettyPrintedJson  = json.dumps(sampleJson, indent=2, separators=(",", " = "))
```
## Expected Output

  "key1" = "value2",
  "key2" = "value2",
  "key3" = "value3"
}
