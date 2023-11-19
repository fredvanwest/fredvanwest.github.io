# Code Review
If you’ve reached this page, then you are probably interested in how all of this works. Rest assured that web standards were employed and there is no need to download anything extra to get started. 
A full explanation of how to write web applications is outside the scope of this short video, but if you already have a background in writing simple JavaScript, CSS and HTML, you will feel right at home.

## Github
The code is housed at Github using the following URL:

`https://fredvanwest.github.io`

You can feel free to clone or fork your own copy and should there be a need to make changes, we can evaluate any pull requests. There are no build systems in place, only static pages, but more complex 
AR experiences can be found below.

## AR.js
The AR.js library can be found at github at the following URL:
`https://ar-js-org.github.io/AR.js-Docs/`
There you will find tutorials and walk throughs for how to use images as markers to trigger pop ups. In our example, we’re using both pop up images as well as a pop up video.

This library provides a framework for building augmented reality applications using a markup language called A-Frame (see: `https://aframe.io` ). There are a number of online videos for 
writing your own A-Frame applications but in this case, A-Frame provides mark up to declare our augmented reality scene as well as describing what happens.

In our case, we pull in the AR.js library using the `<script>` tags and simply mark up the page with A-frame tags. In general, we create a scene and populate it with registration marks and when 
those marks are detected by the Chrome browser (for instance), then an image canvas pops up with the proof graphic populating it.  In the case of the QR code, we do something a little different 
in that when the registration mark is detected, a video (MP4) will play on the canvas rather than simply playing the graphic.  A more detailed explanation is available on the AR.js website.

## MathML
The markup that represents the equations (for instance in the proofs) represents tags that describe mathematical equations. The equations were built using Apple Pages and emitted using an open 
standards language called LaTeX which is commonly used for typesetting. The TEMML website (`https://temml.org`) translates LaTeX into MathML for rendering within modern websites since LaTeX does not display as is.

The Equations Themselves
These equations have circulated the web for many years but collecting them in this format and using them along with the music and proofs is unique to Mathemajickal Mugs.  The proofs themselves 
are relatively easy to follow and are a tool to explain concepts to amateur math students.
