# verifik-test

The candidate will utilize this mini angular app template where they can see examples of screens already built by our developers in the Team.

The Test is based on 3 simple things:

First the candidate will download the repository and run the project locally with the `ng` commands, after that, the candidate will build a page 

just like this one here (https://status.onesignal.com/) but inside our platform.

## Details:

1. The page should display the status of each of our endpoints (https://docs.verifik.co)

2. You will request every 1 minute the status of each endpoint ( for the sake of the test only ) but in a real case scenario we will ping it every 10-15 minutes.

3. The design should look very similar to the one provided by onesignal.com. We care about nice UX/UI so it's important that the developer knows how to make nice designs.

4. each ping will represent a green or red bar. You will save in localStorage each time you request the API to see the status of each endpoint.



## Bonus points:

1. Create a mini Node.js project with MongoDB to store those pings into a Collection so when we refresh or open it in another tab, it will still keep the previous PINGS which represent the red/green bars on each endpoint.




