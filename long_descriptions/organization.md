The "organization" parameter refers to the relation, in terms of implementation strategy, between the monitored application and the on-chip monitoring system. The relation is expressed through the MONICA mode. 

The MONICA model abstracts the generic monitoring process with three parts: a Monitored Behaviour, a Monitoring Infrastructure, and a Monitoring Processor. They are detailed in the following (and shown in the picture below):

-Monitored Behaviour (MB) - MB represents the tasks, executing on a target system, that have to be monitored with an on-chip monitoring system. Suppose that a system is composed of multiple tasks (T1, T2, ..., TN): in case only the first three of them shall be monitored, MB is represented by T1, T2 and T3. MB can be implemented in hardware (executed by dedicated and not reprogrammable hardware architectures) and software (executed by a programmable processor).

-Monitoring Infrastructure (MI) - MI represents all the necessary mechanisms, part of an on-chip monitoring systems, able to extract raw information. The mechanisms that are part of the monitoring infrastructure can be implemented in software or hardware: a software mechanism is a mechanism that, in order to perform the raw information extraction, uses the resources of the target under analysis. A hardware mechanism, on the other hand, is a mechanism that, in order to perform the raw information extraction, has a dedicated hardware architecture.

-Monitoring Processor (MP) - MP represents all the necessary tasks, part of an on-chip monitoring system, that, by using raw information as inputs, apply some algorithms to provide monitoring information, organized in metrics. MP can be implemented in hardware or software.

![organization](https://i.imgur.com/nJbR3yb.png)

MB, MI, and MP have all two possible implementations: hardware (HW) or software (SW). By considering the implementation of MB-MI-MP, it is possible to classify a monitoring process, also allowing grouping on-chip monitoring systems accordingly with such a classification.
The possible values of the monitoring organization parameter are expressed with a triple (MB, MI, MP), indicating the type of implementation:

-SW-SW-SW

-SW-SW-HW

-SW-HW-SW

-SW-HW-HW

-HW-SW-SW

-HW-SW-HW

-HW-HW-SW

-HW-HW-HW

-Not Applicable: when used in Find Mode, it means that the requirement of this parameter is not applicable for the considered monitoring requirements. Therefore, when searching for on-chip monitoring systems satisfying those monitoring requirements, only the on-chip monitoring systems with this parameter set as "Not Applicable" will be considered. When used in Insert Mode, it means that this parameter is not applicable for the described on-chip monitoring system.

-Not Declared: when used in Find Mode, it means that the requirement of this parameter is not declared for the considered monitoring requirements. Therefore, when searching for on-chip monitoring systems satisfying those monitoring requirements, this parameter will not be kept into account. When used in Insert Mode, it means that this parameter is not declared for the described on-chip monitoring system.

For example, the triple (SW, HW, SW) shows that the MB is a software running on a programmable processor, while MI is implemented with dedicated hardware elements. MP, on the other hand, is again a software. The triple can describe a hardware monitoring system that extracts information about a software workload execution without introducing software overhead, and that aggregate these information, for example to get an estimation of worst-case execution time, using a software executing on the same target.
