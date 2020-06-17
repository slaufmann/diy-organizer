# diy-organizer
Create sheets like monthly and weekly calendars for a paper-based organizer.

## Based upon
This project is based on [DIY A5 AvantGarde 2pg/Month and 2pg/week](http://diyplanner.com/node/6270) by Rurik Christiansen and 
was modified to fit my needs and taste.

## License
Like the original source this project is licensed under the Creative Commons license. Since the original 
author did not specify any further details I chose [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/).

## Prerequisites
In order to build this project you need (at least):
* a LaTeX distribution (e.g. texlive-full on Debian Linux)
* Python (tested with Python 2.7.18)
* make

## How to build
First adapt some settings in `gen_Current_Macros.py` to your needs.
Then simply build the document by running `make`.
