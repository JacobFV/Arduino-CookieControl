# Arduino-CookieControl
Cookie Cutter plasma cutter CNC command interpreter for onboard Arduino

CookieControl (my other GIT repository) is the Windows software that reads .SVG files. That program processes the information into an optimized path coordination code. They paths are either lines, arcs, or beizer curves. Then CookieControl sends this information over serial to the Arduino which this program reads from a buffer and moves the Cookie Cutter corespondingly. Because the paths can be quite complicated, the Cookie Cutter code first completes its current path which may take seconds before asking CookieControl for the next path. Writnig this software taught me important serial essentials and impressed the importance of design patterns.
