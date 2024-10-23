Build your own 3D renderer - Java
=================================
Quick Start
-----------

```sh
git clone https://github.com/mohitutkarsh/Ray-tracer.git
cd Ray-tracer

# Build the raytracer
gradle build

# Run it, outputting to a file called "test.png" in the current directory
java -jar build/libs/Raytracer-1.0-SNAPSHOT.jar test.png
```

Scene Definition
----------------

While each project typically asks the reader to add new data to the scene definition, the number of classes to add in Java would drown out the main changes needed to implement a particular project. For that reason, all the data model classes and the scene definition have been set up in a single commit at the beginning of the repository history.

Tagged milestones
-----------------

Each commit of the project implements one of the projects in the workshop. If you wish to implement one of the projects yourself, you can check out the `before-project-N` tag, where `N` is the project number. This will put you in a state just prior to the implementation of that project, with all previous projects implemented:

```sh
# Prepare to implement Project 4
git checkout before-project-4
```
