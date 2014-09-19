##Hello World in Java

To run this program from the command line you can clone this repository using:

    git clone git@github.com:JSalig1/HelloWorld_java.git

Then run:

    java com.example.training.HelloWorld

The seemingly unneccessary subdirectories are there to get a grasp on the 'package' functionality in the source code.

#Passing in Arguments

New class can accept arguments passed in as a series of strings and will output the total count of arguments and the value of each.

Input example:

    java com.example.training.PassingArguments arg1 arg2

Returns:

    Number of args: 2
    arg1
    arg2

Input example:

    java com.example.training.PassingArguments "arg1 arg2"

Returns:

    Number of args: 1
    arg1 arg2
