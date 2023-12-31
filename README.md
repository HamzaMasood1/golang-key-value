# golang-key-value
A key-value store is really just a dictionary. Give it a key, get back a value. You can add new keys, remove keys, or update values. Viola, you have created a NoSQL database! But you can take it a step further and offer it as a web API, so that all your future web apps can utilize your database service.

I really like this project because it is really simple to create the basic "database". You can start by using the dictionary data structure that comes with whatever programming language you're using and slap a web API on top of it. But like all these ideas, there is a lot more that can be added: optimizations for high performance, security and multiple users, atomic transactions, data types, batch operations, persistance, failure recovery, and the ability to run it across multiple servers. Soon enough you'll have a billion dollar product like Redis or Amazon DynamoDB.

Seriously, fire up your code editor and use your favorite language to try this one. I did it with both Go and Racket to get a feel of the differences. It was quite enlightening. The performance was good enough with my Go version on small tests right out of the box.

Further reading:

Key-value database (Wikipedia)
B-tree data structure (Wikipedia)
Atomicity (Wikipedia)
How I built a key value store in Go (web)
Badger: Fast key-value DB in Go (GitHub)
If you want to dive deeper with databases: Database Design for Mere Mortals (Amazon)
