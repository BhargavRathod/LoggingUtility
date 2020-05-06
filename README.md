# Logging Utility
This Utility provide log features to track all execution of complex codes, modules or projects. This can be easier way to debug, find track or find bugs or issues.

 # What is this Logger module?
 This is implementation of Logger Utility for C# Environment.
 This is just class file named 'Logger.cs'.

 # What is need of this Logger Class?
 This class helps to get track of all the logs during excecution of any module(s)/project(s).
 While excecution of complex code, it always difficult to debug for any bug(s) and issue(s) or keeping track of excecution.
 All the Exception related info as well as all the messages will be available in which User/Programmer(s) want to track

 # How to use this Logger Class?
 Please follow below steps:
     1. Change namespace of this class and change to <your_module_namespace>.
     2. Provide file path in which file will be created, for that assign variables.
         e.g. 
             #region Variable Declaration
             static string logPath = @"C:\User\Desktop\"; <provide_your_path_in_your_module>.
             static string logFileName = "logs_dd_mm_yyyy.log"; <provide_your_log_file_name_in_your_module>.
             #endregion
     3. Write Log statement in your code to track details.
           e.g.
               Logger.LogFileWrite("Main method Started", logPath);
               Logger.LogFileWrite("Variable value: " + "value1", logPath);
               Logger.LogFileWrite("Main method Ended", logPath);
               Logger.LogFileWrite("Variable value after method called: " + "value2", logPath);
     4. Write Log statement with Exception in catch block of your code.
           e.g.
               Logger.Log(exception.Message, logPath);
               Logger.Log(exception.ToString(), logPath);
               Logger.Log("Exception caught in demo catch block :: ", logPath);
     5. Observe the file !

 # Can anyone modify this Class?
 Ofcourse, Anyone can modify for custom logics.
 This is just contains basic functionalities of logging.

 # Is this Industrial Standard?
 No, But Industries can use this as their standard.
 This is demostration of the one way in direction to utility.

 # Version
  1.0

 # Author
  Bhargav Rathod, [bhargavrathod98@gmail.com]

 # Limitations
   1. Only works with C# code and .Net Environment.
   2. Work as same logic, Not Intelligent

 # Future Extention
   1. Generic for all Language
   2. Smart Features
   3. Retrivig information of server, machine name, logged in user, dependencies and details
      (in case of multiple user working on servers)
     
 # Contact Details
   For any of your concern you can reach out to me.
       Bhargav Rathod
       bhargavrathod98@gmail.com
       bhargavrathod98@yahoo.com
       India
     
 # Remarks
   Happy Coding :)

