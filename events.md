# Sample file of 10 activities

## Sport / Health

##### This is a very small sample of the coordinates and more precisely of the object/node representing here a sports point on a map. A dataset has been retrieved from the [overpass-turbo site](https://overpass-turbo.eu/) (.geojson file) 

    {
      "type": "Feature",
      "properties": {
        "@id": "node/5022806992",
        "leisure": "fitness_station",
        "ref": "9",
        "sport": "exercise"
      },
      "geometry": {
        "type": "Point",
        "coordinates": [
          8.2022072,
          47.0903231
        ]
      },
      "id": "node/5022806992"
    },
    {
      "type": "Feature",
      "properties": {
        "@id": "node/5022806993",
        "leisure": "fitness_station",
        "ref": "8",
        "sport": "exercise"
      },
      "geometry": {
        "type": "Point",
        "coordinates": [
          8.2028174,
          47.0903632
        ]
      },
      "id": "node/5022806993"
    },
    {
    "type": "node",
    "id": 8009886564,
    "lat": 46.1392154,
    "lon": 7.1170908,
      "tags": {
        "addr:street": "Rue de l'Église",
        "fee": "yes",
        "leisure": "sports_centre",
        "name": "FullyGrimpe",
        "sport": "bouldering"
      }
    },
    {
      "type": "node",
      "id": 9520240670,
      "lat": 47.5746330,
      "lon": 7.5738407,
      "tags": {
        "addr:city": "Basel",
        "addr:housenumber": "215a",
        "addr:postcode": "4056",
        "addr:street": "Elsässerstrasse",
        "fee": "yes",
        "leisure": "sports_centre",
        "name": "ELYS Boulderloft",
        "sport": "bouldering",
        "website": "https://boulderloft.ch/"
      }
    }

     {
      "type": "node",
      "id": 755848113,
      "lat": 47.5409015,
      "lon": 7.5932896,
      "tags": {
        "leisure": "sports_centre",
        "name": "Kletterhalle 7",
        "opening_hours": "Mo-Fr 12:00-22:30, Sa,Su 10:00-19:00",
        "sport": "climbing",
        "website": "http://kletterhalle7.ch/",
        "wheelchair": "limited"
      }
    },
    {
      "type": "node",
      "id": 760345322,
      "lat": 46.3213715,
      "lon": 6.9791925,
      "tags": {
        "name": "Drapel",
        "sport": "climbing"
      }
    }
    
## Comments / Ratings
##### The data that corresponds to the ratings and the comment

    {
      "type": "node",
      "id": 123456789,
      "lat": 46.1802714,
      "lon": 6.1336587,
      "tags": {
        "name": "Le Bout du Monde",
        "sport": "tennis",
        "addr:city": "Carouge",
        "addr:housenumber": "12",
        "addr:postcode": "1227",
        "addr:street": "Rue Jacques-Grosselin",
        "website": "http://www.leboutdumonde.ch/",
        "phone": "+41 22 301 01 56",
        "email": "info@leboutdumonde.ch"
      },
      "comments": [
        {
          "id": 1,
          "user_id": 123,
          "username": "Alice",
          "date": "2022-02-20T14:30:00Z",
          "text": "J'adore ce complexe de tennis, les terrains sont en très bon état et les tarifs sont raisonnables.",
          "rating": 4
        },
        {
          "id": 2,
          "user_id": 456,
          "username": "Bob",
          "date": "2022-03-15T16:45:00Z",
          "text": "Je trouve que le service à la clientèle pourrait être amélioré, mais sinon c'est un bon endroit pour jouer au tennis.",
          "rating": 3
        }
      ]
    }

## Favorites 
##### These are a person's favorites in relation to the activities they like

    {
        "person_id": 12345,
        "person_name": "Alice",
        "favorite_activities": [
            {
                "activity_name": "Climbing",
                "activity_type": "indoor",
                "locations": [
                    {
                        "location_id": 9876,
                        "location_name": "Bloczone",
                        "latitude": 46.1895759,
                        "longitude": 6.1520384,
                        "address": "Chemin des Aulx 18, 1228 Plan-les-Ouates",
                        "website": "https://bloczone.ch/",
                        "phone": "+41 22 700 85 80"
                    },
                    {
                        "location_id": 8765,
                        "location_name": "Swiss-Roc",
                        "latitude": 46.2367129,
                        "longitude": 6.0857831,
                        "address": "Chemin des Aulx 18, 1228 Plan-les-Ouates",
                        "website": "https://www.swiss-roc.ch/",
                        "phone": "+41 22 700 13 40"
                    }
                ]
            },
            {
                "activity_name": "Tennis",
                "activity_type": "outdoor",
                "locations": [
                    {
                        "location_id": 7654,
                        "location_name": "Tennis Club de Genève",
                        "latitude": 46.2159197,
                        "longitude": 6.1594118,
                        "address": "Chemin des Châtaigniers 11, 1207 Genève",
                        "website": "http://tcg.ch/",
                        "phone": "+41 22 735 30 20"
                    },
                    {
                        "location_id": 6543,
                        "location_name": "Tennis Club de Vandoeuvres",
                        "latitude": 46.1967967,
                        "longitude": 6.1806042,
                        "address": "Chemin de la Bessonnette 32, 1253 Vandoeuvres",
                        "website": "http://tennis-club-vandoeuvres.ch/",
                        "phone": "+41 22 759 13 20"
                    }
                ]
            }
        ]
    }

## Login
#### These data represent information related to user accounts, specifically for a login feature. Each record includes the user's first and last name, email address, password, city of residence, and age. The data is in JSON format, which is commonly used for storing and exchanging data between web servers and applications. The purpose of this data is to facilitate user authentication and access control to a web-based service or application.

    {
        "last_name": "Dupont",
        "first_name": "Jean",
        "email": "jean.dupont@example.com",
        "password": "motdepasse123",
        "city": "Lancy",
        "age": 30
    },
    {
        "last_name": "Martin",
        "first_name": "Julie",
        "email": "julie.martin@example.com",
        "password": "1234abcd",
        "city": "Carouge",
        "age": 25
    }