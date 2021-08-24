# virtual-agent-public

Visit the [wiki](https://github.com/Avaya-CXI/virtual-agent-public/wiki) for more information.

## Getting started.

### Get a CPaaS Number from the [CPaaS Console](https://cloud.zang.io/v2/dashboard).
* Click on `Numbers` in the left column.
* Click on `Buy Numbers` in the left column.
* Search for numbers with any critia you choose (you can leave the search field blank to get first available).
* Choose a number and click `BUY` then `Confirm Purchase`
* Click `Configure` to finish setting up your new number in the CPaaS Console.
* Give your new number a friendly name (optional), such as *Virtual Agent Demo*
* Configure the WebLinks for voice and SMS to use **Virtual Agent** by setting 
  - **Voice Request URL** `https://virtuagent.apps.avayacloud.com/voice/` 
  - **SMS Request URL** to `https://virtualagent.apps.avayacloud.com/cpaas-sms`

### Configure your new number on Virtual Agent
* Go to [Virtual Agent](https://virtualagent.apps.avayacloud.com)
* Sign in with your *@avaya* account with SSO
* Go to the `Account` tab.
* Click `Add Configuration`
* Copy your new number into the `Avaya Cloud Number` field. Example `+15551231234`
  - Choose the language and voice you want or leave it to the default English and male voice. 
  - Dialogflow configuration will shown later, do not worry about it for now.

### Start Building with your new Virtual Agent 
* Go to the `Menu` tab.
