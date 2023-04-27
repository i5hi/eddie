# eddie

`a spam reduction authorization service`

eddie offers challenges to clients for reducing spam that reaches your core services.

Supported challenges:

## hashcash

provides a message string and difficulty for a hashcash challenge. client must expend computational resources to solve the challenge. This disincentivizes bots.

## sliderpuzzle 

provides 2 images and y-coordinate starting point. client must find the correct x coordinate to prove they are a human. (requires pairing with an appropriate client side library)

