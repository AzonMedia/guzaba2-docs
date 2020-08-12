# What is new in v0.0.6 (WIP)

- added events in:
  - ExecutorMiddleware::execute_controller_method():
    - _before_execute_controller_method & _after_execute_controller_method
    - _before_execute_controller_method_check_permissions & _after_execute_controller_method_check_permissions
  - QueueRequestHandler::handle():
    - _before_middleware_process & _after_middleware_process
- changes and fixes in ActiveRecordDefaultRoutingMap
    - added checks for route overwriting (if the controller is the same overwriting is acceptable)
    - fixed route merge - it is now possible to merge matching routes if they define different methods
    - improved route metadata

