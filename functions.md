# function_examples
Used to house function examples and templates

# As seen on:
Functions and Arrays in Linux | bash shell scripting
https://www.youtube.com/watch?v=MfOta_tJGcA

#!/user/bin/env bash

# 3 examples of how to name a function
hello(){}
function hello(){}
function hello {}

#1: 
hello(){
echo "Good day $1 and $2"
}

#2:
function hello(){
echo "Good day $1 and $2"
}

#3:
function hello {
echo "Good day $1 and $2"
}



#calls function within script
hello Marry John
