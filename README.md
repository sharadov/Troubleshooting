# Troubleshooting
Commands to troubleshoot system performance.
These comamnds help you deep dive into a hosts with performance issues.
They will give you a high level view of system resource usage and running processes.
Look for errors, saturation metrics and resource utilization.
Saturation is where a resource has more load than it can handle, and can be exposed either as the length of a request queue, or time spent waiting.
Some of these commands require the sysstat package installed. The metrics these commands expose will help you complete some of the USE Method: a methodology for locating performance bottlenecks. This involves checking utilization, saturation, and error metrics for all resources (CPUs, memory, disks, e.t.c.). Also pay attention to when you have checked and exonerated a resource, as by process of elimination this narrows the targets to study, and directs any follow on investigation.
