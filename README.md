CTFDev Environment Setup
-------
Runs all components of the app concurrently (Doesn't use Docker-Compose)
### GitModules Setup
*Running for the first time:*<br>
1. Clone this repo: `git clone --recursive https://github.com/ctfguide-tech/CTFDev.git`
2. Update sub-directories: `git submodule update`<br>
*Check for new git updates in subdirectories:*<br>
1. `git submodule update --init --recursive`<br>

### Running with proxy server
1. First have FireBase and Mongo instances created. You can create a [Mongo Instance](https://github.com/ctfguide-tech/LocalMongo) locally.
2. Run `npm run dev` to run client and api concurrently (You must set up env vars in the respective directories)

### Running in Docker-Compose
This option isn't available yet.