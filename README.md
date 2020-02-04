# Parcel Bootstrap Starter
Starter setup for [Parcel.js](https://parceljs.org/) with Bootstrap (SASS).

This starter offers a quick modular setup of directories/structure and dependencies for getting started with your project while utilzing Parcel.js.

# Getting Started
1. Click on **Use this template** button above the file list.
2. On the next page, type a name for your new repository, and an optional description.
3. Clone your newly created repo locally.
4. Run `npm install` to install dependencies.
5. ...
6. Profit?

# Commands
* `npm install` - Install dependencies.
* `npm start` - Run Parcel.
* `npm run watch` - Start Parcel watch.
* `npm run build` - Build. **Note:** Runs `rm -rf dist` before to reset the dist folder.

# Structure
Following structure has been set up:
```bash
/dist                                                 # Built files are exported to /dist
/src                                                  # Source files
  /styles                                             # Directory for CSS/SCSS files
    _variables.scss                                   # Define variables here
    _bootstrap.scss                                   # Imports Bootstrap includes
    _custom.scss                                      # Your custom styles here
    main.scss                                         # Imports all above files
  /scripts                                            # Directory for JS scripts
    main.js                                           # Placeholder JS file
  index.html                                          # Index page
```
