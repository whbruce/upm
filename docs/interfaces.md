UPM Interfaces                         {#interfaces}
==============

Release 6.1 introduced the concept of C++ interfaces. Currently only a small subset of modules implement interfaces as per table below.
Not that all sensor/actuator interface derive from [IModuleStatus](../src/upm/iModuleStatus.h) that allows you to access the module name.


| Interface    |  Modules | Example |
|--------------|-------------|------|
| [ILightSensor](../src/upm/iLightSensor.h) |  max4409, si1132 | [light-sensor.cxx](../examples/c++/light-sensor.cxx) |
| [ITemperatureSensor](../src/upm/iTemperatureSensor.h) |  max4409, si1132 | [light-sensor.cxx](../examples/c++/light-sensor.cxx) |


