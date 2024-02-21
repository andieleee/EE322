# EE 322
  **Andrew Lee**: *3/4 Electrical Engineer*
  > Concentration in Embedded Systems <br>
  
![](Resources/kirbo_spin.gif)
## About Me
 - Love watching soccer and F1
 - Excited to learn
 - Sleeeeeeep
## [Labs](https://github.com/andieleee/EE322/tree/main/Labs)
  1. [Lab 1](https://github.com/andieleee/EE322/blob/main/Labs/Lab1.md)
  2. [Lab 2](https://github.com/andieleee/EE322/blob/main/Labs/Lab2.md)
  3. [Lab 3](https://github.com/andieleee/EE322/blob/main/Labs/Lab3.md)
  4. [Lab 4](https://github.com/andieleee/EE322/blob/main/Labs/Lab4.md)
  5. [Lab 5](https://github.com/andieleee/EE322/blob/main/Labs/Lab5.md)
  6. [Lab 6](https://github.com/andieleee/EE322/blob/main/Labs/Lab6.md)
  7. [Lab 7 fixed!](https://github.com/andieleee/EE322/blob/main/Labs/Lab7.md)
  8. [Lab 8](https://github.com/andieleee/EE322/blob/main/Labs/Lab8.md)
  9. [Lab 9 WIP](https://github.com/andieleee/EE322/blob/main/Labs/Lab9.md)
  10. [Lab 10 WIP](https://github.com/andieleee/EE322/blob/main/Labs/Lab10.md)
## Code
Some random OMNeT++ Code
```
#ifndef __MY_EXTENDED_NETWORK_SINK_EXT_H_
#define __MY_EXTENDED_NETWORK_SINK_EXT_H_

#include <omnetpp.h>
#include <Sink.h>
using namespace omnetpp;

class Sink_Ext : public queueing::Sink
{
  protected:
    cHistogram histogram;
    virtual void initialize() override;
    virtual void handleMessage(cMessage *msg) override;
};

#endif
```
