# LTSpice UX Design

By: Carson Howell
22 November 2024

Engineering students are exposed to several programs throughout their academic careers, so they are ready to design products once they graduate. Most software now have standard interfaces that users expect to design products in the most efficient way. **Efficiency** is key for engineers as a lot of tasks are repetitive, so having a way to do a task over and over again is vital to speed up lengthy design times. Most software nowadays has keyboard shortcuts as standard so engineers can accomplish tasks in the fewest steps needed.

SolidWorks, AutoCAD, LTSpice, and Fusion are standard software packages for mechanical engineers. Most of these software programs involve using 2D planes to design sketches that eventually turn into 3D products. Once a user learns the controls for one software program, switching from one program to another is quite familiar. However, some software programs have quirks and aren't the same as their standard counterparts. One prime example of this difference is LTSpice.


![image](https://github.com/user-attachments/assets/9f2e9eaf-c8c5-44a1-8985-154e34af720f)
This image shows an audio amplifier circuit. The icons of the resistor, capacitor, transistor, voltage source, and ground can be seen. This helps create a mental map of what the physical circuit will look like.

LTSpice is a software to design, debug, and analyze electric circuits. Its user pane is standard, with a large viewing plane and common toolsets on top for quick access. One common difference between this and other software is using a command line. Command lines have largely disappeared from modern software as most users prefer images and icons to interact with the software. This provides a higher **satisfaction** for users as remembering the syntax of every command is tedious and can often cause mistakes. It is also beneficial as it gives a **mental map** of what each icon does by showing the component being drawn. Having an icon that represents the real life item helps the user understand what this button does. For example, the capacitor looks like two parallel plates, which is what a capacitor essentially is. This creates less of a burden for the user having to figure out what each icon means. Having the wire tool to draw wires allows the user to physically see what connects to each point and what starting points and end points there are. LTSpice does a great job with this distinction as it allows an interface to see the electronic components for its new users; however, it also allows professional users a quick way to draw wires still by allowing a "command line" like interface by writing code to indicate wires.

So, my example was to try to copy this transistor circuit over and over since the circuit was cascaded. I had to go through 4 extra clicks each time I went into select mode to select and copy each time. It does not allow repeating copies. Again, this isn't an issue for advanced users who code the wires, but for new people, this makes the process too tedious to learn.

![image](https://github.com/user-attachments/assets/90693f7b-7b30-4411-9315-3fc0751a4a93)
This image shows the underlying code underneath the calculations. Users can write this code or draw the diagram themselves. Each does the same thing, but one is more convenient for the power user, and one is more convenient for the average user.

One issue I have with LTSpice is that its view controls need to be consistent with other engineering softwares. The typical "click and drag" option is not available. The left-click button moves the drawing in the direction you click, which is the opposite of all software I have used. To select anything, you must right-click anywhere and then click select. Even though power users most likely will take the code method, even for primary users, this could be a better design as it adds an unnecessary step, making that less **effective**. Effectiveness measures the ability to finish a task, and adding this extra step makes it unclear how to select anything when most users would already be used to this convention. The ability to pane in other software typically allows the left click to pane, but you must hold control simultaneously, and this should be used instead. Additionally, another I have is the readability of its charts. It defaults to a dark blue line to chart various data, and the black background makes it very hard to read.

![image](https://github.com/user-attachments/assets/27e37d15-ac99-47ac-a92e-dae7d1653ac9)
This last image demonstrates how hard it is to read the graph with the default blue line. It also demonstrates the unnecessary step of adding the move command under a menu. This neeeds to be a main option since this is a common action

There is a setting to change the color, which is vital when plotting 2 data sets at a time. Another color should be default, and the same color shouldn't be selected again to avoid common confusion.

