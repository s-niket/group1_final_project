ENPM 809B===[ Group-1 ]
Members:

1. Abhiram Dapke(116237024)
2. Prasanna Marudhu(116197700)
3. Smriti Gupta(116748612)
4. Niket Shah (116345156)
5. Piyushkumar Bhuva(116327473)



Contents:
Folder (group1_final_project)
   - config
   - include
   - launch
   - src
   - video
   - CMakeLists.txt
   - package.xml
   - pick_place.sh


------HOW TO RUN:  -----------------
Follow the instructions :

Extract the package in your workspace and build it using: 

1. catkin_make 
2. source devel/setup.bash

Give permissions to the script named "pick_place.sh" by making your present working directory as the package (need xterm installed to run this, install using "sudo apt-get install xterm") and do: 
	
3. cd /path/to/package/
4. sudo chmod a+x pick_place.sh

Run the packages by running the script: 

5 ./pick_place.sh
