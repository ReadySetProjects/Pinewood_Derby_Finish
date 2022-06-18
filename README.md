## Forword

this provided code and any documentation in this repository comes with no warranty or expectations. I 
just wanted to at least provide some of the core info i've gathered and used to make the finish line work
like i have. This is not intended to be a complete plug and play or fully documented source of info, and 
i likely will not have the time to come back through and make it so or fix issues. But you are welcome 
to take what i have and run with it and i hope providing this info helps someone.

## Test7SegDisplay.ino

Test7SegDisplay.ino was my playground for figuring out driving the 7seg displays.

Right now it's setup to have all 4 displays mounted and used to count down every second.

The other define option was used when i have the project breadboard mounted and i could plug in one diplsay
module. So it was used to have a lane input (or a pullup with button to ground) increment the number. the
button input method is probably broken because i could only fit 2 display modules on one side of the
breadboard so it was meand for shiftNumOut() to display 2 digits and ducplicate it on the other two displays.

## RSP_PinewoodDerbyFinish.ino

This file is fully functional as shown in the video!

I did walk through the code qucikly in the video so look there first for an explination on how everything works.
Arduino is not my normal playground, so hopefully my C coding style hasn't come out too much in the code....

## Support

This code was made in conjunction with these youtube videos showcasing building the finish line.

comments section and info in the videos should be the first line of support

[![Video Part 1](https://img.youtube.com/vi/rtugbOUozOg/0.jpg)](https://www.youtube.com/watch?v=rtugbOUozOg)

[![Video Part 2](https://img.youtube.com/vi/Gi4np0JqLgA/0.jpg)](https://www.youtube.com/watch?v=Gi4np0JqLgA)


## Bugs or Issues

I have been able to have the race show weird results a few times, but i think those have been fixed by 
initializing the interrupts after sensor calibration.

If you find a bug you can submit an issue here on github:

https://github.com/revoracing247/RSP_Arduino_PinewoodDerbyFinish/issues

Before posting a new issue, please check if the same problem has been already reported by someone else
to avoid duplicates.

Considering that i will not have the finish line hardware available to test on, there are non garentees
i will be able to fix any issues.

## License and credits

This code has been developed by Colby Robbins in conjuction with Ready Set Robbins

```
	Copyright (c) 2022, Ready Set Robbins
	All rights reserved.

	Redistribution and use in source and binary forms, with or without
	modification, are permitted provided that the following conditions are met:

	* Redistributions of source code must retain the above copyright notice, this
	  list of conditions and the following disclaimer.

	* Redistributions in binary form must reproduce the above copyright notice,
	  this list of conditions and the following disclaimer in the documentation
	  and/or other materials provided with the distribution.

	* Neither the name of the copyright holder nor the names of its
	  contributors may be used to endorse or promote products derived from
	  this software without specific prior written permission.

	THIS SOFTWARE IS PROVIDED BY THE COPYRIGHT HOLDERS AND CONTRIBUTORS "AS IS"
	AND ANY EXPRESS OR IMPLIED WARRANTIES, INCLUDING, BUT NOT LIMITED TO, THE
	IMPLIED WARRANTIES OF MERCHANTABILITY AND FITNESS FOR A PARTICULAR PURPOSE ARE
	DISCLAIMED. IN NO EVENT SHALL THE COPYRIGHT HOLDER OR CONTRIBUTORS BE LIABLE
	FOR ANY DIRECT, INDIRECT, INCIDENTAL, SPECIAL, EXEMPLARY, OR CONSEQUENTIAL
	DAMAGES (INCLUDING, BUT NOT LIMITED TO, PROCUREMENT OF SUBSTITUTE GOODS OR
	SERVICES; LOSS OF USE, DATA, OR PROFITS; OR BUSINESS INTERRUPTION) HOWEVER
	CAUSED AND ON ANY THEORY OF LIABILITY, WHETHER IN CONTRACT, STRICT LIABILITY,
	OR TORT (INCLUDING NEGLIGENCE OR OTHERWISE) ARISING IN ANY WAY OUT OF THE USE
	OF THIS SOFTWARE, EVEN IF ADVISED OF THE POSSIBILITY OF SUCH DAMAGE.
```