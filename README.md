# Tip Calculator 

## *Kaylee Doty*

**Tip Calculator** computes the tip and total amount for a bill. The app uses the base amount and tip percentage to calculate the amount owed, and it also describes the quality of service based on the tip.

Time spent: **5** hours spent in total

## Functionality 

The following **required** functionality is completed:

* [X] User can enter in a bill amount (total amount to tip on)
* [X] User can enter a tip percentage (what % the user wants to tip).
* [X] The tip and total amount are updated immediately when any of the inputs changes.
* [X] The user sees a label or color update based on the tip amount. 

The following **extensions** are implemented:

* [X] Custom color palette selected
* [X] Button added that rounds the displayed tip and total to integers

## Video Walkthrough

Here's a walkthrough of implemented user stories: https://imgur.com/hvpB6f9

GIF created with [LiceCap](http://www.cockos.com/licecap/).

## Notes

It was challenging thinking about how the rounded tip and total should be computed (round together vs. individually) and how these values should be displayed
so that they make the most sense to the user. I wanted to update the EditText field with the rounded base amount so that the total was mathematically consistent,
but I wasn't able to figure out how to do so.

## License

    Copyright [2021] [Kaylee Doty]

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
