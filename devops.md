 
#!/bin/bash
echo "hello"

function1()
{
    echo "call function 2 from function 1"
    function2
}


function2()

{

    echo "this is function2 "
}

function1
#this file added at the branch feature x
