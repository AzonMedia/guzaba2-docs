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
- fixed permission check in ExecutorMiddleware - it was possible to execute the _init() method (if there was such in the controller) even if there is no permission to execute the requested controller method
- changes in ActiveRecordDefaultController:
    - ConfigurationException is thrown if a route overwrites an existing route
    - added 'allow_controller_overwriting_activerecord_route' config option - when enabled it is allowed a ControllerInterface route to overwrite a route defined from ActiveRecordInterface
- added check are all public dynamic methods on the controllers used in the routing map
- added meta data overloading on ActiveRecord ($Object->meta_object_create_microtime)
- added readonly ActiveRecord::get_from_record()
