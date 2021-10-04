The "resource sharing" parameter refers to the elements that are shared between MB, MP and MI (with respect to MONICA model, see "organization" parameter for more details). 

The analysis is for possible sharing among physical and logical resources of MB, MP and MI, as shown in the figure below:

![resource-sharing](https://i.imgur.com/0JKfVvN.png)


The possible values are the following:

-MB-MI : Processing Resources

-MB-MI : Instruction Memory

-MB-MI : Data Memory

-MB-MI : No Sharing

-MB-MP : Processing Resources

-MB-MP : Instruction Memory

-MB-MP : Data Memory

-MB-MP : No Sharing

-MI-MP : Processing Resources

-MI-MP : Instruction Memory

-MI-MP : Data Memory

-MI-MP : No Sharing

-Not Applicable: when used in Find Mode, it means that the requirement of this parameter is not applicable for the considered monitoring requirements. Therefore, when searching for on-chip monitoring systems satisfying those monitoring requirements, only the on-chip monitoring systems with this parameter set as "Not Applicable" will be considered. When used in Insert Mode, it means that this parameter is not applicable for the described on-chip monitoring system.

-Not Declared: when used in Find Mode, it means that the requirement of this parameter is not declared for the considered monitoring requirements. Therefore, when searching for on-chip monitoring systems satisfying those monitoring requirements, this parameter will not be kept into account. When used in Insert Mode, it means that this parameter is not declared for the described on-chip monitoring system.

