<h1>Bicolor-traffic-light-using-Zephyr-OS</h1>



<h2>Overview</h2>

Development of a bicolor traffic light management system for a two-way intersection using Zephyr OS.

The project simulates two cars on lane 1 and three on lane 2 to ensure smooth and safe traffic flow.

Traffic synchronization is handled using mutexes and semaphores, while a pedestrian button allows the light cycle to be interrupted for crossing.

The system state (traffic lights and vehicles) is displayed on four 7-segment displays, fully controlled by the program.

In the demonstration, “F” indicates a green light and “C” indicates a car (e.g., “F2” for light 2 being green, “C2” for car 2 crossing).
</br>
<p align="center"> 
<img src="https://github.com/BASSO-Jostin/Bicolor-traffic-light-using-Zephyr-OS/blob/main/Media/Image_Zephyr.jpg" alt="Image 2" style="width:50%; border-radius:7px; height : 300px">
</p>





<h2>Features</h2>



<ul>

<li>Two-way traffic light control (red and green)</li>

<li>Simulation of up to five cars</li>

<li>Implemented on Zephyr OS for real-time embedded systems</li>

<li>Modular and easy-to-extend code structure</li>

</ul>



<h2>Hardware</h2>



<ul>

<li>Microcontroller compatible with Zephyr OS (EDU32F103)</li>

<li>7-segment displaysgreen lights</li>

<li>buttons</li>

</ul>



<h2>Software</h2>

<ul>

<li>Zephyr OS</li>

<li>C/C++ programming</li>

<li>Make/CMake build system</li>

</ul>



<h2>Contributing</h2>



Contributions are welcome! Feel free to open issues or pull requests for improvements, bug fixes, or feature additions.

