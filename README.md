## Backup of matches.json and matches2.json for footy api

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

## Important

> restcountries.eu api where the flags are pullled from has crashed in the past.

> It's end points may not be secure!
