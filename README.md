# VMHopper
A project which analyzes the loads on virtual machine due to some running application and predicts when to balance load by switching application to another machine. The machine hosting the application run another deamon process which moniters the state of machine and the resources utilization and transmits this information to a Controller machine. Controller collects data, predicts future resource usage and determines when to switch application to another machine.

Currently, the controller uses AGILE [1] to perform data analytics.

## Reference
[1] Nguyen, H., Shen, Z., Gu, X., Subbiah, S. and Wilkes, J., 2013, June. AGILE: Elastic Distributed Resource Scaling for Infrastructure-as-a-Service. In ICAC (Vol. 13, pp. 69-82).
