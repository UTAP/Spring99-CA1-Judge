# Spring 99 - CA1 - Judge
This repository consists of a judge for Spring 99 semester's first computer assignment.

## How to run?

### Linux Users
At first, you should give judge permissions to run by this command:
```
chmod 755 judge.sh
```
Then you should generate testcases for judge by this command:
```
./judge.sh -g mainCode/main.cpp
```

Now you can judge your code by this command:
```
./judge.sh <your code address>
```
For example we can judge our sample code like this:
```
./judge.sh sampleCode/sample.cpp
```

### Mac OS Users

At first, you should give judge permissions to run by this command:
```
chmod 755 mac_judge.sh
```
And then, you should generate testcases for judge by this command:
```
./mac_judge.sh -g mainCode/main.cpp
```

Now you can judge your code by this command:
```
./mac_judge.sh <your code address>
```
For example we can judge our sample code like this:
```
./mac_judge.sh sampleCode/sample.cpp
```