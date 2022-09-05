# WRPG Day API

## Requests

Send an HTTP GET request to <https://w-rpg.github.io/api/day.json> to get a JSON response.

## Response

The JSON response references the current day in the WRPG.

|Field|Description|
|----|----|
|month|Current Month|
|day|Current Day|
|year|Current Year|

### Example

```json
{
    "month": 10,
    "day": 17,
    "year": 2019
}
```
