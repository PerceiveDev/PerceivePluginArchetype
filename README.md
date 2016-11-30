# PerceivePluginArchetype
A Maven archetype for creating Bukkit plugins. This is the template which Perceive memebers should be using.

## Installation
Download this repository, navigate to it in your command prompt / terminal and run:

    mvn install
   
## Usage
To create a project, use the following command (filling in the fields as necessary):

    mvn archetype:generate \
      -DarchetypeGroupId=com.perceivedev \
      -DarchetypeArtifactId=mvn-archetype-perceive-plugin \
      -DarchetypeVersion=1.0.0 \
      -DgroupId="com.perceivedev" \
      -DartifactId="somePlugin" \
      -Dversion="1.0.0" \
      -Dname="SomePlugin" \
      -Ddescription="It's an awesome plugin!"
      
The above command already has the fields set up so the plugin package would be `com.perceivedev.somePlugin`, the display name would be `SomePlugin`, the version would be `1.0.0`, and the description is `It's an awesome plugin!`.

Alternatively, you could always download [PerceiveProject](https://www.github.com/PerceiveDev/PerceiveProject) which is a near clone of this, except that you would manually have to rename files and fill in the fields of the `pom.xml` and `plugin.yml`. It's meant as a sort of backup, so that if you can't get this to work, you can still use the project template.

_**Note: There will be a better command-line tool for creating projects as soon as Rayzr can figure out how to make it work on Windows as well as Unix-based systems.**_
