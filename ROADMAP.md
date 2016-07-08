##Roadmap for Meteor Maker Site

###Goals:
* Provide a home for the meteor-maker generator tool and associated docs
* Create an accessible meteor resource library for developing Meteor apps using latest best-practices
* The meteor-maker tool will encode a lot of the recommendations outlined in the resource center

###Features
* Simple CMS that reads `markdown` files from a remote repo/server
* Navigable resource center, backed by the meteor-maker project

###Development Story
The project will be a meteor app (CMS). Most of the work will be in translating the design from the Frames UI kit into an appealing front-end, backed by the Foundation framework. The route I intend to take is to translate the Frame UIs into React components (topbar, header, etc) for use not only in this project, but for other, more functional apps. I see this as both being an investment in future projects, and also a good way to get the basics of React down.

The backend will (to start) simply consist of a basic posts based CMS and publication tool. Posts will most likely be `markdown` files with some meta-data associated.
