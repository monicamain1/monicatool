The "detection latency" parameter refers to the elapsed time between the instant in which the event instance to be observed happens and the instant where the monitoring information is available.

The set of possible values are the followingones:

- unknown: means that it is not possible to evaluate such a parameter

- value (cc): is a number or a range related to the detection latency value related to clock cycles.

- Not Applicable: when used in Find Mode, it means that the requirement of this parameter is not applicable for the considered monitoring requirements. Therefore, when searching for on-chip monitoring systems satisfying those monitoring requirements, only the on-chip monitoring systems with this parameter set as "Not Applicable" will be considered. When used in Insert Mode, it means that this parameter is not applicable for the described on-chip monitoring system.

- Not Declared: when used in Find Mode, it means that the requirement of this parameter is not declared for the considered monitoring requirements. Therefore, when searching for on-chip monitoring systems satisfying those monitoring requirements, this parameter will not be kept into account. When used in Insert Mode, it means that this parameter is not declared for the described on-chip monitoring system.

For example: detection latency < 4 cc; detection latency in the range 10-50 cc.
