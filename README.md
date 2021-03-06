Universal **_EVENT_** [model](https://aping.readme.io/docs/models) for [apiNG](https://github.com/JohnnyTheTank/apiNG)

# Supported apiNG Plugins
- [x] **Facebook** ([apiNG-plugin-facebook](https://github.com/JohnnyTheTank/apiNG-plugin-facebook))
- [x] **BandsInTown** ([apiNG-plugin-bandsintown](https://github.com/JohnnyTheTank/apiNG-plugin-bandsintown))


# JavaScript
```JavaScript
var event = {
    platform: undefined, //NAME of platform ( "facebook", "bandsintown" , ...)
    artist_name: undefined, //name of artist or host
    artist_id: undefined, //id of artist or host
    artist_link: undefined, //link to artist or host
    start_timestamp: undefined, //timestamp of start date
    start_date_time: undefined, //datetime of start date
    end_timestamp: undefined, //timestamp of end date
    end_date_time: undefined, //datetime of end date
    event_url: undefined, //URL to the event
    ticket_url: undefined, //URL to the ticket
    sold_out: undefined, //boolean (true = sold out)
    intern_id: undefined, // INTERN ID of event (facebook id, bandsintown id, ...)
    caption: undefined, //event title
    text: undefined, //event description
    img_url: undefined, //preview image url (best case 700px)
    place_name: undefined, //location/place name of the location
    city: undefined, //city name of the location
    country: undefined, //country name of the location
    latitude: undefined, //latitude of the coordinates
    longitude: undefined, //longitude of the coordinates
    street: undefined, //street of the location
    zip: undefined, //postal zip of the location
    source: undefined //different payload
};
```

# JSON

```JSON
{
  "platform": false,
  "artist_name": false,
  "artist_id": false,
  "artist_link": false,
  "start_timestamp": false,
  "start_date_time": false,
  "end_timestamp": false,
  "end_date_time": false,
  "event_url": false,
  "ticket_url": false,
  "sold_out": false,
  "intern_id": false,
  "caption": false,
  "text": false,
  "img_url": false,
  "place_name": false,
  "city": false,
  "country": false,
  "latitude": false,
  "longitude": false,
  "street": false,
  "zip": false,
  "source": false
}
```