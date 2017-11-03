This page covers how to create and run a demo Salesforce instance.

1. Sign up for a Free Salesforce Developer Edition Account
2. Load Demo Data
3. Update the Demo Phone Numbers
4. Install the Web Widget

# Sign up for a Free Salesforce Developer Edition Account

Go to the URL below and sign up for a free Salesforce Developer account:

[https://developer.salesforce.com/signup](https://developer.salesforce.com/signup)

# Load Demo Data

Load the Game of Thrones test data here:

[github.com/grokify/gameofthrones/examples/salesforce](https://github.com/grokify/gameofthrones/tree/master/examples/salesforce)

# Update the Demo Phone Numbers

Go to the "Jon Snow" contact and change the phone number to a non-RingCentral number, e.g. your PSTN phone number or Google Voice number.

# Install the Web Widget

Follow the instructions to install the demo which covers:

* Create a Call Center and add users
* Add the Softphone to your Salesforce app
* Add the Apex helper class
* Add the Visualforce page
* Navigate to the the Salesforce App and bring up RingCentral

# Run the Demos

* Click-to-Dial
* Inbound Screen-Pop
* Automatic Call Logging
* Additional Screen-Pops (Google, LinkedIn)

## Click-to-Dial

After installing the Web Widget, all phone numbers should be clickable and will bring up RingCentral.

## Inbound Screen-Pop

Navigate to a webpage other than the Jon Snow contact page. Call the RingCentral number you used to log into the RingCentral Web Widget.

## Automatic Call Logging

After the call, if you wait a few moments and refresh the Jon Snow contact page, you should see the call log entry under tasks.

## Additional Screen-Pops (Google, LinkedIn)

To show these, go to the Visualforce page and uncomment the `window.open` lines for Google and LinkedIn.
