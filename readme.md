##Meteor Cookbook  

Hi.  Welcome to the Meteor Cookbook; a FAQ and tutorial culled and currated from over 12 months of emails and discussions from the [meteor] google group and my experiences rolling out packages and apps.  These documents are intended for the intermediate user learning Meteor, who is accustomed to a) object-oriented frameworks and languages, such as Java and C#, and b) relational databases and data structures derived from SQL table schemas.  The focus is on helping the user grow accustomed to functional programming using document oriented databases.


##Index  

- [General Advice](https://github.com/awatson1978/meteor-cookbook/blob/master/cookbook/general-advice.md)  
- Language References
  - [Glossary](https://github.com/awatson1978/meteor-cookbook/blob/master/cookbook/terminology.md)  
  - [Syntax](https://github.com/awatson1978/meteor-cookbook/blob/master/cookbook/syntax.md)  
  - [Grammar](https://github.com/awatson1978/meteor-cookbook/blob/master/cookbook/grammar.md)  
  - [Language](https://github.com/awatson1978/meteor-cookbook/blob/master/cookbook/reserved.keywords.md)  
- [Installation](https://github.com/awatson1978/meteor-cookbook/blob/master/cookbook/installation.md)  
  - [Quickstart](https://github.com/awatson1978/meteor-cookbook/blob/master/cookbook/quickstart.md)  
  - [Development Tools](https://github.com/awatson1978/meteor-cookbook/blob/master/cookbook/devtools.md)
  - [Development Tools](https://github.com/awatson1978/meteor-cookbook/blob/master/cookbook/development-tools.md)    
  - - [Webstorm IDE](https://github.com/awatson1978/meteor-cookbook/blob/master/cookbook/webstorm.md)
  - [Test Driven Development](https://github.com/awatson1978/meteor-cookbook/blob/master/cookbook/test-driven-development.md)  
- Site Mechanics
    - [File Structure](https://github.com/awatson1978/meteor-cookbook/blob/master/cookbook/filestructure.md) 
    - [Dependencies](https://github.com/awatson1978/meteor-cookbook/blob/master/cookbook/dependencies.md)  
    - [App Structure](https://github.com/awatson1978/meteor-cookbook/blob/master/cookbook/appstructure.md) 
    - [Event Cycle](https://github.com/awatson1978/meteor-cookbook/blob/master/cookbook/event-cycle.md) 
    - [Namespacing](https://github.com/awatson1978/meteor-cookbook/blob/master/cookbook/namespacing.md) 
    - [Packages](https://github.com/awatson1978/meteor-cookbook/blob/master/cookbook/packages.md)  
    - [Configuration](https://github.com/awatson1978/meteor-cookbook/blob/master/cookbook/configuration.md)  
- Open Systems Interconnection Model
  - Physical Layer (Client Side)
    - [Keybindings](https://github.com/awatson1978/meteor-cookbook/blob/master/cookbook/keybinding.md)  
    - [Console Logging](https://github.com/awatson1978/meteor-cookbook/blob/master/cookbook/logging.md)  
    - [Mutlitouch](https://github.com/awatson1978/meteor-cookbook/blob/master/cookbook/multitouch.md)  
  - Data-Link Layer
    - WebKit Browsers
      - [File IO](https://github.com/awatson1978/meteor-cookbook/blob/master/cookbook/fileio.md)  
      - [Video IO](https://github.com/awatson1978/meteor-cookbook/blob/master/cookbook/video.md)  
  - Network Layer
    - [Environments](https://github.com/awatson1978/meteor-cookbook/blob/master/cookbook/environments.md)  
      - [Hosting Providers](https://github.com/awatson1978/meteor-cookbook/blob/master/cookbook/hosting-providers.md) 
      - [Production](https://github.com/awatson1978/meteor-cookbook/blob/master/cookbook/environments-production.md)  
      - [Environment Detection](https://github.com/awatson1978/meteor-cookbook/blob/master/cookbook/environment-detection.md)  
    - [Peer to Peer](https://github.com/awatson1978/meteor-cookbook/blob/master/cookbook/peer-to-peer.md)  
  - Transport Layer
    - [Scaling](https://github.com/awatson1978/meteor-cookbook/blob/master/cookbook/scaling.md)  
    - Data Distribution Protocol
    - Clustering
    - Websockets
  - [Data Layer](https://github.com/awatson1978/meteor-cookbook/blob/master/cookbook/datalayer.md)
    - [Collections](https://github.com/awatson1978/meteor-cookbook/blob/master/cookbook/collections.md)
      - [User Accounts](https://github.com/awatson1978/meteor-cookbook/blob/master/cookbook/accounts.md)  
      - [Aggregation](https://github.com/awatson1978/meteor-cookbook/blob/master/cookbook/aggregation.md)  
    - [Schema Migrations](https://github.com/awatson1978/meteor-cookbook/blob/master/cookbook/schema.changes.md)     
    - [Data Validation](https://github.com/awatson1978/meteor-cookbook/blob/master/cookbook/validation.md)  
    - [Database Management](https://github.com/awatson1978/meteor-cookbook/blob/master/cookbook/database-management.md)
  - Presentation Layer
    - [Templates](https://github.com/awatson1978/meteor-cookbook/blob/master/cookbook/templates.md)  
    - [Images](https://github.com/awatson1978/meteor-cookbook/blob/master/cookbook/images.md)  
    - [Animations](https://github.com/awatson1978/meteor-cookbook/blob/master/cookbook/animations.md)  
  - Application Layer
    - [Routing](https://github.com/EventedMind/iron-router)  
    - Pages
      - [Single Page Design](https://github.com/awatson1978/meteor-cookbook/blob/master/cookbook/pages.single.md)
      - [Multi-Page Design](https://github.com/awatson1978/meteor-cookbook/blob/master/cookbook/pages.multi.md)  
      - [Wizard Dialog](https://github.com/awatson1978/meteor-cookbook/blob/master/cookbook/workflow.md)  
      - Multi-Page with Routing
      - Page Transitions
      - [Modal Dialogs](https://github.com/awatson1978/meteor-cookbook/blob/master/cookbook/pages.dialogs.md)  
      - Errors & Alerts
    - Application Programming Interfaces
      - [Integration of 3rd party APIs](https://github.com/awatson1978/meteor-cookbook/blob/master/cookbook/api-wrappers.md)  
      - Exposing a REST API
    - User Interface Patterns
      - Page Resize
      - Page Freeze
      - Drag and Drop
- [Error Referece](https://github.com/awatson1978/meteor-cookbook/blob/master/cookbook/errors.md)  
- [Recipes](https://github.com/awatson1978/meteor-cookbook/blob/master/cookbook/recipes.md)  
  - Blog
  - [Tagging](https://github.com/awatson1978/meteor-cookbook/blob/master/cookbook/tagging.md)    
- [Breaking Changes](https://github.com/awatson1978/meteor-cookbook/blob/master/cookbook/breaking-news.md)  

**In Progress**  
- [Async & Futures](https://gist.github.com/possibilities/3443021)  
- [Database Migrations](https://github.com/awatson1978/meteor-cookbook/blob/master/cookbook/database-migrations.md)  
- [Data Shaping](https://github.com/awatson1978/meteor-cookbook/blob/master/cookbook/data-shaping.md)




##Applet Demos
Links to live versions of the examples in this cookbook.  

[GroupThink](http://groupthink.meteor.com/)  
[Fonts & Calligraph](http://fonts.meteor.com/)    
[Dictionary](http://dictionary.meteor.com/)  
[Collabtionary](http://collabtionary.meteor.com/)  
[Hubble - CRUD & Datasets](http://hubble.meteor.com/)  
[Acceptance Testing](http://safety-harness.meteor.com/)  
[Creating Forms](http://forms-kitchen-sink.meteor.com/)  
[Understanding The Rendering Event Loop](http://reactive-rendering-tests.meteor.com/)  
[Mobile Devices - iOS in Particular](https://github.com/awatson1978/cordova-phonegap)  


## Support
Found this package to be useful?  Consider tipping the package maintainer for their time!  

[![Support via Gittip](https://raw.github.com/gittip/www.gittip.com/master/www/assets/gittip.png)](https://www.gittip.com/awatson1978/)  

