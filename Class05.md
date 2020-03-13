node-js-getting-started[master]$ heroku logs --tail
2020-03-13T16:16:25.884055+00:00 app[api]: Initial release by user jpchato@gmail.com
2020-03-13T16:16:25.884055+00:00 app[api]: Release v1 created by user jpchato@gmail.com
2020-03-13T16:16:25.993589+00:00 app[api]: Enable Logplex by user jpchato@gmail.com
2020-03-13T16:16:25.993589+00:00 app[api]: Release v2 created by user jpchato@gmail.com
2020-03-13T16:17:28.000000+00:00 app[api]: Build started by user jpchato@gmail.com
2020-03-13T16:17:47.166799+00:00 app[api]: Scaled to web@1:Free by user jpchato@gmail.com
2020-03-13T16:17:47.144210+00:00 app[api]: Release v3 created by user jpchato@gmail.com
2020-03-13T16:17:47.144210+00:00 app[api]: Deploy b9a3b998 by user jpchato@gmail.com
2020-03-13T16:17:48.000000+00:00 app[api]: Build succeeded
2020-03-13T16:17:49.363316+00:00 heroku[web.1]: Starting process with command `node index.js`
2020-03-13T16:17:51.739734+00:00 app[web.1]: Listening on 44324
2020-03-13T16:17:52.527120+00:00 heroku[web.1]: State changed from starting to up
2020-03-13T16:19:43.828914+00:00 heroku[router]: at=info method=GET path="/" host=agile-depths-01953.herokuapp.com request_id=8c5d70e9-fbdf-4378-81b6-3ba1373f4c89 fwd="50.243.104.203" dyno=web.1 connect=0ms service=21ms status=200 bytes=7074 protocol=https
2020-03-13T16:19:44.018715+00:00 heroku[router]: at=info method=GET path="/stylesheets/main.css" host=agile-depths-01953.herokuapp.com request_id=bca254b8-b031-474b-a359-8451f44951f2 fwd="50.243.104.203" dyno=web.1 connect=2ms service=10ms status=200 bytes=908 protocol=https
2020-03-13T16:19:44.011063+00:00 heroku[router]: at=info method=GET path="/lang-logo.png" host=agile-depths-01953.herokuapp.com request_id=ffee3a03-77ee-43d1-9ba6-cad3e7858e08 fwd="50.243.104.203" dyno=web.1 connect=0ms service=8ms status=200 bytes=2567 protocol=https
2020-03-13T16:19:44.389075+00:00 heroku[router]: at=info method=GET path="/favicon.ico" host=agile-depths-01953.herokuapp.com request_id=8a13701d-0f82-4e0a-9090-3d4768244daf fwd="50.243.104.203" dyno=web.1 connect=0ms service=3ms status=404 bytes=394 protocol=https