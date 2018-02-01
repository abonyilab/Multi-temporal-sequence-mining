# Multi-temporal sequence mining
The multi-temporal sequence mining algorithm for mining frequently occurring event sequences.

The algorithm was created for alarm management purposes to detect frequnetly occurring patterns in large alarm databases.

## Sequence Mining based Alarm Suppression

Despite the high-pace improvement of industrial process automation, the management of abnormal events still requires human actions. Alarm systems are becoming crucial in providing situation-specific information to the decreasing number of operators. The key role of an alarm management system is to ensure that only the currently significant alarms are annunciated. The design of alarm suppression rules requires the systematic analysis of the process and its control system. We give an overview of the recently developed data-driven techniques and show that the widely applied correlation based methods utilize a static view of the system. To provide more insight into the process dynamics and represent the temporal relationships among faults, control actions and process variables we propose of a multi-temporal sequence mining based algorithm. The methodology starts with the generation of frequent temporal patterns of the alarm signals. We transform the multi-temporal sequences into Bayes classifiers. The obtained association rules can be used to define alarm suppression rules. We analyze the dataset of a laboratory-scale water treatment testbed to illustrate that multi-temporal sequences are applicable for the description of operation patterns. We extended the benchmark simulator of a vinyl acetate production technology to generate easily reproducible results and stimulate the development of alarm management algorithms. The results of detailed sensitivity analyses confirm the benefits of the application of temporal alarm suppression rules which are reflecting the dynamical behaviour of the process.

The files are the supplementary materials of our paper published in IEEE Access, 2018
For the extended simulator of the vinyl acetate production technology and the source codes of the Bayes’ theorem-based evaluation of sequences see: https://github.com/abonyilab/VACsimulator 

Gyula Dorgo, Janos Abonyi PhD

MTA-PE Lendület Complex Systems Monitoring Research Group, Department of Process Engineering, University of Pannonia Department of Process Engineering, University of Pannonia, Egyetem str, 10. POB 158, Veszprém, H-8200, Hungary janos@abonyilab.com
