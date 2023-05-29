# Signature pad question type for LimeSurvey
A LimeSurvey question theme that uses the [signature_pad](https://github.com/szimek/signature_pad) js library (MIT Licence) to allow for the display of a signature pad as a variation of the LimeSurvey short-free-text type question, and to store the signature as PNG [Data URI](http://en.wikipedia.org/wiki/Data_URI_scheme)

First version is Compatible with LimeSurvey version 3.x

## Installation and Usage

1. Extract the files and place the signature folder in the upload/themes/question folder of LimeSurvey
2. Create a new "Short free style" text question and change the "Question theme" to "signature". The question code can be anything, but for this example, use: SIGNATUREQUESTION
3. A signature element will now display instead of a text box for entry.
4. You can display the signature in a subsequent question as an image by the following HTML/Expression Manager code:
`
<img src="{SIGNATUREQUESTION}"/>
`

##Demonstration video

<figure class="video_container">
  <video controls="true" allowfullscreen="true">
    <source src="https://raw.githubusercontent.com/adamzammit/LimeSurvey-Signature-Question/master/limesurvey-signature-question-usage.webm" type="video/webm">
  </video>
</figure>

##Details
Author: Adam Zammit <adam.zammit@acspri.org.au>
Repo: https://www.github.com/adamzammit/LimeSurvey-Signature-Question
