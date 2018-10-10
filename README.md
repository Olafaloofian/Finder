## Finder is a project built by web developers Michael Kerr, Eric Rivera, and Sibyl Pomeroy.

#### Finder's purpose is to provide a simple, Tinder-like swiping interface for matching job applicants and recuiters together. It allows users to find each other based on industry and position, then opens a chat channel so they can discuss the implications of potential jobs.

***

### The following technologies are showcased in the code of the project:
- JavaScript
- React
- Node
- PostgresQL
- CSS
- React Context API
- Enzyme
- Jest
- Chai
- Cypress
- Pusher ChatKit
- Google Maps API
- MaterialUI
- Nodemailer
- Redis

***

#### Home view (no user logged in)
<img src='./media/homenouser.png' alt='Home View No User' width='300'>
All features of Finder require a user to be logged in through their LinkedIn account.

#### Logged in profile view
<img src='./media/profilemain.png' alt='Profile Main' width='300'>
After logging in using Auth0, users can access their profile page.

#### Profile edit view
<img src='./media/profileedit.png' alt='Profile Edit' width='300'>
Here, the user can enter and update their profile information - which is then saved in a database.

#### Job map
<img src='./media/jobmap.png' alt='Job Map' width='300'>
This map populates with the approximate locations of nearby users that are the opposite role (recruiter/applicant) as the logged in user (Google Maps API).

#### User settings
<img src='./media/usersettings.png' alt='User Settings' width='300'>
This is where a user can change his or her recruiter/applicant status, or temporarily deactivate their account if they've found what they are looking for on Finder for now. Additionally, a user may completely delete their account from the database or change their email address.

#### Home view
<img src='./media/home.png' alt='Home' width='300'>
Returning home, the user now sees potential matches within their industry. If they are an applicant, recruiters' cards will show up here. If the are a recruiter, applicants' cards will appear.

#### Match success
<img src='./media/matchfound.png' alt='Match Found' width='300'>
In the event of a match (both users have swiped right on each other), an animation will appear and an email sent to each user notifying them (Nodemailer).

#### Contacts
<img src='./media/chat.png' alt='Contacts' width='300'>
All matches a user makes adds the match to this contacts screen.

#### Chat
<img src='./media/chatting.png' alt='Chatting' width='300'>
By tapping on one of the contacts, a user can open a live chat window to speak to them directly (Pusher ChatKit).




