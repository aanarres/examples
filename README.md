#What is Greta
Greta decentralizes data distribution, just as internet was once intended. It's pure JS and works on top of any hosting and distribution solution you might be using today. Greta uses webRTC to distribute data directly between concurrent users of a service or site, which means no servers are used to distribute the data. Use Greta by simply including the standard script or customize after your specific needs. All data distributed in Greta’s network is safely encrypted.

Greta always fallbacks to your current CDN or server solution if the algorithm estimates that is more appropriate for your end users – for example if someone is on a desert island or have a metered connection. Should something, against all odds, go wrong – the worst thing that can happen is that we fallback to your existing distribution solution.

If you want more information, check our documentation: [https://greta.io/documentation](https://greta.io/documentation)

#How to register

These examples will work regardless if you have a Greta account or not. However, signing up is free and you can then use Greta for your own page as well as get analytics from our real time dashboard. Get your Greta script here: [https://app.greta.io/signup](https://app.greta.io/signup)

#How to run the examples
First of all you need a web server running on your local machine, as some of the JS functions used are not allowed on file:// you will need to access the examples over http:// or https://

If you already have a web server running, just make sure to put the examples in the right directory or point the server to the right place.

If you do not have a web sever running yet, we have some quick ones you could use:

###Using python:
```
git clone https://github.com/gretaio/examples.git
cd examples
python -m SimpleHTTPServer
```
Go to [http://localhost:8000/](http://localhost:8000/)

###Using nodejs:
```
npm install -g http-server
git clone https://github.com/gretaio/examples.git
cd examples
http-server
```
Go to [http://localhost:8080/](http://localhost:8080/)

#Support

You can get in contact with us on [Slack](https://slack.greta.io) or send a [support ticket](https://greta.io/support) with any questions you have!
