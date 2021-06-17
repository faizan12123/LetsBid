# LetsBid

Authors: Bakkr Alnaji, Faizan Hussain, Artin Mirzayans, Evan Johnson, Thanh Tran


List of features/services and Its Status:
Sign In Page With User Verification ~ Status: Completed
Functionality of Bidding Functionality ~ Status: Completed
Functionality of Auction Functionality ~ Status: Completed
User Interface and Design For Homepage ~ Status: Completed
User Interface and Design For Bidding Page ~ Status: Completed
User Interface and Design For Sign In ~ Status: Completed
Connect Project to Database ~ Status: Completed
Test Coverage for Front End Functionality ~ Status : 100% Completed
Test Coverage for Back End Bidding Functionality ~ Status: 76% In Progress
Test Coverage for Back End Auction Functionality ~ Status: 88% In Progress
Going Global ~ Status: In Progress
Security Captcha for Sign In Page ~ Status: Incomplete
Payment Method ~ Status: Incomplete


Instructions on How To Run:
Requirements to launch the project:
Install Visual Studio Code
Install Angular CLI
Install Intellij IDEA
Install Node JS

How To run Back End For Auctioning Functionality:
Open IntelliJ
Clone main branch named “main”
Go to main application and run the main

How to run Back End for Bidding Functionality:
Open IntelliJ
Clone main branch named “LetsBid-BiddingFunctionality-BE”
Go to main application and run the main

How to run Front end:
Open Visual Studio Code
Open Angular project
Clone branch called “LetsBid-Auction” in an angular project
In separate Angular Project clone branch called “LetsBid-Bidding”
Make sure you have npm installed, type in terminal “npm install”
Once installed, run “ng serve” in the terminal in both projects
Open the link given to you in terminalNOTE: The Back end for the auction, Bidding, and UI must be running at the same time.


Future Functional Requirements:
1.) Paypal payment acceptance:
A software program that we would like to implement in the future would be the Paypal checkout. This would allow users to purchase the 
items they bid for using Paypal. We plan to do this by integrating the PayPal API into our software.
2.) Apple payment acceptance:
A software program that we would like to implement in the future would be a Apple payment checkout. This will be implemented by 
integrating an apple payment API into our software. This will allow our buyers to check out items and purchase them using their Apple 
pay
3.) Notifications:
We would like to implement a notification center that pushes notifications to users on updates on their bids. It would notify them to let 
them know if they have been out-bid on an item, if they won the auction, and if they lost an auction. We would also like to notify sellers if 
a buyer has placed a bid on the item they are selling as well as providing updates on how much time they have left for their item to be up 
for sale before expiring.
4.) Messaging Center:
We would like to implement a messaging center within the website to allow users to message sellers so that they can easily ask them 
questions on any items for sale. This would also allow sellers to message their buyers incase there is any issues that have came up on 
the item for sale. As of right now we are only providing buyers and sellers each other’s email to contact each other, but this would bring 
more convenience to the users of the website.

Future Non-Functional Requirements:
1.) Security:
In the near future, we would have liked to implement captcha security for when users sign in, post items for sale, or even bid on items for 
sale. This would help prevent DDoS attacks on the website and further enhance the security of the website.
More security testing to ensure hackers can not access databases and pull out any secret user information that is not meant to be 
exposed to the public.
2.) Safety:
Contract for the buyer to agree on before posting an item to make sure they are actually selling the product as advertised. This protects 
the buyers and ensures that they will not be getting scammed and will receive the actual items they have sought out for.
Contract for the seller to sign when purchasing an item to let them know that there is no refund on the item they are purchasing. This will 
protect sellers from having to deal with users using their items and then returning them right after they are done using them. It also 
protects them from users breaking their items and then wanting to return them.
A pop-up asks the user if they are sure they are willing to bid the amount they input to ensure that no one is accidentally placing an 
incorrect amount for their bid.
Another contract for the sellers to ensure they are not selling illegal items and that they are following the rules of the website when 
posting an item for sale.
3.) Reliability:
Create an additional database to store user information. As of right now, we are using one database to store both user information and 
items for sale information. By adding an extra database for user information, the data will be stored in a more reliable way because if one 
database goes down, not all sources of information being stored will be affected.
4.) Quality:
Increase amounts of testing done so that all functions and code in the program have been adequately tested for bugs or resilience. This 
ensures that the website is running properly and that users have a seemless user experience


Future Software Design:
In our previous architecture. We only had one database. In the future, We plan to add an extra database which will store the 
user information such as the payments, first name, last name, and address. This will expand the versatility of our website.
