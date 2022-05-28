// page 4
menu details of item selected
{Post}> localhost:9700/menuItem
{body}> [3,6,2]


> PlaceOrder
{post} > localhost:9700/placeOrder
{body} > 

{
	"name": "vinod",
	"email": "vinod@gmail.com",
	"address": "Hno 406,thane",
	"phone": 986754750,
	"cost": 800,
	"menuItem": [5,3,1],
	"status": "Pending"
}

// page5

> see all order place
{get} > localhost:9700/viewOrder

>Get order on basis of emailId
>>>>> localhost:9700/viewOrder?email=vinod@gmail.com
