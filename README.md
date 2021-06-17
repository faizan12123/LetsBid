# LetsBid <br />

Authors: Bakkr Alnaji, Faizan Hussain, Artin Mirzayans, Evan Johnson, Thanh Tran <br />


List of features/services and Its Status:<br />
Sign In Page With User Verification ~ Status: Completed <br />
Functionality of Bidding Functionality ~ Status: Completed <br />
Functionality of Auction Functionality ~ Status: Completed <br />
User Interface and Design For Homepage ~ Status: Completed <br />
User Interface and Design For Bidding Page ~ Status: Completed <br />
User Interface and Design For Sign In ~ Status: Completed <br />
Connect Project to Database ~ Status: Completed <br />
Test Coverage for Front End Functionality ~ Status : 100% Completed <br />
Test Coverage for Back End Bidding Functionality ~ Status: 76% In Progress <br />
Test Coverage for Back End Auction Functionality ~ Status: 88% In Progress <br />
Going Global ~ Status: In Progress <br />
Security Captcha for Sign In Page ~ Status: Incomplete <br />
Payment Method ~ Status: Incomplete <br />


Instructions on How To Run: <br />
Requirements to launch the project: <br />
Install Visual Studio Code <br />
Install Angular CLI <br />
Install Intellij IDEA <br />
Install Node JS <br />

How To run Back End For Auctioning Functionality: <br />
Open IntelliJ <br />
Clone main branch named “main” <br />
Go to main application and run the main <br />

How to run Back End for Bidding Functionality: <br />
Open IntelliJ <br />
Clone main branch named “LetsBid-BiddingFunctionality-BE” <br />
Go to main application and run the main <br />

How to run Front end: <br />
Open Visual Studio Code <br />
Open Angular project <br />
Clone branch called “LetsBid-Auction” in an angular project <br />
In separate Angular Project clone branch called “LetsBid-Bidding” <br />
Make sure you have npm installed, type in terminal “npm install” <br />
Once installed, run “ng serve” in the terminal in both projects <br />
Open the link given to you in terminalNOTE: The Back end for the auction, Bidding, and UI must be running at the same time. <br />


Future Functional Requirements: <br />
1.) Paypal payment acceptance:<br />
A software program that we would like to implement in the future would be the Paypal checkout. This would allow users to purchase the 
items they bid for using Paypal. We plan to do this by integrating the PayPal API into our software. <br />
2.) Apple payment acceptance: <br />
A software program that we would like to implement in the future would be a Apple payment checkout. This will be implemented by 
integrating an apple payment API into our software. This will allow our buyers to check out items and purchase them using their Apple 
pay <br />
3.) Notifications: <br />
We would like to implement a notification center that pushes notifications to users on updates on their bids. It would notify them to let 
them know if they have been out-bid on an item, if they won the auction, and if they lost an auction. We would also like to notify sellers if 
a buyer has placed a bid on the item they are selling as well as providing updates on how much time they have left for their item to be up 
for sale before expiring. <br />
4.) Messaging Center: <br />
We would like to implement a messaging center within the website to allow users to message sellers so that they can easily ask them 
questions on any items for sale. This would also allow sellers to message their buyers incase there is any issues that have came up on 
the item for sale. As of right now we are only providing buyers and sellers each other’s email to contact each other, but this would bring 
more convenience to the users of the website. <br />

Future Non-Functional Requirements: <br />
1.) Security: <br />
In the near future, we would have liked to implement captcha security for when users sign in, post items for sale, or even bid on items for 
sale. This would help prevent DDoS attacks on the website and further enhance the security of the website.
More security testing to ensure hackers can not access databases and pull out any secret user information that is not meant to be 
exposed to the public. <br />
2.) Safety: <br />
Contract for the buyer to agree on before posting an item to make sure they are actually selling the product as advertised. This protects 
the buyers and ensures that they will not be getting scammed and will receive the actual items they have sought out for.
Contract for the seller to sign when purchasing an item to let them know that there is no refund on the item they are purchasing. This will 
protect sellers from having to deal with users using their items and then returning them right after they are done using them. It also 
protects them from users breaking their items and then wanting to return them. <br />
A pop-up asks the user if they are sure they are willing to bid the amount they input to ensure that no one is accidentally placing an 
incorrect amount for their bid. <br />
Another contract for the sellers to ensure they are not selling illegal items and that they are following the rules of the website when 
posting an item for sale. <br />
3.) Reliability: <br />
Create an additional database to store user information. As of right now, we are using one database to store both user information and 
items for sale information. By adding an extra database for user information, the data will be stored in a more reliable way because if one 
database goes down, not all sources of information being stored will be affected. <br />
4.) Quality: <br />
Increase amounts of testing done so that all functions and code in the program have been adequately tested for bugs or resilience. This 
ensures that the website is running properly and that users have a seemless user experience <br />


Future Software Design: <br />
In our previous architecture. We only had one database. In the future, We plan to add an extra database which will store the  
user information such as the payments, first name, last name, and address. This will expand the versatility of our website. <br />
