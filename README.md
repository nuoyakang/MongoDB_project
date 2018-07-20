# MongoDB_project

There are two major methods of streaming data from Twitter: Streaming API and REST API. Streaming API is real-time, and it will give records from the point of query until we stop, and the later one is retrospective which will give us the records from the past to as far as the search index.
In this project report, we will do the following:
➢ Building a sample service.
The sample service can accept data from a Twitter stream and stores locally in database. This part includes:
1. Streaming tweets using Twitter REST API
• Establish the connection with Twitter.
• Establish the connection with MongoDB database.
• Define searching parameters in REST API.
• Extract twitter data with the defined searching parameters and fetching data from twitter into MongoDB.
2. Streaming tweets using Twitter Streaming API
• Establish the connection with Twitter.
Working with streaming data: Mining Twitter Data with Python and MongoDB
Scott Herford email: jherford@mail.smu.edu Nuoya Rezsonya email: nrezsonya@mail.smu.edu Lu Cheng email: lucheng@mail.smu.edu
2
• Establish the connection with MongoDB database.
• Set up the query definition in the Streaming API.
• Streaming process and store the collected data into local MongoDB.
➢ Comparing the design considerations: Real-time processing vs. Batch processing.
Real-time vs. batch processing in terms of processing and performance and scalability.
