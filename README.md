# PizzaWithFriends
## An App by Marcus, Michael, and Kapil
### The Vision of Luke Juusola

#### Objective:

Search through phone/Facebook contacts every 5 minutes and check if the contact has Domino's Pizza on the way

#### Steps:

1. Access contacts and locally store them as a dictionary (name, phone number)
2. Iterate through these phone numbers and search phone number on https://www.dominos.com/en/pages/tracker/#/track/order/
3. In the app, display a table of contacts with who is getting pizza and who is not (sorted by who is getting pizza).
   Also, check the contacts once a minute with a refresh option.
   Outside the app, check every 5 minutes and send a push notification
   (potentially add an option to only push notifications if store is within a 25 mile radius).

#### Permissions:
- Access contacts
- Push notifications
- Access Web
