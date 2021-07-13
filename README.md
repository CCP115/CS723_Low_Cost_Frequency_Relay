# CS723_Low_Cost_Frequency_Relay
A two person project, written in C, to create an embedded system that monitors, drops, and reconnects loads based on the frequency of the incoming power signal.
Development was done using FreeRTOS and its associated synchronous, concurrent programming principles.

The design was split into separate threads, and priorities were assigned based on importance. Interrupts are used to monitor the enviroment, such as the frequency of the incoming signal, and behaviour of the system is based off of these external environment inputs.

The .docx file contains a report that breaks down functionality, design decisions taken, and justifications for these decisions. A system wide diagram is provided that also covers the relationships between interrupts, tasks, global variables, and guards such as mutexes and semaphores.
