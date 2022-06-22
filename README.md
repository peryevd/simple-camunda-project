###Install:
 - Download initialize project from:
 ```https://start.camunda.com/ ```
 - Open with IntelliJ IDEA
 - Add decorator ```@EnableProcessApplication``` to ```src/main/java/com/example/workflow/Application.java```
 - Create folder ```META-INF``` in ```src/main/resources```
 - Create empty file ```processes.xml``` in ```META-INF```
 - Add folder ```static/forms``` in ```src/main/resources```

### Run:
  - Build project

### Usage:
  - html files for forms put into ```src/main/resources/static/forms```, and import in modeler as ```embedded:app:forms/YourForm.html```
  - camunda forms put into ```src/main/resources/static/forms```, and import in modeler as ```camunda-forms:/forms/YouForm.form```