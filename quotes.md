# WRPG Quotes API

## Requests

Send an HTTP GET request to <https://w-rpg.github.io/api/quotes.json> to get a JSON response.

## Response

The response you should receive from the Quotes API is a dictionary of lists containing strings. Dictionary keys will reference the source of the quote, whether it be from a character or external media. Note that all keys are lowercase.  
For example, if you wanted a quote associated with [Erik Ferata](https://w-rpg.github.io/vhouwiki/#Erik%20Ferata), you could send a request to the API and look for a random entry in the value of the "erik" key.

### Example

```json
{
    "erik": [
        "Erik: Mastard."
    ]
}
```
