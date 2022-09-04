# WRPG Day API

## Requests

Send an HTTP GET request to <https://w-rpg.github.io/api/misc/day.json> to get a JSON response.

## Response

The JSON response references the current day in the WRPG.

|Name|Value|
|----|----|
|month|integer|
|day|integer|
|year|integer|

### Example

```json
{
    "month": 10,
    "day": 17,
    "year": 2019
}
```
