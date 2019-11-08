# TaskMaster
Control the execution flow of a set of tasks. (Scala) 

   I wrote this as a framework for a project that executed sets of user selected tasks.   There are two main parts TaskMasters and TaskSteps.   TaskMasters have some of their own properties cheif among them is a list of TaskSteps.
   
   When a task in the task list fails the task chain is broken.
  
   I had this connected to a Java/Swing frontend that would build itself based on a list of TaskMasters.  Users could select tasks via the GUI.  I don't know if it would makes sense to include that here.
