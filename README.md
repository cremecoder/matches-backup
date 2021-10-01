# Backup of matches.json, matches2.json and flag svg's for footy api

<br>

## **`matches.json`**

This is the code for GetData.js and SortData.js that the original flags API uses:
https://restcountries.eu/rest/v2/all?fields=name;flag

```
GetData.prototype.createMatchesJSON
return fs.writeFileSync("./data/matches.json", strData)

GetData.prototype.findTeam
this.apiData = require("../data/matches2.json")

SortData.prototype.sortWCFlags
if (country.name == wcCountry) {
  flags.push(country)
}
```

<br>

## **`matches2.json`**

https://restcountries.com/v2/all?fields=name,flags

<br>

## Important

> Both API's for the flags are unreliable.
