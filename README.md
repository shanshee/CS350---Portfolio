# CS350---Portfolio

Among the projects for this course, the thermostat prototype and the Morse code display stood out. The thermostat project was designed to regulate temperature; it included a task scheduler that interfaced with a temperature sensor to monitor the ambient temperature. This was then compared to a predetermined set point, controlling a heating system (indicated by an LED) based on this comparison. User input was accepted through two buttons to adjust the set point, with the system regularly updating the temperature, the heating status, and runtime via UART.

The Morse code project was another highlight, where I programmed a system to cycle through displaying the messages 'SOS' and 'OK' in Morse code using LEDs. Users could switch messages with a button press, with the implementation using a state machine for LED control, ensuring accurate timing for dots, dashes, and spaces between characters and words.

I believe my strength in these projects was my methodical approach to breaking down tasks into manageable segments and pre-planning the program's flow. This strategy not only streamlined development but also simplified debugging.

An area for improvement identified was in creating state diagram documentation. While I could conceptualize and code the projects effectively, translating these ideas into clear and coherent state diagrams proved challenging. This is an aspect I aim to enhance with further practice.

Throughout these projects, I significantly expanded my knowledge in embedded systems programming, a new area for me before this class. The experience was enriched by various resources, particularly the documentation for the TI microcontroller, which became an invaluable part of my learning toolkit.

The projects honed my skills in program planning and modularization, invaluable across a wide range of future projects and coursework. By adhering to best coding practices—using descriptive naming, commenting, and modular functions—I ensured the projects were maintainable, readable, and adaptable. Specifically, the use of a state machine facilitated the easy addition of new features without altering existing code, exemplified by the ease of adding new Morse code messages.
