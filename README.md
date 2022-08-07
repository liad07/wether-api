212 of the 365 chalenge in 2022 1 day 1 challenge
## js example
```javascript
fetch("https://liadk07.pythonanywhere.com/?city=tel aviv")
            .then(response => response.json())
            .then(data =>console.log(data.city+","+data.info+","+data.wether))
```
