# myAdapter

My IoBroker Adapter stub file
It contains the main classes I use in all ioBroker projects

## Changelog

### 1.2.8

* added support for  "@iobroker/adapter-core": "^2.3.x" used for js-controller 3.0
* changed name in code
* Change of isLinuxApp

### 1.2.5

* Changed to newer @iobroker/adapter-core and removed to use 

### 1.2.0

* Added feature to use timestamp instead of ack in makestate/changestate to update state with other (old) timestamp

### 1.1.6

* new init routine asking only for adapter objects and separately for system config object
* Log message when adapter is in compact mode
* Change waitfunction to accept functions as arg
* Change isLinuxApp to return true only o0n linux-os
* Prepared for compact mode

### 1.1.3

* new init and getObj routine

### 1.0.3

* added A.number(v) which creates a number from v and if it is NaN then it will be 0

### 1.0.2

* latest update of Df/Dr/D and repeat