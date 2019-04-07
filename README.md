# myAdapter

My IoBroker Adapter stub file
It contains the main classes I use in all ioBroker projects

## Changelog

### 1.1.5

* new init routine asking only for adapter objects and separately for system config object
* Log message when adapter is in compact mode
* CHange waitfunction to accept functions as arg
* Change isLinuxApp to return true only o0n linux-os

### 1.1.3

* new init and getObj routine

### 1.0.3

* added A.number(v) which creates a number from v and if it is NaN then it will be 0

### 1.0.2

* latest update of Df/Dr/D and repeat