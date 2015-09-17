<p align="center">
<a href="https://www.youtube.com/watch?v=PQaZqxVtln4
" target="_blank"><img src = "https://github.com/SAP/BUILD/blob/master/docs/images/BUILD_Logo_Light.png?raw=true" /></a>
<br />
Beta - work in Progress
</p>

# Overview of BUILD
BUILD  is an open-source, cloud-based, and social platform that enables users with no UI development knowledge to create fully interactive prototypes. Without writing a line of code, you can perform user research, design the UI, include realistic data, and share the prototypes with colleagues. Developers can use the code of the prototype as a jumpstart to quickly create the app.

<p align="center">
<a href="https://www.youtube.com/watch?v=PQaZqxVtln4
" target="_blank"><img src="https://github.com/SAP/BUILD/blob/data-model-samples/docs/images/image_youtube_email.png?raw=true" 
alt="To view the BUILD getting started click on the image..." width="640" height="360"/></a>
</p>

For a more detailed description of BUILD, see the [BUILD Overview](https://github.com/SAP/BUILD/wiki/BUILD-Overview).

# User Documentation
Check out the [BUILD Support Site](http://sap.github.io/BUILD_User_Assistance) for detailed help topics and video tutorials about using BUILD!

# Make a Contribution

So you want to contribute to BUILD? Good choice! There is lots of scope for contribution, and there's plenty to do! 
Popular contributions include bug reports, feature requests, and new features. [This document](https://github.com/SAP/BUILD/blob/master/Contributing.md) describes how to make contributions to any of these modules.

##Getting Started

###Prerequisites
- install [GIT](https://git-scm.com/downloads)
- install [npm.js](https://docs.npmjs.com/cli/install) - _*only version 1.4.28 is supported*_
- install [node.js](https://docs.npmjs.com/cli/install) -_*versions 10.33 and 10.38 are supported*_
- install [mongodb](https://www.mongodb.org/downloads#previous) -_*only version 2.6.x is supported*_
- Follow install for your OS @ https://github.com/TooTallNate/node-gyp/blob/master/README.md#installation


###Download / Clone

1. Clone [BUILD](https://github.com/SAP/BUILD) repo
    ```sh
    git clone https://github.com/SAP/BUILD.git
    ```

2. Install required node modules (dependencies) (note, you need to be in the BUILD/ folder within the repo):
    ```sh 
    npm install -g grunt-cli
    cd BUILD/BUILD/
    npm install
    ```
    
3. Initialize the database(Required just the first time):
   ```sh
    cd server
    node initSchema.js
    node setDefaultAccess.js
    cd ..
   ```
   
4. Start the BUILD application (for Dev):
    ```sh
     grunt serve
    ```

Go to [http://localhost:9000](http://localhost:9000) in Chrome browser and click Join

_If you're having a problem installing, you can create a bug or ask a question using the [BUILD Issue Tracker](https://github.com/SAP/BUILD/issues), contact contribute.build@sap.com or tweet our twitter account [buildwithbuild](https://twitter.com/buildwithbuild) and we will reach out to you._ 

# Modules in Build
**Foundation Modules**
+ [angular-sap-common-directives](https://github.com/sapbuild/angular-sap-common-directives)
+ [angular-sap-common-services](https://github.com/sapbuild/angular-sap-common-services)
+ [angular-sap-ui-elements](https://github.com/sapbuild/angular-sap-ui-elements)
+ [angular-sap-common-filters](https://github.com/sapbuild/Norman)
+ [node-sap-mongo-config](https://github.com/sapbuild/node-sap-mongo-config)
+ [node-sap-common](https://github.com/sapbuild/Norman)
+ [node-sap-app-server](https://github.com/sapbuild/node-sap-app-server)
+ [node-sap-mailer](https://github.com/sapbuild/node-sap-mailer)
+ [node-sap-secure-store](https://github.com/sapbuild/node-sap-secure-store)
+ [node-sap-upload](https://github.com/sapbuild/node-sap-upload)
+ [node-sap-mongo](https://github.com/sapbuild/node-sap-mongo)
+ [node-sap-promise](https://github.com/sapbuild/node-sap-promise)
+ [node-sap-logging](https://github.com/sapbuild/node-sap-logging)
+ [node-sap-upload](https://github.com/sapbuild/node-sap-upload)
+ [node-sap-mongo-config](https://github.com/sapbuild/node-sap-mongo-config)
+ [node-sap-build](https://github.com/sapbuild/node-sap-build)

**Build Modules**
+ [BUILD_PrototypeEditors](https://github.com/sapbuild/PrototypeEditors)
+ [BUILD](https://github.com/sapbuild/angular-sap-common-directives)
+ [BUILD_Projects](https://github.com/sapbuild/Projects)
+ [BUILD_UICatalogManager](https://github.com/sapbuild/UICatalogManager)
+ [BUILD_UserResearch](https://github.com/sapbuild/UserResearch)
+ [BUILD_UXRuleEngine](https://github.com/sapbuild/UXRuleEngine)
+ [BUILD_BusinessCatalogManager](https://github.com/sapbuild/BusinessCatalogManager)
+ [BUILD_Auth](https://github.com/sapbuild/Auth) 
+ [BUILD_Shell](https://github.com/sapbuild/Shell)
+ [BUILD_SharedThirdParties](https://github.com/sapbuild/SharedThirdParties)
+ [BUILD_Common](https://github.com/sapbuild/Common)
+ [BUILD_AngularUIGrid](https://github.com/sapbuild/NgUIGrid)
+ [BUILD_AngularUIGridTree](https://github.com/sapbuild/norman-angular-ui-tree)
+ [BUILD_AngularUIGridZip](https://github.com/sapbuild/AngularZip)
+ [BUILD_Html2Canvas](https://github.com/sapbuild/Html2Canvas)
+ [BUILD_KeyBoardEventPolyfill](https://github.com/sapbuild/norman-keyboard-event-polyfill)
+ [BUILD_D3Plugins](https://github.com/sapbuild/norman-d3-plugins)
+ [BUILD_jQuery](https://github.com/sapbuild/jquery-norman)

**Admin Modules**
+ [BUILD_AdminUsers](https://github.com/sapbuild/admin-users)
+ [BUILD_Admin](https://github.com/sapbuild/admin)
+ [BUILD_AdminAudit](https://github.wdf.sap.corp/UXD-BUILD-OPENSOURCE/BUILD_admin-audit)

# Licenses

This project is licensed under the Apache Software License, v. 2 except as noted otherwise in the [License file](https://github.com/SAP/BUILD/blob/master/LICENSE.txt).

_Please do not remove this license from cloned or forked versions of BUILD._

###Licenses for Contributors

+ [Individual Contribution License Agreement](https://github.com/SAP/BUILD/blob/master/docs/SAP%20License%20Agreements/SAP%2BIndividual%2BContributor%2BLicense%2BAgreement.pdf) 
+ [Corporate Contributor License Agreement](https://github.com/SAP/BUILD/blob/master/docs/SAP%20License%20Agreements/SAP%2BCorporate%2BContributor%2BLicense%2BAgreement.pdf) 

# Legal Notices

[View the legal notice about fonts used in Build](https://github.com/SAP/BUILD/wiki/Legal-Notice-About-Fonts).
