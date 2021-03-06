[![Codacy Badge](https://api.codacy.com/project/badge/Grade/ced3d7489b0441929563cacfbe5b8e47)](https://www.codacy.com/app/pegasus.ict/PBFL?utm_source=github.com&amp;utm_medium=referral&amp;utm_content=pegasusict/PBFL&amp;utm_campaign=Badge_Grade)

# BashBox - A BASH Framework
This is my attempt at building a framework for BASH.

### Update july 2nd 2020: A complete overhaul has begun
I've decided to change my function library into a framework due to added benefits.
### Functionality:
| Functionality                    | Status | Progress | Remarks                               |
|----------------------------------|:------:|---------:|---------------------------------------|
| dynamic loading of modules       | alpha  |      10% | rewritten autoloader; needs testing   |
| automagic installing of modules  |planned |      10% | depends: git                          |
| logging                          | alpha  |      10% | rewritten, needs new tests            |
| ini parsing                      | alpha  |      50% |                                       |
| apt-get functionality            | alpha  |      50% |                                       |
| git functionality                | draft  |      50% |                                       |
| exit code generating/handling    |  dev   |      40% |                                       |
| date/time functions              |  beta  |       -- |                                       |
| file generation/modification     |partial |          |                                       |
| templating                       |planned |          |                                       |
| filesystem operations            |partial |          |                                       |
| temp dirs/files                  |        |          |                                       |
| mutex (lock files) functionality |        |          |                                       |
| RSA functionality                |        |          |                                       |
| *edit in progress...*                                                                        |

### Update nov 4th 2019: implemented a new autloloading system, inspired on PHP's autoloader.
Place your lib file in the "lib" directory and a file in the autoload directory. See one of the existing ".load.bash" files for examples.

--
Acknowledgements:
ini parser: Ruediger Meier (https://github.com/rudimeier/)
