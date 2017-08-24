# How to build a Whatsapp-clone using Ionic 2 CLI and Meteor

Facing your next mobile app project, you want to choose the best solutions to start fast while also solutions that will stay relevant when your project grows and scales.

The two companies that took the concept of creating a platform with a complete set of tools for your development needs and not just another framework to the furthest are `Meteor` and `Ionic`.

**Ionic** - Ionic has become one of the most popular solutions to develop hybrid mobile apps fast across different platform.

The `Ionic` platform includes solutions for prototyping, build, testing, deploying apps, a market of starter apps, plugins and themes, CLI integration and push notifications service. (Further writing by an Ionic person)

**Meteor** - But your app needs a full stack solution.

`Meteor` has become the only open source JavaScript platform that supply the complete set of solutions you need to create a real time mobile connected apps.

The `Meteor` platform is reliable, fast and easy to develop and deploy and it will also handle all the complexities of your app when it grows and scales with time.

### So which one should you choose?

Your best option is to use them both!

Both companies made the steps needed to support each other:

- [Meteor now has official support for Angular with it's 3rd party libraries!](http://info.meteor.com/blog/official-angular-support-with-angular-meteor-1.0.0?__hstc=219992390.d5a12b08bbf681831d288088f2c1b55f.1476117688291.1482430169317.1482433129287.88&__hssc=219992390.2.1482433129287&__hsfp=2355228760)
- [Ionic added official support for Meteor's packaging system](https://github.com/driftyco/ionic/pull/3133)

So now we can use the strengthnesses of each of those platform combined to create the ultimate stack for your mobile apps.

In this tutorial, we will create a full `WhatsApp` clone using Angular and `Ionic` framework as a client platform and `Meteor`'s reactive collections and authentication packages as our back-end.

## How to install


0. [Install Node](https://nodejs.org/en/download/)

1. [Install Meteor](https://www.meteor.com/install)

2. [Install Ionic](https://ionicframework.com/docs/intro/installation/)

3. Install meteor client bundler

```
$ sudo npm install -g meteor-client-bundler
```

4. Clone repository and install dependencies
```
$ git clone https://github.com/Urigo/Ionic2CLI-Meteor-WhatsApp.git
$ cd Ionic2CLI-Meteor-WhatsApp/
$ meteor npm install sharp
$ npm install
$ npm run meteor-client:bundle
$ npm run api
```

5. Run app
```
$ ionic serve
```

[{]: <helper> (navStep ref="https://angular-meteor.com/tutorials/whatsapp2/ionic/setup")

| [Begin Tutorial >](https://angular-meteor.com/tutorials/whatsapp2/ionic/setup) |
|----------------------:|

[}]: #

