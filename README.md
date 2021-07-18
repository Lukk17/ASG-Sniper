# ASG Sniper  

Target practice.  

## Importing project  

### Android Studio/ IDEA Intellij:  
Import whole project (ASG_sniper) and in File > Project Structure... delete all modules.  
Then import whole `ASG_sniper` without any gradle and only "Flutter" module.  
Without any Android modules (it will ask for Android modules twice).  
Mark `lib` as source file and `test` as test.  

### Visual Studio Code:  
Add whole project folder (ASG_sniper) to workspace.  
Then in platform.io import NodeMCU part - it will be visible as extra folder next to `ASG_sniper`.  
So it will be double - one inside `ASG_sniper` folder and another in workspace root folder.  
This way you can see `.gitignore` and other project files as well as build Flutter app.  


### Compiling Flutter Web:  
`flutter build web`  
> A release build uses dart2js (instead of the development compiler) to produce a single JavaScript file main.dart.js. You can create a release build using release mode (flutter run --release) or by using flutter build web. This populates a build/web directory with built files, including an assets directory, which need to be served together.
 You can also include --web-renderer html or --web-renderer canvaskit to select between the HTML or CanvasKit renderers, respectively.