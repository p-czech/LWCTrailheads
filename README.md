# LWC Trailheads

This repo is developed in package development model. 
We are using playground as our DevHub and we are creating scratch orgs to develope changes.
All necessary commands can be found in: https://developer.salesforce.com/docs/atlas.en-us.sfdx_dev.meta/sfdx_dev/sfdx_dev_intro.htm

In order to pass the trailhead tasks, you need to convert the files using sfdx and deploy to you DevHub.
1. Create package: sfdx force:source:convert -r sourceFolder -d packageName
2. Deploy to devhub: sfdx force:mdapi:deploy -d packageName -u userNameOrAlias -w 5 

Using "-w 5" we wait 5 min to make sure we catch all deployment errors (some configuration may differ between Scratch orgs and DevHub preventing the deployment)


Links to trailheads:
1. Lightning Web Components Basics:
    https://trailhead.salesforce.com/en/content/learn/modules/lightning-web-components-basics?trail_id=build-lightning-web-components
    on master


