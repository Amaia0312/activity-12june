# activity-12june
homework for today

* Ripple effect tutorial from web designer issue 286

*The <link rel="style sheet" type="text css" href="styles.css" /> links the main page with the css sheet together 
*  The button step:  <button class="ripple">Ripple Button</button>
    <button class="ripple red shadow">Ripple Button</button>
    <button class="ripple big">Ripple Button</button>
    <button class="ripple big red shadow">Ripple Button</button> this is the set up for the buttons on the page.\
* The body initation : body {
    background: url('image.jpg') black;
    background-size: cover;} this step makes a background using a image so the effect can be seen when you click on it.
*The intial ripple effect: .ripple {
    position: relative;
    background: transparent radial-gradient(circle, transparent 1%, rgba(255,255,255,.5) 10%, transparent 1%) center;background-size: 2000%; background-position: center;transition: background 1s, opacity 1s;
    font-size: 1em;opacity: .75;color: #fff;, this step is the first part of the ripple.

*Activating the Ripple : .ripple:hover { opacity: 1;}.ripple:active {background-size: 0;transition: 0s;
    opacity: .25;This step is when the mouse triggers the ripple effect  and it resizes the image and sets up immediate activation.Makes it semi transparent.

*Additional properties and sharebutton sytles:
 por.big { font-size: 2em }.red { Color:red; }.shadow {Text-shadow: 2px 2px 2px black;}button border: .1mm solid;padding: 1em; these steps allows the boxes to appear as diffrent colors and the borders and padding around the buttons.