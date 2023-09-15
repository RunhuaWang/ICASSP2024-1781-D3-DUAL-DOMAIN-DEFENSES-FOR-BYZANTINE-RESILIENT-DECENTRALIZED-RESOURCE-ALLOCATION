Algorithms：
Resilient algorithms：DGD+AGG(CTM,IOS,SCC), BREDA(CTM)
Non-resilient algorithms：DGD, DRA

The number of agents：100
The number of honest agents：94       The number of Byzantine agents：6

Network：random 

Total resource constraint：5000 
Local resource constriant：[0,100]

Cost function：a*(agent_resource_quantity-b)^{2}
a：uniform distribution U[1, 2]
b：gaussian distribution N[2, 0.6^2]

Byzantine attack：Bzantine agents send false dual variables to honest agents
