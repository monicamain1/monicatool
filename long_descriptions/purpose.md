The "purpose" parameter refers to the goal of the monitoring process performed by the on-chip monitoring system.

Its value can be chosen among multiple categories:

-Debugging - A monitor for debugging allows to observe a component (hardware or software) at runtime in its target environment, in order to find and eliminate bugs. This kind of on-chip monitor spans from the support to classical debugging actions during the development cycle of a system, to support to runtime validation and verification that can be part also of the system life-cycle.

-Performance - A monitor for performance observes the runtime behavior of a system, collecting different statistics, which help to evaluate system performance or to optimize system weaknesses. In the last years, these kind of on-chip monitors have been applied also to perform a worst-case execution time analysis.

-Quality of Service (QoS) - A Quality of Service (QoS) monitor observes, at runtime, the interconnection among different IP components, with the goal of supporting requirements guaranteeing from the point of view of bandwidth and latency.

-Power, Energy and Temperature - A monitor for power provides a measure of the power dissipation of a component, strictly related to the energy and the temperature, for which dedicated on-chip monitors can also exist.

-Fault-tolerance and Reliability - The fault-tolerance and the reliability of a system involve multiple abstraction layers, from application to circuit, thus an on-chip monitoring system can support on ensuring them. In particular, on-chip monitoring systems can observe the system state and identify faults, in order to trigger countermeasures, or can provide information to build a system model used for reliability analysis.

- Security - Monitoring systems for security support on checking that the system performs operations that was intended to do. This can be done by checking the system state against a model, verifying some predefined signatures, or using filtering structures that allow only some processes to work.

The possible values of this parameter are not mutually exclusive.
