# DMX

## Documentation

### Scanned

This product adopts display mode operation and DMX mode operation,
the specific settings are as follows:

| NO |                              Display | Function Instruction                       |
|:--:|-------------------------------------:|--------------------------------------------|
| 1  |                            A001-A512 | DMX512 address code setting                |
| 2  |                            Au01-Au04 | Auto mode, 4 modes in total                |
| 3  |                            So01-So04 | Sound mode, 4 modes in total               |
| 4  |                            SE01-SE09 | Sound control sensitivity                  |
| 5  | CL01-CL03<br/>CL01<br/>CL02<br/>CL03 | Color selection<br/>single color<br/>RG<br/>RGY |

DMX channel function: This product uses standard DMX-512 signal, 
a total of 10 control channels, the control content is as follows:


| Channel |                        Channel Instruction                         |                                              Value range | Function Instruction                                              |
|:-------:|:------------------------------------------------------------------:|---------------------------------------------------------:|:------------------------------------------------------------------|
|   CH1   |                           Mode selection                           |                0-63  <br/>64-127<br/>128-191<br/>192-255 | Closed light mode<br/>Manual mode<br/>Auto mode<br/>Sound mode    |
|   CH2   |                         Closed light mode                          | No | No                                                                | 
|   CH2   |   Manual mode   | 0-255 | 51 patterns to choose                                             |
|   CH2   |   Auto mode   | 0-63<br/>64-127<br/>128-191<br/>192-255 | Auto mode 1<br/>Auto mode 2<br/>Auto mode 3<br/>Auto mode 4<br/>  |
|   CH2   |   Sound mode   | 0-63<br/>64-127<br/>128-191<br/>192-255 | Sound mode 1<br/>Sound mode 2<br/>Sound mode 3<br/>Sound mode 4<br/> |

### Printed
![pic1](docs/images/DMX-1.jpg)
![pic2](docs/images/DMX-2.jpg)

## Cable
[The cable](https://www.lixada.com/p-l0385.html)

![pic3](docs/images/DMX-cable-1.jpg)
