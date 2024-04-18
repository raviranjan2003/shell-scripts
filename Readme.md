# Shell Script

### Display anything on console
```sh 
    echo "I am Ravii"
```
### Variables
```sh
    name="Ravii"
    echo $name
```
### Take input from console
```sh
    echo "What is your name : "
    read name
    echo "Hello, $name"

    read -p "What is your name : " name
    echo "Hello, $name"
```
### Operators
    -Arithmetic Operators: +, -, *, /, %
    -Comparison Operators: ==, !=, -eq, -ne, -lt, -le, -gt, -ge
    -Logical Operators: && (AND), || (OR), ! (NOT)

### Conditional
```sh
    a=5
    b=10
    if [ $a -gt $b ]; then
            echo "$a is greater than $b"
    else
            echo "$b is greater than $a"
    fi
```

### Loops
For Loop
```sh
    for i in {1..5}; do
        echo "Number: $i"
    done
```
While Loop
```sh
    a=5
    while [ $a -gt 0 ]; do
        echo "Number a : $a"
        a=$((a-1))
    done
```