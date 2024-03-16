# WanderLust

## Phase 1 Part A (Basic Setup):

### Install Basic Node.js Packages:
- express
- ejs
- mongoose
- method-override

### Folder Structure:
- models
  - listing.js (Mongoose model for storing listing details)
- init
  - data.js (Contains some data for initialization of the database)
  - index.js (Initializes the database by storing data from "data.js")
- views
  - listing
    - index.ejs (Index Route)
    - show.ejs (Show Route)
    - new.ejs (New Route)
    - edit.ejs (Edit Route)
- app.js (Entry Point)
- package.json and package-lock.json (npm initialization files)

### Goal Achieved at the End of Phase:
- Able to perform basic CRUD operations

    