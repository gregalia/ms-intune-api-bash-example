# Start Grabbing Intune Device Data from the MS Graph API

Before running this script, access must be provisioned via an 'app registration' in the Azure portal, which in turn requires a global admin to approve. More info [here](https://aka.ms/30DaysMSGraph).

Once the registration has been completed, put the `TENANT_ID`, `CLIENT_ID` and `CLIENT_SECRET` in the `.CONFIG` file and the script will `source` (import) them.

Also, in order to test all of this out beforehand, it's useful to know (I didn't) that you can't just sign up for an Azure trial. You need a _Microsoft 365_ license.

Happy Hacking!
