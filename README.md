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
  2. Second
  3. Third
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
