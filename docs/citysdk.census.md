# Global





* * *

### parseToVariable(aliasOrVariable) 

Checks to see if a string is in the aliases dictionary and returns the appropriate variable if so.

**Parameters**

**aliasOrVariable**: `string`, A string to parse into a variable string.

**Returns**: `string`, Variable string


### latLngToFIPS(lat, lng, callback) 

Converts co-ordinates to Census FIPS via the Geocoder API

**Parameters**

**lat**: `float`, Latitude

**lng**: `float`, Longitude

**callback**: `function`, Callback function



### acsSummaryRequest(request, callback) 

Makes a request to the ACS5 Summary API. Should be used via APIRequest and not on its own, typically

**Parameters**

**request**: `object`, JSON request (see APIRequest)

**callback**: `function`, Makes a request to the ACS5 Summary API. Should be used via APIRequest and not on its own, typically



### APIRequest(request, callback) 

Processes a data request by looking at a JSON request

**Parameters**

**request**: `object`, The JSON object of the request

**callback**: `function`, A callback, which accepts a response parameter



### GEORequest(request, callback) 

Get a city's geography by name, as well as requested variables. Currently supported locations:

**Parameters**

**request**: `object`, The JSON request

**callback**: `function`, The callback to take the response, which is geoJSON




* * *









