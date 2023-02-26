# JS-Day-18-B
Background Slider

These lines of code enable a slider with buttons that can change the background images. The HTML code forms the webpage structure and links external files such as CSS and JavaScript. CSS code determines the layout and style of the webpage, including the slider and arrow buttons' position and design. JavaScript code adds functionality to the webpage, listens to arrow button clicks, and changes the active slide.

The slider is created using a series of div elements with a class of slide. Each slide element has a background-image property that defines the image to be used as the background. An activeSlide variable keeps track of the current slide, starting at 0.

To create the arrow buttons, button elements with a class of arrow and the id of left and right, respectively, are used. The i element within each button has the class of fas fa-arrow-left or fas fa-arrow-right to define the left and right arrow icons.

When a user clicks the left or right arrow button, the activeSlide variable changes, and the slide elements are transitioned using CSS to display the next or previous background image. The opacity property is used to transition the slide elements, making the active slide visible and the inactive ones invisible.