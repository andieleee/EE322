# EE 322
  **Andrew Lee**: *3/4 Electrical Engineer*
  > Concentration in Embedded Systems <br>
  
![](Resources/kirbo_spin.gif)
## About Me
 - Love watching soccer and F1
 - Excited to learn
 - Sleeeeeeep
## [Labs](https://github.com/andieleee/EE322/tree/main/Labs)
  1. [Lab 1](https://github.com/andieleee/EE322/blob/main/Labs/Lab_1.md)
  2. [Lab 2](https://github.com/andieleee/EE322/blob/main/Labs/Lab_2.md)
  3. [Lab 3](https://github.com/andieleee/EE322/blob/main/Labs/Lab_3.md)
  4. [Lab 4](https://github.com/andieleee/EE322/blob/main/Labs/Lab_4.md)
  5. [Lab 5](https://github.com/andieleee/EE322/blob/main/Labs/Lab_5.md)
  6. [Lab 6](https://github.com/andieleee/EE322/blob/main/Labs/Lab_6.md)
  7. [Lab 7](https://github.com/andieleee/EE322/blob/main/Labs/Lab_7.md)
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
