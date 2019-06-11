# Step 2: connect to Firestore

We start to build a simple webpage which lists all messages stored in `messages` collection.
Navigate to [Firebase console](https://console.firebase.google.com/) and create a database in Firebase with Testing mode.
Once the database is created, create a collection named `messages` and create some documents under the collection.
Each collection should have `name (string)`, `text (string)`, and `timestamp (timestamp)` fields.
Values can be random.

After editing, spin the local development server by running `firebase serve -p 8080` and navigate to the preview
by accessing `http://localhost:8080`.
You should see the texts from the saved messages on the screen.
