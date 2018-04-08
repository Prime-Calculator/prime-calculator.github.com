##WebAPI

###Use:
```
https://prime-calculator.github.io/list.html?from=1&to=100&raw=true
```

###Add either:
- &raw
- &raw=true

To only show a list of the prime numbers between 1 & 100.

###Extracting data
If you have access to JavaScript. Just phrase all data from the URL (with the "&raw") using:
```
document.body.innerText
```