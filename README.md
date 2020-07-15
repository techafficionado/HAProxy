To start the simple node web server on different ports:

PORT=6060 node app.js
PORT=7070 node app.js
PORT=6161 node app.js
PORT=7171 node app.js

To start haproxy and see loadbalancing in action:

haproxy -f l4LoadBal.cfg
haproxy -f l7LoadBal.cfg
