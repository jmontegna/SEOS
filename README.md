# SEOS
Systems Engineering OS

Summary:
Create a work management system to go on top of an actual operating system to coordinate work and reduce complexity from communication overheads in distributed systems.

Motivation
Original idea was to develop a task management system for organizing the communication, creation, scheduling, working, and updating of tasks in a generic high level manner. This system is to accept an external communication, such as an email, and generate a task instance for the work asked for in the communication. From this instance, the necessary links, documentation, and other information of the task would be put into a Task State, which would be added to a table of task states. From here the task instance would send it’s ID to the task scheduler which would use an algorithm to determine which task to be performed next. Once a task is chosen, the task instance is loaded into the Work Module wherein the specific tasks and subtasks are performed and the Task Instance updated. Updates to the instance could generate a communication going back to the originating sources describing the updates and task status.
This idea has similarities to how operating systems worked and it did not originally include any systems engineering concepts other than finding a way to tangibly manage complexity and the inevitable communication/organizational overhead that complexity brings.
