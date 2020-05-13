# News-app
This news application is builtusing IBM services like: IBM Discovery Service, IBM Node Red Application. It is also integrated with slack as a slck bot.
* Code is written in Node.js, with the server-side using the Express framework and the client using ReactJS.
* Pre-built Watson Discovery News collection is used
* Watson Discovery service is accessed through the Watson Discovery API
#Flow
1. The user interacts with the Watson Discovery News Server via the app UI.
1. User input is processed and routed to the Watson Discovery News Server.
1. The Watson Discovery News Server sends user requests to the Watson Discovery Service.
1. The Watson Discovery Service queries the Watson News Collection.
1. The Watson Discovery Service sends news articles to the RSS Reader.
1. The Watson Discovery Service responds to Slack search requests.
