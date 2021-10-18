The "synchronization" parameter refers to the required synchronization among elements that implement MI, MB, MP, in order to correctly perform the monitoring action.

The possible values are the following ones:

- Automatic: the synchronization does not require actions, as it is guaranteed by the use of the monitoring system itself: this is the case, for example, of a user space operating system application monitored with the technique of source level code instrumentation, where the compilation process ensures the correct synchronization among MB, MI and MP.

- Manual: a hardware/software custom component is required to guarantee the synchronization.

-Not Applicable: when used in Find Mode, it means that the requirement of this parameter is not applicable for the considered monitoring requirements. Therefore, when searching for on-chip monitoring systems satisfying those monitoring requirements, only the on-chip monitoring systems with this parameter set as "Not Applicable" will be considered. When used in Insert Mode, it means that this parameter is not applicable for the described on-chip monitoring system.

-Not Declared: when used in Find Mode, it means that the requirement of this parameter is not declared for the considered monitoring requirements. Therefore, when searching for on-chip monitoring systems satisfying those monitoring requirements, this parameter will not be kept into account. When used in Insert Mode, it means that this parameter is not declared for the described on-chip monitoring system.
