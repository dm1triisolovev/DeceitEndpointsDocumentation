## Auth: Cloud client authorization
URL: https://api-staging.deceit.gg/auth \
Method: POST \
Auth Required: No

## Parameters
`module`: Authorization module | String \
`session`: Current session | String \
`token`: Jwt token | String \
`version`: Game version | String \
`name` steam username | String \
`properties`: unknown | Object

## Example Response: (Success)
```json
{
    "success": true,
    "token": "eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJhdWQiOiJ1c2VyIiwic3ViIjoiY2xvdWQtY2xpZW50IiwiYWN0Ijoie1wiZWF0XCI6XCJzdGVhbVwiLFwiZWFpZFwiOlwiNzAwMDAwMDAwMDAwMDAwMDBcIixcInBsdGZtXCI6XCJzdGVhbVwiLFwiZHR5XCI6bnVsbH0iLCJzZXNzaW9uIjoiMjI0QUVEMDA0RkRFQ0NDMTA2M0U1QkI1QTYyOEFFOUUiLCJpc3MiOiJodHRwczovL2RlY2VpdC1jbG91ZC1qd2tzLnMzLmV1LXdlc3QtMS5hbWF6b25hd3MuY29tL3Byb2QiLCJuYW1lIjoiZWR3NHJkIiwicGxhdGZvcm1JZCI6IjAwMDIwZTAwMDAwOTAwMDAwMDAwMDAwMDAwMDAwMDAwIiwiZXhwIjoxNzY4MjA4NDcyLCJ1c2VySWQiOiI3MDBmYTA4MC0wMDAwLTAwMDAtMDAwMC0wMDAwMDAwMDAwMDAiLCJ2ZXJzaW9uIjoicmVsZWFzZS0xMjA5OCIsImRlbW8iOmZhbHNlfQ.K0MsK6xuBz8rvYBj3vZSfflwGeiWLFHKjEVzln8l4l0",
    "expiry": 1768208472864,
    "demo": false,
    "error": null,
    "userId": "700fa080-0000-0000-0000-000000000000"
}
```

## C/P Payload
```json
{
	"module": "EOS",
	"session": "224AED004FDECCC1063E5BB5A628AE9E",
	"token": "eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJhdWQiOiJ1c2VyIiwic3ViIjoiY2xvdWQtY2xpZW50IiwiYWN0Ijoie1wiZWF0XCI6XCJzdGVhbVwiLFwiZWFpZFwiOlwiNzAwMDAwMDAwMDAwMDAwMDBcIixcInBsdGZtXCI6XCJzdGVhbVwiLFwiZHR5XCI6bnVsbH0iLCJzZXNzaW9uIjoiMjI0QUVEMDA0RkRFQ0NDMTA2M0U1QkI1QTYyOEFFOUUiLCJpc3MiOiJodHRwczovL2RlY2VpdC1jbG91ZC1qd2tzLnMzLmV1LXdlc3QtMS5hbWF6b25hd3MuY29tL3Byb2QiLCJuYW1lIjoiZWR3NHJkIiwicGxhdGZvcm1JZCI6IjAwMDIwZTAwMDAwOTAwMDAwMDAwMDAwMDAwMDAwMDAwIiwiZXhwIjoxNzY4MjA4NDcyLCJ1c2VySWQiOiI3MDBmYTA4MC0wMDAwLTAwMDAtMDAwMC0wMDAwMDAwMDAwMDAiLCJ2ZXJzaW9uIjoicmVsZWFzZS0xMjA5OCIsImRlbW8iOmZhbHNlfQ.K0MsK6xuBz8rvYBj3vZSfflwGeiWLFHKjEVzln8l4l0",
	"version": "release-12098",
	"name": "edw4rd",
	"properties":
	{
	}
}
```