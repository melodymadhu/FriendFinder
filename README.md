# FriendFinder - The most compatible to your taste.

A dating app developed using full stack - node, express, bootstrap, Jquery..deployed on heroku

This application captures User's name, URL of the User's Image, and answers to set of pre-defined questions.

Then it matches the users choice values for the questions against the other user's choices stored inside an array initialized at the time when the server program starts running. The array is initialized with one default profile.

Whichever already stored array entry produces least deviation with respect to the current user's choices..that array entry is retrieved and the corresponding User's Name and Image URL is shown in a Modal-PopUp.

If the user doesn't provide Name, ImageURL or do not answer any of the questions, then corresponding alerts are shown and the modal-popup is shown but informing no Friend could be found.

The very first user of this app..will be shown the default profile stored in the array. Subsequent users will be shown their closed matched friend per the logic explained above. 