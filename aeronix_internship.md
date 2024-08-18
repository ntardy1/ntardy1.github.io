# Engineering Internship @ [Aeronix, Inc](https://www.aeronix.com/).

I worked as an engineering intern at Aeronix from May 2024 through early August 2024. My role was largely (like, 95%) that of a software engineering intern, and during my time there, I had the opportunity to meaningfully contribute to two projects.

For the first project, I developed a C++ application to facilitate communication with a spacecraft (i.e., sending commands and receiving telemetry) and assist with pre-launch ground testing efforts. To support its communication functionality, the app used [Google Protocol Buffers](https://protobuf.dev/) (Protobufs) to serialize and deserialize outgoing commands and incoming telemetry messages. These messages adhered to the form prescribed by the [CCSDS Space Packet Protocol](https://public.ccsds.org/Pubs/133x0b2e1.pdf) and were displayed to the user with a scolling text window. Furthermore, the app leveraged a Model-View-Controller (MVC) architecture to cleanly and efficiently separate the data-storage and data-structure portions from the user interface portion (which was dependent on the esoteric library selected for the GUI generation).

This project exposed me to a plethora of the facets of professional software engineering, including (but absolutely not limited to)
- the practices of Agile software development (Scrum, Sprints, etc.),
- using a Jira ticketing system for task tracking, and
- writing clean, expandable, and turnkey code in an iterative development environment.

For the second project, I had the opportunity to work with [Mesa OpenGL](https://www.mesa3d.org/): an open-source 3D graphics library. I removed reliance on external dependencies from portions of the library's code and replaced the functionality with calls to local header files (`#include`) that were designed to mimic the previous dependencies. I then used `Make` and `GNU` compilation tools to semi-automate the compilation process for the "reduced" library. In addition to `Make`, this project gave me the opportunity to work with software development tools such as `gcc` and Linux VMs.

While my time at Aeronix allowed me to develop the skills I described above, it also enabled me to sharpen some skills I had already established, such as `C++`, `Python`, and working with `git` for version control. Overall, this time expanded my software development knowledge and empowered me with the capability to effectively contribute to a larger variety of complex software projects.

[Return to main page](./index.html).