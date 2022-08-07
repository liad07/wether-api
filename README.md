212 of the 365 chalenge in 2022 1 day 1 challenge
## javascript example
```javascript
fetch("https://liadk07.pythonanywhere.com/?city=tel aviv")
            .then(response => response.json())
            .then(data =>console.log(data.city+","+data.info+","+data.wether))
```
## python example
``` python
import requests
r = requests.get("https://liadk07.pythonanywhere.com/?city=tel aviv")
print(r.json())
```
