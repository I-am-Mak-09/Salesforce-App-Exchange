

#  AppExchange App Strategy
## App Type
### What Is an ISVforce App?
If you want your app to extend Sales or Service Cloud, build an ISVforce app. You can sell ISVforce apps only to existing Salesforce customers. These apps are typically designed to augment Sales Cloud or Service Cloud business functions.
[ISVforce Guide](https://developer.salesforce.com/docs/atlas.en-us.packagingGuide.meta/packagingGuide/packaging_intro.htm?_ga=2.41603298.1191589124.1681705446-847556882.1679280956)
### What Is an OEM Embedded App?
If your app doesn’t rely on Sales Cloud or Service Cloud functionality, you want to build an OEM Embedded app.

 OEM Embedded app, you can make three types of user licenses available to your customers: 
 - Lightning Platform
 - Customer Community
 - Customer Community Plus.

### ISVforce Vs  OEM Embedded App
|         |ISVforce app|OEM Embedded app|
|---------|------------|----------------|
|Audience|Existing Salesforce customers|Net-new customers/Existing Salesforce customers|
|Source of user licenses|Purchased from Salesforce|Embedded in application/From Existing Salesforce|
|License type around which app is built|Depends on solution and targeted customers. Sales and Service Cloud are most common.|Lightning Platform, Customer Community (optional), Customer Community Plus (optional)|
|AppExchange Application licenses|Provided by partner|Provided by partner|

## Salesforce Edition
Editions are tiered, with each edition building on the previous one. Going up a tier increases the features available and raises the limits on certain features.
![Salesforce Editions](https://res.cloudinary.com/hy4kyit2a/f_auto,fl_lossy,q_70/learn/modules/isv_plan/isv_plan_editions/images/0b119c126d24df9a792dfe14876bde9a_appex-app-strategy-u-2-1-editions.png)

- **Essentials (E)** The edition for businesses with five or fewer users. Functionality is minimal.
- **Professional Edition (PE)** Mid-size customers use PE. It has everything a customer needs for CRM and no limit on user licenses. It doesn’t include all the bells and whistles, but it does includes easy-to-use customization, integration, and administration tools to facilitate small to mid-size deployments.
- **Enterprise Edition (EE)** EE is our most popular edition. It includes all core tools and technologies, and meets the needs of large and complex businesses. In addition to all the functionality available in Professional Edition, it includes advanced customization and administration tools to support large-scale deployments.
- **Unlimited Edition (UE)** UE is like EE on steroids. Large enterprises purchase these editions. In addition to all the functionality available in EE, UE includes Premier Support, increased storage limits, and other features.
- [Editions Comparison Chart](https://www.salesforce.com/editions-pricing/sales-and-service-cloud/?_ga=2.242413634.1191589124.1681705446-847556882.1679280956&_gl=1*lxvhzx*_ga*ODQ3NTU2ODgyLjE2NzkyODA5NTY.*_ga_H6M98GGB18*MTY4MTcxMzQzNS42Ny4xLjE2ODE3MTM0MzcuMC4wLjA.)

![](https://res.cloudinary.com/hy4kyit2a/f_auto,fl_lossy,q_70/learn/modules/isv_plan/isv_plan_editions/images/1a49b3692b4d103b268bef23ae3c087e_2-a-3080-db-da-26-4-f-80-a-8-dc-eb-84492-c-3174.png)

## Tools to Build Your App
### Connect Salesforce to External Systems
- [API](https://help.salesforce.com/s/articleView?id=sf.integrate_what_is_api.htm&type=5)
- [Outbound Messaging](https://developer.salesforce.com/docs/atlas.en-us.api.meta/api/sforce_api_om_outboundmessaging.htm?_ga=2.242736322.1191589124.1681705446-847556882.1679280956)
- [Apex Callouts](https://developer.salesforce.com/docs/atlas.en-us.apexcode.meta/apexcode/apex_callouts.htm?_ga=2.245945284.1191589124.1681705446-847556882.1679280956)
- [Platform Events](https://trailhead.salesforce.com/content/learn/modules/platform_events_basics)
- Salesforce Connect
- [Heroku Connect](https://www.heroku.com/connect)
- [Canvas](https://developer.salesforce.com/docs/atlas.en-us.216.0.platform_connect.meta/platform_connect/canvas_framework_intro.htm?_ga=2.209375314.1191589124.1681705446-847556882.1679280956) 

|The technologies|	What are they used for?|	Our two cents|
|---------------|--------------------------|------------------|
|Declarative tools|	Configuring and building your app	|Use as much as possible!|
|Apex, Lightning Components, and Visualforce	|Configuring and building your app |When declarative is not enough, bring in programmatic.|
|The APIs and other integration tools|	Integration between Salesforce and external systems	|Pick the option that most closely fits your needs.|
|Chatter	|Collaboration	|It’s a selling point!|
|Communities|	Collaboration with customers, partners, and employees|	Easily extend the reach of your app to a larger audience.|
|Salesforce mobile app, Lightning Components, Salesforce Mobile SDK|	Making your app mobile ready	|Businesses love mobile.|
### Plan Your Application

- Who comprises your target audience?
- What is your business strategy?
- Which Salesforce editions will you support?
- Which license type do you want to use?
- Is your staff familiar with the Salesforce platform?
- What is your strategy for ensuring that your offering is secure?

## Resources 
- [5 Steps to Build Your First AppExchange App](https://www.youtube.com/watch?v=fAuBGdfLB-o)
-  [Help Docs](https://help.salesforce.com/s/articleView?id=sf.overview_limits_general.htm&type=5)
- [Execution Governors and Limits](https://developer.salesforce.com/docs/atlas.en-us.apexcode.meta/apexcode/apex_gov_limits.htm?_ga=2.237706176.1191589124.1681705446-847556882.1679280956)
