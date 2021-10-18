The "Type of Physical Implementation" (TPI) parameter refers to the physical implementation of the UUM. In other words, TPI refers to the type of physical platform where the monitoring system can perform the monitoring action.

The possible values are the following ones:

- Completely fixed (CF): this TPI refers to hardwired implementations. They can be, for example, a hardwired GPP (such as Intel ATOM) or a hardwired SPP without any available reconfigurable logic.

- Reconfigurable (RCF): this TPI refers to reconfigurable logic based implementations, such as implementations on FPGAs.

- Partially fixed (PF): this TPI represents a mix of the first two, such as the case of Xilinx Zynq7000 where there is a dual-core hardwired processor with an FPGA in the same chip.

- Not Applicable: when used in Find Mode, it means that the requirement of this parameter is not applicable for the considered monitoring requirements. Therefore, when searching for on-chip monitoring systems satisfying those monitoring requirements, only the on-chip monitoring systems with this parameter set as "Not Applicable" will be considered. When used in Insert Mode, it means that this parameter is not applicable for the described on-chip monitoring system.

- Not Declared: when used in Find Mode, it means that the requirement of this parameter is not declared for the considered monitoring requirements. Therefore, when searching for on-chip monitoring systems satisfying those monitoring requirements, this parameter will not be kept into account. When used in Insert Mode, it means that this parameter is not declared for the described on-chip monitoring system.
