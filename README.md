### FORK CHANGES 
Change to support Alpine for hass.io (hassio):

Add to __/drivers/spidev.cpp__
````cpp
#include <asm/ioctl.h>
````
to solve the problem: error: 
````
'_IOC_SIZEBITS' was not declared in this scope
````

-----------------------------------------------------------------

MySensors Library v2.3.2-alpha

Please visit www.mysensors.org for more information

Documentation
-------------
[master](https://www.mysensors.org/apidocs/index.html) [development](https://www.mysensors.org/apidocs-beta/index.html)

CI statuses
-----------
Current build status of master branch: [![Build Status](https://ci.mysensors.org/job/MySensors/job/MySensors/job/master/badge/icon)](https://ci.mysensors.org/job/MySensors/job/MySensors/job/master/)

Current build status of development branch: [![Build Status](https://ci.mysensors.org/job/MySensors/job/MySensors/job/development/badge/icon)](https://ci.mysensors.org/job/MySensors/job/MySensors/job/development/)

Current build status of master branch (nightly build of Arduino IDE): [![Build Status](https://ci.mysensors.org/job/MySensors-nightly-IDE/job/MySensors/job/master/badge/icon)](https://ci.mysensors.org/job/MySensors-nightly-IDE/job/MySensors/job/master/)

Current build status of development branch (nightly build of Arduino IDE): [![Build Status](https://ci.mysensors.org/job/MySensors-nightly-IDE/job/MySensors/job/development/badge/icon)](https://ci.mysensors.org/job/MySensors-nightly-IDE/job/MySensors/job/development/)
