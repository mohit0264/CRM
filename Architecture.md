![platform](https://cloud.githubusercontent.com/assets/22348863/19458348/1eddb1a0-94e9-11e6-82ab-3a175b88a86b.png)

# Understanding the Salesforce Architecture - Force.com:
Data Centric
- Multitenant architecture: An application model in which all users and apps share a single, common infrastructure and code base.
- Metadata-driven development model : An app development model that allows apps to be defined as declarative “blueprints,” with no code required. Data models, objects, forms, workflows, and more are defined by metadata.
- API Access: Several application programming interfaces (APIs) provide direct access to all data stored in Force.com from virtually any programming language and platform.
  1. The SOAP API and REST API integrate your organization’s data with other applications
  2. The RESTful Bulk API (also available using Data Loader) loads or deletes large numbers of records
  3. The Metadata API manages customizations in your organization (also available using the Force.com Migration Tool)
  4. The Chatter REST API accesses Chatter feeds and social data
  5. The Streaming API provides notifications reflecting data changes in your organization
- Apex: The world’s first on-demand programming language, which runs in the cloud on the Force.com platform servers.
- Visualforce: A framework for creating feature-rich user interfaces for apps in the cloud.
- Mobile Access: With Salesforce mobile apps, you can access custom apps built using the Force.com platform’s point-and-click development tools. Your users can access those apps on their mobile devices—and you don’t have to learn any mobile programming languages.
- AppExchange directory: A Web directory where hundreds of Force.com apps are available to Salesforce customers to review, demo, comment upon, and/or install. Developers can submit their apps for listing on the AppExchange directory if they want to share them with the community.

![apex_architecture](https://cloud.githubusercontent.com/assets/22348863/19458606/bdf01ebc-94ea-11e6-9972-9bf20709545b.png)

# SFDC MVC Pattern contains three modules:
![mvc](https://cloud.githubusercontent.com/assets/22348863/19458916/f1fa566c-94ec-11e6-87b4-c4ae70ee246f.jpg)

1. Model: What schema and data does salesforce uses to represent complete system. In salesforce, SObjects are the model as every entity is mapped to SObject.Objects, fields and relationships come under model layer
2. View: How the schema and data is represented. Tabs, visualforce Pages, Page Layouts come under view layer.
3. Controller: How the interface actions. Controllers are use to perform actions whenever user interact visualforce. Workflow, Apex classes and triggers come under controller.

