# WRPG Character API

## Requests

Send an HTTP GET request to <https://w-rpg.github.io/api/character.json> to get a JSON response.

## Responses

The JSON response of the character API is a dictionary of dictionaries that contain details about a character. Any of the fields may return as null.

|Field|Description|
|-----|-----------|
|full_name|String containing character's full name.|
|icon|String containing link to an image of the character.|
|bio|String containing a short description of the character.|
|nicknames|List of strings that serve as nicknames the character may go by, or be given by other characters.|
|status|String containing the current status of the character. Often "Alive," "Deceased," or "Unknown."|
|species|String containing the species of the character.|
|gender|String containing the gender of the character.|
|pronouns|String containing the character's pronouns.|
|mbti|String containing the character's MBTI.|
|orientation|String containing the character's sexual/romantic orientation.|
|occupation|List of strings containing current or former occupations of the character.|
|goals|List of strings containing the character's primary goals.|
|strengths|List of strings containing the character's strengths.|
|weaknesses|List of strings containing the character's weaknesses.|
|abilities|List of strings containing various special abilities the character may possess.|
|birthplace|String containing the birthplace of the character.|
|nationality|String containing the nationality descriptor of the character.|
|birthday|Dictionary containing the month, day, and year of the character's birth.|
|height|String containing the character's height.|
|hair_color|String containing the character's hair color.|
|eye_color|String containing the character's eye color.|
|sleep_schedule|String describing the character's sleep cycle.|
|hobbies|List of strings containing the character's hobbies.|
|favorite_color|String containing the character's favorite color.|
|favorite_food|String containing the character's favorite food.|
|least_favorite_food|String containing the character's least favorite food.|
|chocolate_preference|String containing the character's preference in chocolate.|
|coffee_preference|String containing the character's preference in coffee.|
|fears|List of strings containing the character's greatest fears.|
|influences|List of strings containing the character's greatest influences.|
|family|List of strings containing the character's family members.|
|friends|List of strings containing the character's close friends.|
|allies|List of strings containing the character's allies.|
|neutral|List of strings containing entities the character is completely neutral towards.|
|enemies|List of strings containing the character's enemies.|
|vibes|Dictionary of the character's Vibes.|

### birthday

|Field|Description|
|-----|-----------|
|m|Month of the character's birth.|
|d|Day of the character's birth.|
|y|Year of the character's birth.|

### vibes

|Field|Description|
|-----|-----------|
|baby|Baby Value|
|soft|Soft Value|
|clown|Clown Value|
|gremlin|Gremlin Value|
|feral|Feral Value|
|cursed|Cursed Value|
|pass|Whether or not the character passes the Vibe Check|
