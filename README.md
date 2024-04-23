# Bucket-List Site
This project is created using flask
BucketList using Flask

In this Project :
------>I made a post request to save a new item
> API Creation(POST)
👉 1. Request Information: URL= /bucket , HTTP Method = POST
2. Client (ajax request) → Server (flask: save item in database) : bucket
3. Server (flask: send success message) → Client (ajax response) : the message will be something like, “item
saved successfully!”

 creating and using the GET api - reading the list of items from the API (Read→ GET)
 > API Creation(GET)
 👉 1. Request info: URL= /bucket , HTTP Method = GET
2. client(ajax) → server(flask) : (the client only needs to send the data, no additional data is required by the server)
3. server(flask) → client(ajax) : after the client receives the data from the server, it will display that data on the
page

[Bucket List] - Creating the POST API and request (marking a bucket list item as
complete)
1) Creating and using the API - Bucket List Completion API (Update→ POST)
👉 1. Request Information: URL= /bucket/done , HTTP Method = POST
2. Client (ajax) → Server (flask) : num (bucket list item number)
3. Server (flask) → Client (ajax) : message to the user (Bucket list item completed!)

About the delete button : When the delete logic is finished, an automatic page load is triggered and the most recent list of list items is shown on the
page
