# PRIP

# Background:-
• There is no easy-to-use website to act as a bridge between representatives and general public.

• People are not acquainted with the participation of their representatives and the representatives are not entirely acquainted with the needs of the people.

• Filing petitions regarding issues of the region and popular petitions being known by public and representatives on the internet is not readily available. Offline petitions are hard to file and even harder to track.

Our website provides a platform for the people and representatives to overcome the aforementioned problems. We have developed a website to bridge the gap between people and their representatives, where people can get to know in detail about the proposals and talks in the Parliament and also get to know about the participation of their representatives in the same.

# Features:-
• Provision to display all the proposals, discussions and debates in the legislative houses, divided constituency wise.
• Option for general public to vote on them so that the representatives can get to know the in-demand topics(on the basis of votes).
• Option for public to get to know about the participation of their representatives in the legislative houses which will help them make an informed decision in the future. 
• People will be allowed to file petitions and popular ones(based on votes) will be sent to the constituency's leader's office which can be discussed in the house. 
• Public can vote for petitions and also comment anonymously. 
• There is a provision to track the status of your provision. You may get to know if your petition is filed, if it has become popular or if the mail has been sent to the leader regarding the issue if the demand is high enough.

# Tech-Stack:-
• MongoDB, Express.js, Node.js, React.js, Bootstrap, Fetch.

# Instructions to use:-
• Pre Requisites:- Node, NPM, Yarn, MongoDB
• Clone the repository and run ```npm install``` in both the React folder as well as the Server folder. This should download all the required dependencies onto your local systsem.
• Go to the server folder and create a new folder named "mongodb" and a subfolder named "data". Move to the "mongodb" folder and run the command ```mongod --dbpath=data --bind_ip 127.0.0.1```
• Go to the Server folder and run ```npm start```. This should start your server on localhost:3000.
• Go to the React folder and run ```yarn start```. Allow the application to run on another port. This should start your client side.
• For nodemailer to run, go to "mailer.js" in the server folder and update the email ID and password of the account you want to send mails from.
• You may add leaders, states and constituencies for testing purposes from the './leaders' and './states' endpoints on the server.
