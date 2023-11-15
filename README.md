# ProfessionalSkills
Homework
Using Github to cooporate with others
Version controls, local and online, my branches and others branches
Used CMake to build a system for testing
Tested the gray-scott-sim model (type, len, value)
Using Github's Actions to contineous intergrate

/////////////////
Trival Process:

## gitbash
cd d:
cd Learning/ProfessionalSkills/test 
git clone https://github.com/scicomp-durham/gray-scott-sim.git
mkdir frankrepo
cd frankrepo
## copy 'gs.cpp' to 'frankrepo'
git status
git add gs.cpp
git commit -m 'First commit'
git remote add origin git@github.com:FrankFang99/ProfessionalSkills.git 
git push -u origin master

## Windows PowerShell
mkdir my_project
cd my_project
## copy 'gtest.cc' to 'my_project'
## useful link: https://google.github.io/googletest/quickstart-cmake.html

cmake -S . -B build
cmake --build build
cd build 
ctest

## git bash
git add gstest.cc
git add CMakeLists.txt
git commit -m "Second commit" gstest.cc CMakeLists.txt
git remote -v
git push origin master

## log in github and click Actions, search 'cmake', change some details and commit.
## edit read me
