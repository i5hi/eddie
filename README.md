# eddie

an authorization service that presents challenges to your clients and authorizes access to your core services.

eddie does not perform any form of authentication and requires no use of personally identifiable data such as IP, email or phone number.

eddie aims to minimizing spam and abuse of your core services.

Supported challenges:

## hashcash

provides a message string and difficulty for a hashcash challenge. client must expend computational resources to solve the challenge. This disincentivizes bots.

## sliderpuzzle 

provides 2 images and y-coordinate starting point. client must find the correct x coordinate to prove they are a human. (requires pairing with an appropriate client side library)
