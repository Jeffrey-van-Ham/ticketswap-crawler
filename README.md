# Ticketswap-Crawler
ORIGINAL CREDITS TO: ducdigital

Do you want to go to an amazing festival but the tickets are sold out?
Are you tired of checking TicketSwap every minute (or even every few seconds) for a new ticket?

The TicketSwap Crawler does exactly this for you (and it never gets tired)...

This smart bot opens your default browser window as soon as there is a new ticket available.

Note: The bot only opens the page with the available ticket, and you have to reserve the ticket yourself!

# How to use

- Install node.js
- Get the required modules/packages.
- Run `node app.js`
- Optional: Set up a macro to reserve the ticket.
- Enjoy your event!

# Settings:

The most important change from the original script, is that this bot runs only one instance at the time, in order to avoid multiple calls (be kind to TicketSwap servers :) and to avoid getting a captcha check. I found that checking 2 every seconds works fine.

- CHECK_INTERVAL: Time used to check for new tickets.
- FOUND_INTERVAL: Little pause when a ticket is found (to give time to the macro to reserve the ticket).
- ROBOT_INTERVAL: Time to sleep/wait when captcha is needed (as it gets disabled after a while).
- ERROR_INTERVAL: Time to sleep/wait when there's an error.
- URLMAX_TIMEOUT: Maximum time used for web requests (in order to avoid pending/stuck requests).
- HOST: ie. 'https://www.ticketswap.nl' you can change this for .com, .de, etc.
- EVENT_URL = You can get this URL from the page of the event that you want to go.
*Times are in seconds* 

# Contribution:

First of all thank the original author: 'ducdigital'

Improve the code as you want!

SHARE!
