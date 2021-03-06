# irpg-web

Web interface for the IdleRPG running
KentIRC. See [here](https://graymalk.in/irc/irpg.html).

## Structure

A python script is run against the IdleRPG database extracting player
information. This is then packaged up into a JSON file and used to
populate the status page.

### Example JSON
The file is a list of objects, each object represents a user. This is
a truncated verson of the currently live IdleRPG. I only show the
character of `bunu`.


```json
[
	{
		"idled": "8357826",
		"gloves": "29",
		"boots": "61",
		"y_pos": "486",
		"amulet": "40",
		"ring": "48",
		"tunic": "84b",
		"online": "1",
		"level": "56",
		"nick": "bunu",
		"x_pos": "57",
		"on_quest": false,
		"alignment": "g",
		"username": "bunu",
		"class": "King of the Tribbles",
		"weapon": "53",
		"leggings": "35",
		"next_ttl": "176445",
		"helm": "61a",
		"charm": "48",
		"shield": "47"
	}
]
```
