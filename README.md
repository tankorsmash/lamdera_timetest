# To Reproduce

* run `lambera live --port <portnum>`
* browser to `localhost:<portnum>`
* open dev console
* notice 'ticking' every few seconds, along with NoOpToFrontend from Backend, and to Frontend
* refresh page, logs no longer show up for 'ticking' nor NoOpToFrontend
* click 'Reset Backend'
* receive one 'ticking' message from the init command, but no back and forth NoOpToFrontend logs
* stop server
* `lamdera reset`
* start server, `lamdera live --port <portnum>`
* refresh page
* 'ticking' every few seconds
