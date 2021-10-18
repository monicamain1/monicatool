The "techniques" parameter refers to the technique employed to perform a monitoring action.

The parameter can assume the following values:

- Source Level Code Instrumentation: this type of instrumentation is related to the addition of source code directives within the source code of the monitored application, in order to extract event instances.

- Binary Level Code Instrumentation: this type of instrumentation is related to the addition of directives at binary level, in order to extract event instances. This can be statically performed (Static Binary Level Code Instrumentation) or dynamically performed (Dynamic Binary Level Code Instrumentation).

- Sampling:  a monitoring system that adopts the sampling approach wraps itself around the execution of an application, taking control of the program flow, and then pausing the execution at specific points to record the current state of the system (such as reading the program counter register).

- Hardware Performance Counters: they represent hardware elements composed of a counting register with a control system, able to collect some metrics related to performance events.

- Performance Monitoring Units: they are dedicated hardware elements built inside a processor to measure its performance parameters. The difference with a hardware performance counter is that a performance monitoring unit is not necessarily based on events counting operations.

- Hardware Trace Buffers: they are dedicated hardware elements able to trace an application execution, and either store that traces or output them.

- Custom: the system uses a custom technique to perform the monitoring action.

-Not Applicable: when used in Find Mode, it means that the requirement of this parameter is not applicable for the considered monitoring requirements. Therefore, when searching for on-chip monitoring systems satisfying those monitoring requirements, only the on-chip monitoring systems with this parameter set as "Not Applicable" will be considered. When used in Insert Mode, it means that this parameter is not applicable for the described on-chip monitoring system.

-Not Declared: when used in Find Mode, it means that the requirement of this parameter is not declared for the considered monitoring requirements. Therefore, when searching for on-chip monitoring systems satisfying those monitoring requirements, this parameter will not be kept into account. When used in Insert Mode, it means that this parameter is not declared for the described on-chip monitoring system.
