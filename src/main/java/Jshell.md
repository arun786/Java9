# Jshell

to print Hello World on jshell console

    jshell> "Hello World"
    $1 ==> "Hello World"

to print 5 * 3

    jshell> "5 * 3"
    $2 ==> "5 * 3"

to print the result 5 * 3

    jshell> 5 * 3
    $3 ==> 15

to print multiplication table of 5

    jshell> for ( int i =0 ; i < 10; i++){
       ...> System.out.println((i+1)+ " * 5 = " + ((i+1) * 5));
       ...> }
    1 * 5 = 5
    2 * 5 = 10
    3 * 5 = 15
    4 * 5 = 20
    5 * 5 = 25
    6 * 5 = 30
    7 * 5 = 35
    8 * 5 = 40
    9 * 5 = 45
    10 * 5 = 50

print number of seconds in a day

    jshell> 60*60*24
    $10 ==> 86400
