Import library
```angular2html
import json
```

Read json object
```
data = json.loads(string)
print(data)
```

Convert json to python object
```angular2html
data['people']
```

Loop through the list
```angular2html
for person in data['people]:
print(person['name])
```

