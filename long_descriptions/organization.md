The "organization" parameter refers to the relation, in terms of implementation strategy, between the monitored application and the on-chip monitoring system. The relation is expressed through the MONICA mode. 

The MONICA model abstracts the generic monitoring process with three parts: a Monitored Behaviour, a Monitoring Infrastructure, and a Monitoring Processor. They are detailed in the following:

-Monitored Behaviour (MB) - MB represents the tasks that have to be monitored. Suppose that a system is composed of multiple tasks (T1, T2, ..., TN): in case only the first three of them shall be monitored, MB is represented by T1, T2 and T3. MB implemented in hardware (executed by dedicated and not reprogrammable hardware architectures) and software (executed by a programmable processor).
  
