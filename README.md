

## Intro & Motivation

**LinkWarden is a self-hosted, open-source bookmark + archive manager to collect, and save websites for offline use.**

The objective is to have a self-hosted place to keep useful links in one place, and since useful links can go away (see the inevitability of [Link Rot](https://www.howtogeek.com/786227/what-is-link-rot-and-how-does-it-threaten-the-web/)), LinkWarden also saves a copy of the link as screenshot and PDF.

## Features

* Auto-capture a screenshot and PDF from each website.

* Dark/Light mode support.

* Responsive design.

* Search, filter and sorting functionality.



### Using Docker Compose V2 (Recommended)

1. Make sure docker is installed.

2. Clone this repository.

3. Head to the main folder and run `docker compose up -d`.

The app will be deployed on port 3000.

### Configuration
To configure the app create a `.env` file (in the main folder), here are the available variables:
```
CLIENT_PORT=2500           # Default: 3000
API_PORT=5700              # Default: 5500
API_ADDRESS=192.168.1.14   # Default: localhost
```

> If you want to use this app across the network set `API_ADDRESS` as the computer (where LinkWarden is hosted) IP address.



