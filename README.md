## Update Transaction Day to Current Date (FinDock for Fundraising)
<a href="https://githubsfdeploy.herokuapp.com?owner=ashley-findock&repo=virtual-terminal-person-account&ref=main">
  <img alt="Deploy to Salesforce"
       src="https://raw.githubusercontent.com/afawcett/githubsfdeploy/master/deploy.png">
</a>


## A quick description for what this repo contains:

Screenflow to be used on Person Accounts that creates Gift Transaction & processes credit card payment using the FinDock Virtual Terminal

## Requirements
The prerequisites to deploy this repository are:

Fundraising enabled and configured in your Salesforce environment

FinDock for Fundraising activated along with either Stripe or Worldpay PSP connectors

## Installation

Simply install and activate the flow. You can then include it on your Person Account page layout or trigger it an Action on the Person Account object. (When adding to a Page Layout, make sure to tick the checkbox to Pass the record ID into the variable recordId.)

Go to the "Take Payment" Screen element to configure your Processor, Target and update other settings as desired

To deploy the flow to your Salesforce environment, you can:
- use `sfdx`.
- Click the "Deploy to Salesforce" button at the top of this README. Once redirected, log in to your Salesforce environment by clicking "Login to Salesforce" in the top-right corner of the page.
- any other deployment method you prefer.

## Contributing

When contributing to this repository, please first discuss the change you wish to make via an issue or any other method with FinDock before making a change.

## Support

FinDock Labs is a non-supported group in FinDock that releases applications. Despite the name, assistance for any of these applications is not provided by FinDock Support because they are not officially supported features. For a list of these apps, visit the FinDock Labs account on Github. 

## License

This project is licensed under the MIT License - see the [LICENSE](/LICENSE) file for details
