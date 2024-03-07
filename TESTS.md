# charge test
## setup
Connected 
```mermaid
flowchart LR
  usb --> b051[osf.b051.v1.0]
  b051 --> b105[osf.b105.v1.0]
  b105 --> b117[osf.b117.v1.0]
```
loaded 2 cells and monitored the input energy.
## results
The two cells charged at roughly 400mW untill full. Once charging stopped the circuit used roughly 4mW.


# discharge test
## setup
Connected 
```mermaid
flowchart LR
  b117[osf.b117.v1.0] --> b102[osf.b102.v1.0]
  b102 --> load
```
loaded 2 cells and monitored the output energy.
## results
no problems were encountered with an output of 1A.
