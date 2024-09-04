Project Title: GeoCanvas

Technologies: Java Swing

Functionalities:

Shape Drawing:

This applications enables users to draw various shapes, including rectangles, circles, hexagons, dots, lines and donuts. Implemented functionality for changing the border and fill colors of shapes using the JColorChooser class.

Shape Transparency:

Enabled transparency within the interior of circles. This functionality was achieved using java.awt.Graphics2D, java.awt.Shape, java.awt.geom.Area, and java.awt.geom.Ellipse2D classes.

MVC Architecture:

The application is structured according to the Model-View-Controller (MVC) pattern, ensuring a clear separation between data, user interface, and application logic.

Shape Management:

Implemented functionalities for adding, deleting, and modifying hexagons using the Adapter pattern. Enabled Z-axis position management for shapes, including operations such as "To Front", "To Back", "Bring To Front", and "Bring To Back".

Undo/Redo Functionality:

Implemented undo and redo functionalities using the Command and Prototype patterns. Undo and redo buttons are enabled only when the respective functionalities are available.

Logging and Data Storage:

Implemented a system for generating and displaying logs of executed commands, with the ability to save these logs to text files. Added functionality for serializing the complete drawing and saving it to external media using the Strategy pattern.

User Interaction:

Users can view the currently active colors for shape borders and fills, and change them through a color dialog. Implemented multi-selection of shapes and modification of individual shapes. Delete and modify buttons are available only under specific conditions.

Loading and Creating Drawings:

Implemented functionality for loading text files containing logs of executed commands and generating the corresponding drawings based on those commands.
