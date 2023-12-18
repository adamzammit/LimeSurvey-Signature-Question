# Signature pad question type for LimeSurvey
A LimeSurvey question theme that uses the [signature_pad](https://github.com/szimek/signature_pad) js library (MIT Licence) to allow for the display of a signature pad as a variation of the LimeSurvey short-free-text type question, and to store the signature as PNG [Data URI](http://en.wikipedia.org/wiki/Data_URI_scheme)

Compatible with LimeSurvey versions 3.x,4.x,5.x,6.x


## Installation and Usage (LimeSurvey 6.x)

1. Download the latest release
2. Visit the "Configuration" -> "Themes" -> "Question theme" in the LimeSurvey GUI
3. Click on "Upload and Install" and browse to the latest release download, and click on "Upload".
4. Create a new question and choose the "Signature Pad" type (under "Text questions") - (note due to a LimeSurvey bug, the preview of short free text question will appear instead)
5. You can display the signature in a subsequent question as an image by the following HTML/Expression Manager code:
```
<img src="{signature}"/>
```


## Installation and Usage (LimeSurvey 3.x, 5.x)

1. Extract the files and place the signature folder in the upload/themes/question folder of LimeSurvey
2. Create a new "Short free style" text question and change the "Question theme" to "signature". The question code can be anything, but for this example, use: signature
3. A signature element will now display instead of a text box for entry.
4. You can display the signature in a subsequent question as an image by the following HTML/Expression Manager code:
```
<img src="{signature}"/>
```

## Installation video (LimeSurvey 6.x)

[limesurvey-install-question-theme-2023-12-19.mp4](https://github.com/adamzammit/LimeSurvey-Signature-Question/assets/1452303/14757dac-3a61-4301-8858-23d17689d922)

## Demonstration video (LimeSurvey 6.x)

[limesurvey-use-question-theme-2023-12-19.mp4](https://github.com/adamzammit/LimeSurvey-Signature-Question/assets/1452303/dd31b7ed-98c1-4f32-a30c-b2d43fd3c0a9)

## Demonstration video (LimeSurvey 3.x)

[limesurvey-signature-plugin-2023-05-29_16.11.48.webm](https://github.com/adamzammit/LimeSurvey-Signature-Question/assets/1452303/f69d1f9f-6037-458c-8da7-295814ad9efd)


## Details
Author: Adam Zammit <adam.zammit@acspri.org.au>
Repo: https://www.github.com/adamzammit/LimeSurvey-Signature-Question
