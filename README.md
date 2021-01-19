# Pre-work - *Tip Calculator*

**Tip Calculator** is a tip calculator application for iOS.

Submitted by: **Kevin Lin**

Time spent: **2** hours spent in total

## User Stories

The following **required** functionality is complete:

* [x] User can enter a bill amount, choose a tip percentage, and see the tip and total values.
* [x] User can select between tip percentages by tapping different values on the segmented control and the tip value is updated accordingly

The following **optional** features are implemented:

* [ ] UI animations
* [ ] Remembering the bill amount across app restarts (if <10mins)
* [ ] Using locale-specific currency and currency thousands separators.
* [ ] Making sure the keyboard is always visible and the bill amount is always the first responder. This way the user doesn't have to tap anywhere to use this app. Just launch the app and start typing.

The following **additional** features are implemented:

- [ ] List anything else that you can get done to improve the app functionality!

## Video Walkthrough

Here's a walkthrough of implemented user stories:

![](https://i.imgur.com/MGrqUaY.gif)


GIF created with [EZGIF.com](https://ezgif.com).

## Notes

Everything went successful while implementing the code by following the guide, however, after a few times of restarting the simulator the Tap Gesture Recognizer stopped working, at first I thought this is caused by misckling something in the program as I'm not familiar with Xcode itself. However, the issue still remains after building a new project. 

The workaround was to switch between simulating devices, after switching from 12 Pro to 11 Pro Max the Recognizer started working again without any changes in the code itself. 

The other issue I faced was I couldn't get the slider to work with the Tip Control to show the current Tip Percentage as this is the first time I code using Xcode, I'll be finding videos online to learn how to develop a better software using Xcode than the one I completed here.  

## License

    Copyright 2021 Kevin Lin

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
