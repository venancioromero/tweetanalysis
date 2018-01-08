# tweetanalysis

## Instructions

  
```bash
git clone https://github.com/venancioromero/tweetanalysis.git

cd tweetanalysis

docker-compose run \
-e DOWNLOAD_TIME=<TIME IN SECONDS> \
-e ACCESS_TOKEN_KEY=<YOUR_ACCESS_TOKEN_KEY> \
-e ACCESS_TOKEN_SECRET=<YOU_ACCESS_TOKEN_SECRET> \
-e CONSUMER_KEY=<YOU_CONSUMER_KEY> \
-e CONSUMER_SECRET=<YOU_CONSUMER_SECRET> \
tweetanalysis
```

