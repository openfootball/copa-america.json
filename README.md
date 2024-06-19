# copa-america.json

Free open public domain football data in the JSON (JavaScript Object Notation)
data interchange format.
Tournaments include:

- Copa América 2021
- Copa América 2024 

Example - Copa América 2024 Match Schedule (Fixtures and Results) - [`2024/copa.json`](https://raw.githubusercontent.com/openfootball/copa-america.json/master/2024/copa.json):

``` json
{
  "name": "Copa América 2024",
  "rounds": [
    {
      "name": "Matchday 1",
      "matches": [
        {
          "num": 1,
          "date": "2024-06-20",
          "time": "20:00",
          "team1": { "name": "Argentina", "code": "ARG" },
          "team2": { "name": "Canada",    "code": "CAN" },
          "score": {},
          "group": "Group A"
        },
        {
          "num": 2,
          "date": "2024-06-21",
          "time": "19:00",
          "team1": { "name": "Peru",  "code": "PER" },
          "team2": { "name": "Chile", "code": "CHI" },
          "score": {},
          "group": "Group A"
        },
        ...
      ],
    },
  ],
}
```


## Updates / Contributions Welcome - Please Update the Football.TXT Sources

Note: The JSON files get (auto-)generated using the datasets in the Football.TXT format, thus, **please do NOT
edit the (auto-)generated JSON files but the Football.TXT sources (upstream) in the tournament repos** e.g.:

- Copa América in [**`/copa-america`**](https://github.com/openfootball/copa-america)

Note: For the Copa América 2024 please update the source text file
[`/copa-america/2024--usa/copa.txt`](https://github.com/openfootball/copa-america/blob/master/2024--usa/copa.txt) 
for the group and knockout (quarter-finals, semi-finals, etc.) stage.


## Add Your Leagues and Tournaments!

Any leagues or tournaments missing? Contributions welcome!
For starting your own repo from scratch see the [League Quick Starter Kit](https://github.com/openfootball/league-starter).


## More - Add Your Scripts Here

Your Script Here



## License

The copa-america.json schema, data and scripts are dedicated to the public domain. Use it as you please with no restrictions whatsoever.




## Questions? Comments?

Yes, you can. More than welcome.
See [Help & Support »](https://github.com/openfootball/help)

