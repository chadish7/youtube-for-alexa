- Start by heading to [the Alexa Developer Console](https://developer.amazon.com/alexa/console/ask)

- Sign in with your Amazon account.

- Click on Create skill

- Enter a name for your skill & make sure that Custom and Provision your own, are selected

- On the next screen select start from scratch and click the choose button.

- Scroll down and click on the Interfaces button.

- Enable the audio Interface, video Interface and the display Interface.

- Click the save Interfaces button.

- Look on the left for a button called JSON Editor, click it.

- Remove all text from the box.

- Open the [InteractionModel JSON](/InteractionModel_en.json)

- Copy all the text from here and paste it in the box.

- Click on save model then click build model.

- Now look for the endpoint page. (located on the left)

- Select AWS Lambda ARN and in the Default Region box enter your ARN 

- Leave the other boxes blank. click on save model then build model.

- Now navigate to the test page(at the top)

- Next to where it says Test is disabled for this skill. click on the dropdown menu and choose development.

- You now have a working skill just say Alexa launch YouTube.

If you like this project [consider donating](https://paypal.me/andrewstechshow)

if you have any issues please post them in the issues.
