# Rocket Chat Flash Briefing
Flash Briefing Skill - Powered By Rocket.Chat

***

# Let's Get Started

Deploy your Flash briefing skill in minutes using Rocket chat and broadcast messages on both channel and skill in realtime.

# Setup

### Pre-requisites

* Node.js (> v8.10)
* Register for an [Amazon Developer Account](https://developer.amazon.com/)
* Rocket Chat Server updated to Release 1.2.0-rc.0 or later.

### Enabling Anonymous Read

* Go to **Server** -> **Three Dot Menu** -> **Administration** -> **Accounts** , and Set **Allow Anonymous Read** to **True**.

**Note:** Requires Admin Access.

### Creating Broadcast Channel

* On Server Homepage click on **Create New** -> **Channel**

* Set **Private Channel** -> **Public Channel** and Enable **Broadcast Channel**.

* Then give your **Channel Name**, and click on **Create**.

### Deploying Code

* **env Variables:**

  * **PORT** : Enter The Port number you want server to run on.
  
  * **CHANNEL_NAME** : Enter the name of the broadcasting channel we created earlier. Make sure its in lower case with no spaces.

  * **SERVER_URL** : Enter your current Rocket.Chat server url here. Ex- https://your.sever.chat

* After App is deployed we will be using **Server URL** in the next step.

### Creating Flash Briefing Skill

* Go [Alexa Developer Console](https://developer.amazon.com/alexa/console/ask).

* Click on **Create Skill**, give **Skill name** , **Default language** and choose **Flash Briefing** model then click on **Create Skill**.

* Write **Custom Error Message**, then click on **Add new feed**. Fill details as per you requirement.

* Choose **Content type** as **Text**.

* In **Feed**, paste the **Server URL**.

* Upload Photo and hit **Add**.

* Click on **Save** and that should complete the complete the process.

# TODOs

Need community help in the following:

* add a conversation flow to allow an admin to "publish the briefing" daily using the VUI
* add support for audio content for more personal flash breifing delivery
