node worker.js --wtype wrk-node-http --env production --port 3000

docker build -t app-node .

docker run app-node worker.js --wtype wrk-node-http --env production --port 3000