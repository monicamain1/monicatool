In order to describe a monitoring action, an abstraction based on three parameters is used, as can be shown in the figure below.
![Global-Monitor](https://i.imgur.com/UQKC8iH.png)

The parameters are MB-MI-MP (Monitored Behaviour - Monitoring Infrastructure - Monitoring Processor), and they are detailed in the following:

- Monitored Behaviour (MB) - MB represents the tasks that have to be monitored. Suppose that a system is composed of multiple tasks (T1, T2, ..., TN): in case only the first three of them shall be monitored, MB is represented by T1, T2 and T3. When implemented on a hardware/software platform, MB constitutes the UUM. MB implemented in hardware and software are indicated, respectively, with the notations: MB-<HW>, MB-<SW>. It is worth noting that we refer to tasks implemented in software as tasks executed by a programmable processor, while we refer to tasks executed in hardware as tasks executed by dedicated (and not reprogrammable) hardware architectures.
- Monitoring Infrastructure (MI) - MI represents all the necessary mechanisms for extracting raw information from a UUM. The mechanisms that are part of the monitoring infrastructure can be implemented in software or hardware: a software mechanism is a mechanism that, in order to perform the raw information extraction from the UUM, uses the resources of the UUM itself. A hardware mechanism, on the other hand, is a mechanism that, in order to perform the raw information extraction, has a dedicated hardware architecture. MI completely implemented in hardware and software are indicated, respectively, with the notations: MI-<HW>, MI-<SW>.
- Monitoring Processor (MP) - MP represents those elements that, by using raw information as inputs, apply some algorithms to provide monitoring information, calculating some metrics. Specifically, MP can be viewed as a number of tasks that can be implemented in hardware or software, indicated, respectively, with the notations: MP-<HW>, MP-<SW>.



By considering the implementation of MB-MI-MP, it is possible to classify several monitoring actions and to group monitoring systems accordingly with such a classification.
The possible values of the monitoring organization parameter are expressed with a triple (MB, MI, MP), indicating the type of implementation. 
For example, the triple (SW, HW, SW)  shows that the MB is a software running on a programmable processor, while MI is implemented with dedicated hardware elements. MP, on the other hand, is again a software. For instance, the triple (SW, HW, SW) can describe a hardware monitoring system that extracts information about a software workload execution without introducing software overhead, and that manages this information to obtain useful one using software running on a host computer.
