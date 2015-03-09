
#Request Skeleton Definition
######################################

`{
	tag: 1 , //integer, optional 
	cmd: "String: , //required 
	body:{} //optional
}`

#Response Skeleton Definition
######################################
`{
	tag: String, //integer, optional 
	evt: String, 
	body: {} //JsObject , optional
}`


## Objects

| Object name  | Object description |
| ------------- | ------------- |
| member | catreloaded member  |
| Message  | message to be sent   |

## Events

| Event name  | Event description|
| ------------- | ------------- |
| join-channel  | when member join new channel  |
| join-group | when member join new group  |
