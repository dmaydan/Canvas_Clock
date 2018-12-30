# Analog Clock on `<Canvas>`
The design of this analog clock is loosely based off of the [following image of a rolex](https://www.christies.com/lotfinder/Lot/inducta-for-rolex-a-large-and-attractive-5967650-details.aspx). The construction and animation of the clock takes advantage of several trigonometric functions. The <code>requestAnimationFrame(animate)</code> function schedules the animate function to run whenever the browser is ready to repaint the document; when the browser tab is active, the document will be repainted about 60 times per second, which is usually sufficient for producing high quality imagery. All the imagery is constructed within the `<canvas>` element.

You can view a demo of this clock at https://dmaydan.github.io/Canvas_Clock.
