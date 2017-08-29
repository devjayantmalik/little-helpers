## alfred/pixelsToEm.alfredworkflow
type `em#` and the workflow asks for your desired font-size in pixels.
The output will result in em-Values. The cursor is then placed right before "em" so you can easily modify the output to "rem".

Example output: `0.625em; /* -- 10px/16px -- */`

![Screenshot](/.screenshots/pixelsToEm.alfredworkflow.gif)

#TODO:
- currently based on 16px / allow dynamic input of root-font-size
- ~~add Icon~~
- ~~remove leading 0 in result~~

# Kudos
[Zach Leat](https://github.com/zachleat/) came up with a typinator-snippet for instant calculation of em/rem-Values.
https://gist.github.com/zachleat/c135c079f802934006978e2257086cc3

This is workflow is based on Zach's idea