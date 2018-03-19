

This project start with the excellent starter kit:

1. git clone git@github.com:codediodeio/angular-firestarter.git aCodingBatLeaderBoard

Idea -- Let people login and provide their CodingBat.com done url.  e.g. 

1. http://codingbat.com/done?user=payne@mattpayne.org&tag=6764324312

Then every X hours, a cron job will scan those pages and populate the 
firestore database.   When someone views the page they will be able 
to see the leader-board amongst the participants.


