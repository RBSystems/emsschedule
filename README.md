# emsschedule
[![CircleCI](https://img.shields.io/circleci/project/byuoitav/emsschedule.svg)](https://circleci.com/gh/byuoitav/emsschedule) [![Codecov](https://img.shields.io/codecov/c/github/byuoitav/emsschedule.svg)](https://codecov.io/gh/byuoitav/emsschedule) [![Apache 2 License](https://img.shields.io/hexpm/l/plug.svg)](https://raw.githubusercontent.com/byuoitav/emsschedule/master/LICENSE)

## Notes
Because of naming discrepancies between our databases and the data in [EMS](https://emsweb.byu.edu/VirtualEMS/BrowseForSpace.aspx), some rooms may not be found on search. This package is written so that such situations return a "false positive" in this case so that microservices aren't blocked eternally.
