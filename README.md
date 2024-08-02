1-  Logging is a powerful aid for understanding and debugging a program’s run-time behavior. Logs capture and persist the important data and make it available for analysis at 
any point in time. This information can be used for debugging, performance monitoring, and troubleshooting. Logging is essential for understanding how software behaves in 
different environments and diagnosing issues. 

2-Logging is essential for various reasons: 
    -They provide invaluable insights into how your application behaves under different circumstances, which can be crucial for identifying
      and diagnosing issues
    -Also help in understanding the user’s journey through your application, thereby aiding in enhancing user experience.
    -They help identify unusual activities that could potentially signal a security breach, and can be used to investigate and respond to security branches when they occur.

3-Logging levels help classify and control the importance and verbosity of log messages in your application. They indicate the severity of the events being logged and allow 
  developers to filter log output based on what’s relevant at any given time.
  Levels are hierarchical, meaning that if you set the logging level to WARN, messages with levels ERROR and WARN will be logged, but INFO and DEBUG messages will not. 
  This hierarchy helps in controlling the verbosity of log outputs:
    ERROR Use for exceptions or problems that need fixing.
    WARN Use for potential issues that don’t stop the application but might need attention.
    INFO Use for general updates on the application's state or workflow.
    DEBUG Use for detailed, diagnostic information that helps trace the execution flow or understand the system state.
    TRACE Use for the most detailed tracing of application behavior, typically for very fine-grained debugging.
