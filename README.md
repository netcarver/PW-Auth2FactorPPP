# PPP 2-Factor Authentication For ProcessWire

This module requires the [CryptoPPP library module](https://raw.github.com/netcarver/PW-CryptoPPP/master/CryptoPPP.module) to be installed and then uses it to add 2-factor authentication to ProcessWire. On installation and activation you will see an additional 'Token' field in the login form and you will have to enter the right one-time-code into this field to be able to login. These tokens can either be printed out in advance and carried on your person or they can be delivered by email.

## Email Delivery

To setup email delivery simply make sure that every user who will use the system has a valid email address. Upon the first failed login, the required token will be emailed to the user's email address and thereafter they will be able to login. 

## Printing The PPP One-Time-Pad Cards.

If you prefer to print the codes in a handy credit-card sized format then...

1. Go to your profile screen
2. Expand the "PPP Initialisation Vector" field
3. Hit the "Show Token Cards" button to open a new browser window with the next 3 useful cards
4. Use your browser's print option to print these out
5. Trim them to size and store
