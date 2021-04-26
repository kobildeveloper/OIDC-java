# mIDentity Box OpenId Connect Java Examples

This repo contains Java example apps that demonstrate the various OpenId Connect flows

1. [Authorization Code Flow using Spring Security](spring-boot-app)

## What can I use these for
OpenId Connect is a great way to add user authentication to your application
where you are depending on another party to manage the user identities.

In this case mIDentity Box can manage the identity of your users making it
faster to get up and running.

## Single Sign On (SSO)
By implementing OpenId Connect via mIDentity Box you are creating a
session which can be used to single sign on from your custom app
into other apps that your users may have access to via the mIDentity Box portal

## MFA
If MFA is enabled for a user in mIDentity Box then they will be prompted to
enter a token during the authentication. mIDentity Box takes care of all of this
for you, making strong authentication much easier to implement in your app.

## Requirements
In order to run any of the examples you will need to create an OpenId Connect
app in mIDentity Admin portal.

### Mobile App
1. [Android app](https://play.google.com/store/apps/details?id=com.kobil.mIdentity.box)
2. [iOS App](https://apps.apple.com/us/app/midentity-box/id1534159545)

If you don't have a mIDentity Box account [you can sign up here](https://midentitybox.com/selfenrollment).
