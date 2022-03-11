# EEE3088F_2022_Templating

A repo that demonstrates a useful git repo configuration for archiving a KiCAD project for EEE3088F 2022.

This repo will be updated periodically throughout the course

# How to use this repo
1. Clone it recursively:
```bash
git clone https://gitlab.com/r4space/eee3088f_2022_templating.git --recursive
```

2. Explore it, look around, read all the readmes, try opening the example kicad project in the PCB folder

3. Keep an eye on this repo, and pull down updates throughout the course as new content is added and/or explained

4. Make your own repo from scratch and model it on this one.  **Do not** just directly clone this repo.  While often the perfect way to replicate useful information, in this case the goal is for you to gain experience making your own repositories, making your own decisions about how they should be structured, and fixing bugs as you encounter them.  This repo is given as a guide and you are expected to use it as a model - if you have no reason to chose another approach, follow this examples for minimal problems.

# Things to note about this repo
1. It has a README.md file.  Every git repository, public or private, must have a good README explaining to anyone who comes to it:
* What is here?
* Who is the target audience?
* How to install the contents?
* How to use the contents?
* How to get help useing the contents?
* What the future plans for the repo and what is its status? (Eg is the project in beta/under development/archived/moved/etc).  And if active, is there a plan for which features will be added when?
* How to contribute back to the repo if desired?
* Under what conditions/license may the contents be used?
Finally, rather have a README that is too long than too short.  But if it's getting long, consider using other forms and locations for further documentation.

2. Its Structure: It is often useful to include information about how the repo has been structured in the toplevel README.  This repo has the following subfolders, which provide a useful common structure for custom electronics projects:
    * PCB: The KiCAD Project, Schematics & Layout and Project Libraries
    * Firmware: Any software developed for the hardware or instructions on where to find relevant sofware in cases where it makes more sense to have this in its own dedicated repo make this a git submodule
    * Docs: Project documentation and component datasheets
    * Production: The gerber files, BOM, Budget, or anything required by the fabrication houses
    * Simulation: Any simulation files (eg SPICE) or design stage generated results (Eg matlab or excel) 
    * CAD: Any 3D models or mechanical designs for enclosures or support

2. The [.gitignore](./.gitignore) file is worth looking at copying for your own project repo for the course.

3. This repo includes a submodule.  This is why when you cloned it you needed to include the flag '--recursive' as part of the clone command.  The purpose of this submodule is explained [here](./PCB/PCB_readme.md)

# License
[Creative Commons Attribution 4.0 International license](https://choosealicense.com/licenses/cc-by-4.0/)
