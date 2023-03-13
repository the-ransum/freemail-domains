# freemail-domains
Compiled list of freemail provider domains.

## Data Handling

- [View Raw](https://raw.githubusercontent.com/xransum/freemail-domains/main/domains.txt)

**Javascript**

```javascript
var domains = await fetch('https://raw.githubusercontent.com/the-ransum/freemail-domains/main/domains.txt').then(r => r.text()).then(r => r.split(/\n/g));
domains // Array(3753) [ "1033edge.com", "11mail.com", "123.com", "123box.net", … ]
```
