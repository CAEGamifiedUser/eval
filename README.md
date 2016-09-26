eval
---

In this repository, there is a ToDoList application.
To gamify the application, we use Gamifierjs library here :
```
https://github.com/CAE-Gamified/Gamifierjs
```

- I already added those library in ToDoList application in gamification folder.
- You only need to edit applicationScript.js in ToDoList/js and gamifier.js in ToDoList/gamification folder

Edit the files
---
- Edit File gamifier.js

change $APPLICATION_ID$ with application ID of gamification

- Edit File applicationScript.js
add
```
Gamifier.triggerAction("{action ID}");
```
in wherever it is needed to trigger action

- Create a new space in ROLE
```
http://gaudi.informatik.rwth-aachen.de:8073/{whatever the name is}
```
- Add the gamified widget
```
https://caegamifieduser.github.io/eval/ToDoList/gamification/widget.xml
```
- Add the visualization widget
```
https://rwth-acis.github.io/Gamification-Visualization-Frontend/widget.xml
```
- Finish
