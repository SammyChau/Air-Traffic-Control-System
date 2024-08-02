# Air-Traffic-Control-System
The main objective of this mini-project is to illustrate the concepts and practical applications of ATC using OpenGL, an API known for its capability to render 2D and 3D vector graphics across various platforms. 
Air traffic control (ATC) is an essential service that manages the safe and efficient movement of aircraft both in the sky and on the ground. Ground-based controllers direct aircraft to prevent collisions, organize the flow of traffic, and provide pilots with vital information and support. ATC systems are crucial for maintaining order and safety in increasingly busy airspaces, ensuring that each aircraft maintains a safe distance from others through enforced traffic separation rules.The main objective of this mini-project is to illustrate the concepts and practical applications of ATC using OpenGL, an API known for its capability to render 2D and 3D vector graphics across various platforms. By leveraging OpenGL, the project aims to visually demonstrate the key functions of ATC systems, making the complex processes involved in air traffic management more comprehensible.
Functions used in the program
1.	glutInit() : interaction between the windowing system and OPENGL is initiated
2.	glutIniDisplayMode() : used when double buffering is required and depth information is required
3.	glutCreateWindow() : this opens the OPENGL window and displays the title at top of the window
4.	 glutInitWindowSize() : specifies the size of the window.
5.	glutInitWindowPosition() : specifies the position of the window in screen co-ordinates
6.	 glutKeyboardFunc() : handles normal ASCII symbols
7.	 glutSpecialFunc() : handles special keyboard keys
8.	 glutReshapeFunc() : sets up the callback function for reshaping the window
9.	 glutIdleFunc() : this handles the processing of the background
10.	 glutDisplayFunc() : this handles redrawing of the window
11.	 glutMainLoop() : this starts the main loop, it never returns
12.	 glViewport() : used to set up the viewport
13.	 glVertex3fv() : used to set up the points or vertices in three dimensions
14.	 glColor3fv() : used to render color to faces
15.	 glFlush() : used to flush the pipeline
16.	 glutPostRedisplay() : used to trigger an automatic redrawal of the object
17.	 glMatrixMode() : used to set up the required mode of the matrix
18.	 glLoadIdentity() : used to load or initialize to the identity matrix
19.	 glTranslatef() : used to translate or move the rotation centre from one point to another in three dimensions
20.	 glRotatef() : used to rotate an object through a specified rotation angle
Interaction with the program
We can have an interaction with this project using popular input device like mouse and key board are used to interact with this program. Some keys of key board have specific function, we mentioned them below
1.	‘a’ – add new plane 
2.	‘r’ – to remove plane
3.	‘t’ – take off
4.	 ‘q’– quit
