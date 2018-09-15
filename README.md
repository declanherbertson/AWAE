
AWAE (an Anonymous Way to Attend Events) is a proof of concept anonymous ticket service developed for the Bluzelle 2018 Decentralized Database Hackathon

What is it?

AWAE is a service built of the bluzelle decentralized database that allows event tickets be created and purchased completely anonymously

How does it work?

AWAE allows an Establisment to create an event with details including cost, and generates two keys, a public key, and a private key. the public key is shared to those wishing to purchase a ticket and when entered into the website, will pull the details for the event. Then it allows for an anonymous payment through a cypto currency. Once the payment is completed, AWAE will generate a order confirmation number for the ticket purchaser which will be accesible to the Establishment through their private key. The Establishments private key allows the creator to manage the event and access and modify the orders.

What is working in this concept?

AWAE in its proof of concept form allows an Establishment to create an event, generating both public and private keys. it also lets the user find and purchase a ticket for an event (the payment process is out of the scope of the project and is replaced by a purhase button). The creators private key does give access to the orders, but the management page was not completed in the time frame.

How do I run it?

It used a locally run test swarm, or node network to act as the database. documentation for deploying the local node network can be found on the swarmDB github. The test swarm was deployed on a macbook using docker. For the javascript to be able to include the neccesary requires in html, it must be compiled using a service called browserify. the cli command to do so is browserify input.js -o output.js where you reference the output javascript.

As this was a hackathon completed in 24 hours, no formal design parameters where followed and in many cases the logic and implementation follows worst pratices.

This was a team effort.

This project was part of a team effort. I wrote the javascript and interfaced with the database api. This project was created in 24 hours and does not follow proper design or good standards whatsoever.
