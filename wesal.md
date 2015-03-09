#Wesal Protocol Definition
This is the  definition of wesal protocol ......................

##Connection initialization
at first we should intialize the connection via websockets ....

####Example 
`wss://127.0.0.1:8080/websocket`

### Sending first message 
when someone connects to the server the server should not accept ANY message except the "initialize" command otherwise, it's a malicious client that doesn't understand our protocol, we should fail and close the websocket connection immediately.

####Request
`{tag: 1, "cmd": "initialize", accesstoken: "ab12cd"}`
