PNR API
=======

_Difficulty_: __Intermediate__

A RESTful API for getting the current PNR status of an Indian Railways ticket. There is no official API provided by IR, so it is a pain for developers as they have to scrape the HTML. Let's do the dirty work for them.

## Specifications ##

A simple RESTful API which will spit out the PNR data in JSON format.

### Usage ###

Suppose your PNR is __6223797269__. You just have to do a ``GET`` at:

```
http://your-api-domain/6223797269
```

You'll get a JSON like this.

```
{
  "data": {
    "alight": {
      "code": "NDLS", 
      "name": "NEW DELHI"
    }, 
    "board": {
      "code": "JSME", 
      "name": "JASIDIH"
    }, 
    "chart_prepared": "CHART PREPARED", 
    "class": "SL", 
    "from": {
      "code": "JSME", 
      "name": "JASIDIH"
    }, 
    "passenger": [
      {
        "seat_number": "Can/Mod", 
        "status": "W/L 54,RLGN"
      }
    ], 
    "to": {
      "code": "NDLS", 
      "name": "NEW DELHI"
    }, 
    "train_name": "POORVA EXPRESS", 
    "train_number": "12303", 
    "travel_date": "5-10-2013"
  }, 
  "status": "OK"
}
```

### Implementation ###

* Language: [Python](http://python.org)
* Web Framework: [Flask](http://flask.pocoo.org)
