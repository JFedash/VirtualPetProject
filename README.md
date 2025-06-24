# Pixel Pets:
## What does our software do?
Our team has created a fun and interactive game that teaches responsibility and other important life skills to players of all ages. You can choose from multiple characters, each with unique stats and abilities. We’ve included save game functionality, engaging music, and parental controls to make sure kids can enjoy the game responsibly.

## Folder Structure:
- **`group71.wiki/`**  
  Repository for all project documentation. This serves as the central wiki containing technical references, planning notes, and team documentation.

- **`group71/`**  
  Main development repository. This contains all the source code, assets, and files related to the implementation of the project.

- **`VideoExample/`**  
  A showcase folder containing a video demonstration of the rewritten version of the game for presentation and evaluation purposes.

## Required libraries:
* Jackson-core 2.18.3
* Jackson-annotations 2.18.3
* Jackson-databind 2.18.3

## How to build
1. Create necessary directories
mkdir -p build/classes
mkdir -p build/classes/my_package/assets/data
2. Compile Java files
javac -d build/classes -cp "lib/*:build/classes" src/my_package/*.java
3. Copy resources (JSON files from your assets)
cp -r src/my_package/assets/data/* build/classes/my_package/assets/data/

## How to use
1. make sure you are in the root directory (/VirtualPetProject)
2. run the following java -cp "lib/*:build/classes:src:." my_package.app
3. if on windows run java -cp "lib/*;build/classes;src:." my_package.app
4. Full tutorial on the main page

## Pins
* Parental Controls password: 1234
