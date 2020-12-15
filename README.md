# OpenTrivia
Small multiplayer quiz demo using express and socket.io in the backend and React for the UI. [Click Here](https://opentrivia.herokuapp.com/) to view the live demo. 

# To-Do

- Ajout timer
- Changement clic sur réponse à toggle (attente timer)
- db question

# Amelioration

- multiple types question (audio, video, qcm, question libre)
- interface utilisateur ajout question
- l'admin choisi les réponses (ou alors case à cocher dans option game pour faire à la vox populi ?)

### How to use locally:

* Clone the repository and run the following command to download all dependencies.
```
 npm install
```
* Now open a terminal run the following command if you just want to start the server for development.
```
npm run watch
```
Use the following commands if you want to manually build from src to test for production.
```
npm run build:prod or npm run build:dev followed by npm run serve
```
* Open the brower and navigate to http://localhost:3000 for the main screen and point all other devices to http://your_internal_ip:3000 and follow onscreen instructions.

