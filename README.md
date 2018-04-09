WebAPI

Use:
```
https://prime-calculator.github.io/list.html?from=1&to=100&raw=true&showIndex
```

Add either:
- &raw
- &raw=true

To only show a list of the prime numbers between 1 & 100.

Extracting data

Just phrase all data from the URL (with the "&raw") using:

JavaScript:
```
window.onload = document.body.innerText
```

Add either:
- &showIndex
- &showIndex=true

To also display each prime number's index value!