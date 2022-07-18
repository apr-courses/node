# Async/await

## Homework

### The task description

We need to write the 2 scripts. First - add users to the blacklist. Second - check if the user is already on the blacklist.

First script
1. Create a blacklist.json file in your project. [{"ip": "192.168.1.1", "country": "Ukraine"}]
2. You have to check if your IP from Ukraine. If yes - add this IP to the blacklist and print it to console.
4. To get info about the user IP and Country use open source API - [https://ip-api.com/docs/api:json](https://ip-api.com/docs/api:json)

Second script
1. Receive the user IP by using [https://ip-api.com/docs/api:json](https://ip-api.com/docs/api:json)
2. Compare the IP with the IPs in blacklist.
3. Print "you are blocked" or "you pass control"

The result should be:
1. After running the first script - your IP should be in console and added to blacklist.json
2. After running the second script - you should print message - you are blocked (if IP already in blacklist)

Important points!
The IP should not duplicate in blacklist.

Additional option: set administrator's ids and total count of users as environment variables.
