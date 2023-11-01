![Capsula Link](https://github.com/mavrinpn/Capsula-Link-App/raw/main/Capsula-Link-iPhone-1.png)

![Capsula Link](https://github.com/mavrinpn/Capsula-Link-App/raw/main/Capsula-Link-iPhone-2.png)

# About

Svetofon is a mobile native application developed with a fully custom design for iOS using Swift language.

A hybrid format is used for user authentication: primary authentication is performed by entering a PIN code sent to the user's email. Further work is carried out in completely offline mode. At the same time, user data is backed up on the server, if necessary, authentication takes place through a previously saved token.

Bluetooth LE 4.0 protocol is used to interface with an external device (smart simulator). A command system and a communication protocol between the application and the smart trainer have been developed.

As part of the training statistics collection system, a module for exporting user training history to xlsx format has been developed.
To create unique training complexes, a proprietary protocol for storing and playing exercises in json format has been developed. At the same time, the user has the opportunity to create their own exercises through the configurator, set the necessary parameters and export/import the received training complexes.

## AppStore

- App published at [App Store](https://apps.apple.com/ru/app/светофон/id1597336312)

## Other Features

- Adaptive UI
- SQLite
- PDF and XLSX export

## Backend

- The server part is deployed on a VDS on Node.js (Express, Mongoose, Passport) and is proxied via Nginx.
- MongoDB is used as the database.
- The server part includes an API for the application - authentication functions, an analytics module, and a backup management module.

## Supports iPad

![Capsula Link](https://github.com/mavrinpn/Capsula-Link-App/raw/main/Capsula-Link-iPad-1.png)

![Capsula Link](https://github.com/mavrinpn/Capsula-Link-App/raw/main/Capsula-Link-iPad-2.png)


My LinkedIn: [Pavel Mavrin](https://www.linkedin.com/in/pavel-mavrin-developer/)
