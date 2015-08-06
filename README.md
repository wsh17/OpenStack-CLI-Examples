# OpenStack-CLI-Examples

This repository contains HOW-TO examples for the OpenStack CLI.  This is done under bash under lunix. 
# How How to create and configure Host Aggregates in your COPC Eenvironment

Host aggregates can be used to sub-divide an availability zone in to multiple pieces. Then 
you can, thru the use of flavors, control who runs within a particular aggregate.  The reasons
you may want to do this maybe you need to seperate physically two groups, or you may have
a faster or slower set of hypervisor nodes you would like to pool together so you could
control where VM's actually run. I am sure there are other use cases for the feature as 
well, below we will describe how to setup aggregates. 
