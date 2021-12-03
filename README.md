# _epicodus_review_3_ #

#### _An application to show my understanding of arrays and looping_

#### By _**Ryan Rendon**_

## Technologies Used

* _HTML_
* _CSS_
* _JavaScript_
* _Jquery_

## Description

_Hello and thank you for viewing my Magic of looping application! This project uses concepts learned in my early weeks at epicodus. It combines HTML elements with bootstrap as well as a custom style sheet! The application will take a postitive number and create a list from 0 to the inputted number and replace numbers containing a 1, 2, or 3 with a custom message._

| Input      | Output     | 
| :---       |    :----:  |      
| 3          | Beep, Boop, Won't you be my Neighbor?     | 
| 5          | Beep, Boop, Won't you be my Neighbor?, 4, 5  |

## TTD Specs
_Describe: looping()

Test: "It should return a warning 'field is required' if nothing is inputted"
Code: looping(0);
Expected Output: 'field is required'

Test: "It should return Beep if 1 is entered"
Code:  looping(1);
Expected Output: beep

Test: "It should return boop instead of 2 if 2 is entered"
Code: looping(2);
Expected Output: beep, boop

Test: " It should return 'Won't you be my neighbor?' instead of 3 if 3 is entered"
Code: looping(3);
Expected Output: beep, boop, Won't you be my neightbor?

Test: "It should return beep if the number contains a 1"
Code: looping(11);
Expected Output: beep, boop, Won't you be my neightbor?, 4, 5, 6, 7, 8, 9, beep, beep

Test: "It should overide rules of 2 > 1 so if 12 is entered it should return boop"
Code: looping(12)
Expected Output: beep, boop, Won't you be my neightbor?, 4, 5, 6, 7, 8, 9, beep, beep, boop

Test: "It should overide rules of 3 > 2 || 3>1 so if 32 || 13 is entered it should return 'Won't you be my neighbor"
Code: looping(13)
Expected Output: 0,beep,boop,Won't you be my neighbor?,4,5,6,7,8,9,beep,beep,boop,Won't you be my neighbor?,beep,beep,beep,beep,beep,beep,boop,boop,boop,Won't you be my neighbor?,boop,boop,boop,boop,boop,boop,Won't you be my neighbor?,Won't you be my neighbor?,Won't you be my neighbor?
## Setup/Installation Requirements

* You can visit my github Rendo4 or you can copy this link to my repository https://github.com/Rendo4/epicodus-review-3 
* _open your terminal_
* _use the command "cd desktop"_
* _use the command "git clone (https://github.com/Rendo4/epicodus-review-3)_
* _It should now be on your desktop! Open the folder "epicodus-review-3"_
* _Click on "Index.html" This will open the file for viewing._

## Known Bugs

* _No known bugs_

## License

Copyright 2021 Ryan Rendon

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

    http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.

## Contact Information
_{Rendon.S.Ryan@gmail.com}_