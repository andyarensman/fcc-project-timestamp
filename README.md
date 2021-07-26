# FreeCodeCamp: APIs and Microservices Project #1 - Timestamp Microservice

FreeCodeCamp's first APIs and Microservices project, completed. This is part of the APIs and Microservices certification. You can find the hosted project at [this link](https://boilerplate-project-timestamp.andyarensman.repl.co/). This project demonstrates understanding of Node and Express.

Here are [FreeCodeCamp's](https://www.freecodecamp.org/learn/apis-and-microservices/apis-and-microservices-projects/timestamp-microservice) requirements to complete the project:
>A request to `/api/:date?` with a valid date should return a JSON object with a `unix` key that is a Unix timestamp of the input date in milliseconds
>
>A request to `/api/:date?` with a valid date should return a JSON object with a `utc` key that is a string of the input date in the format: `Thu, 01 Jan 1970 00:00:00 GMT`
>
>A request to `/api/1451001600000` should return `{ unix: 1451001600000, utc: "Fri, 25 Dec 2015 00:00:00 GMT" }`
>
>Your project can handle dates that can be successfully parsed by `new Date(date_string)`
>
>If the input date string is invalid, the api returns an object having the structure `{ error : "Invalid Date" }`
>
>An empty date parameter should return the current time in a JSON object with a `unix` key
>
>An empty date parameter should return the current time in a JSON object with a `utc` key

Completed ~6/10/21 on [replit](https://replit.com/@AndyArensman/boilerplate-project-timestamp) - uploaded to GitHub on 7/22/21
