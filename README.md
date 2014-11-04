CandyBot
========

This is a modification of [SnackBot](https://github.com/electricimp/examples/tree/master/SnackBot) that dispenses candy in response to SMS messages rather than via a website. The repository isn't actually a fork as I don't need the entire electricimp/examples repo.

The code was written in around 15 minutes which is why there is more of SnackBot hanging around than there really should be.

Instructions for the hardware are available at [Instructables](http://www.instructables.com/id/SnackBot-The-Internet-Connected-Candy-Machine/). The SMS integration is achieved by creating an account at [Twilio](http://www.twilio.com) and routing incoming SMS requests to the Electric Imp agent URL.