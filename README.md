# manoa-tckts.github.io

- [Homepage](https://manoa-tckts.github.io/) - Homepage detailing current project status.

**The following are possible functionalities of this application:**

* Roles: There are three roles in the system: 
* Normal - buyer/seller. Can make posts for buying and selling tickets
* Promoter - someone who is an official distributer of tickets for an event or company, This status can be authenticated by Admins(see below) to confirm the legitimacy of promoters. Promoters can provide the amount of tickets that they currently have available to them.
* Admin - Administrators are special users who have the ability to monitor the behavior of users in the system, ban users who violate the conditions for use of the system, and create new categories and other functionality. Admins can also appoint users as promoters by checking the legitimacy of promoters. 
* Categories: The categories can be the different types of events that have tickets available. UH campus center has a list of upcoming events which can be used as a basis of possible events. 
* Values: Ticket sellers can provide face values for the tickets, how much they are willing to sell the ticket for, if prices are negotiable, etc. An advanced implementation can be the percentage of discount that the seller is selling the ticket when compared to online or store prices 
* A face value pertains to what it is being sold at at online stores or official stores. These may also include service fees. Sellers of tickets usually sell their tickets for prices lower than face value. A feature can be implemented such that a percentage of the seller's price when compared to the face value price is displayed. 
* Notifications: By default, communication occurs via UH email, but students can also elect to receive information via text message. To do this, they must specify both their mobile phone number as well as their provider (i.e. Verizon, AT&T). Most providers have an “SMS gateway” mechanism that will enable your app to generate a text message to them. 
* Alerts: Users can set up alerts, for example if they are looking for a ticket for a specific event. Then they are automatically notified when that item is listed for sale.
* Photos: Sellers of tickets should provide photos to ensure the legitimacy of the tickets. 
* Upon first login, all users must agree to Terms of Use before they obtain access to the system.
* Profiles: Users have profiles which provide optional information such as further means of contact: instagram, facebook, twitter, email, phone. 

**Mockup page ideas**

Some possible mockup pages include:

* Public landing page
* Login page
* User home page
* Admin home page
* User Profile page
* Events page
* List Item page
* Create item page
* Notify admin page
* Promoters page

**Use case ideas**

* New user goes to landing page, logs in, gets home page, sets up profile.
* Admin goes to landing page, logs in, gets home page, edits site.
* User goes to landing page, logs in, looks for tickets, sets up notification.
* User logs in, lists tickets to sell.
* User tries to buy tickets.
* User and admin interact to ban inappropriate usage.

**Additional functionalities for future versions**

* Implement proximity locations so that users can find people near them to make transactions. 
* Users can write reviews for other users on things such as legitimacy, how well the transaction went, if they violated any terms and if they should be banned, etc. 
* Use something similar to Uber where there are notifications as to where the buyer/seller is in relation to each other
* Messaging system for users to communicate with each other
* Previews of the events such as sound clips or movie clips

