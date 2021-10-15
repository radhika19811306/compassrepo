# compass-test
The program runs using python 3.8. Please ensure you have python 3+ on your laptop

Please clone the repo as follows and execute using the following commands
### pip3 install requests
### git clone https://github.com/radhika19811306/compass-test.git
### python3 radhika.py

The output of the file is written to the same location where the command is executed. the ouput file name is

### output.csv

The program takes the following inputs
1. The github username
3. The personal token for identification
4. The no of commits (this is only for the purpose of testing)

Assumptions
1. The commits will be fetched for user and user name should be provided
2. the user can have more than 1 repo
3. when calculating the mean the interval between each of the x commits is calcuated in decending order. Hence mean is calculated over x-1 values
4. I have not used log4j but logging capabilities for debugging can be added easily





