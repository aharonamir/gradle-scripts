## gradle-scripts
common gradle tasks
# How to use:
- Set dockerImage before adding the script, e.g:
  project.ext.set("dockerImage", [full-image-name] like "hello/world")
- add the script file :
  apply from: 'https://raw.githubusercontent.com/aharonamir/gradle-scripts/master/build.gradle'

Enjoy
