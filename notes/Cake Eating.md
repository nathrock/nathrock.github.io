
# Cake eating problem

A cake eater is endowed with a cake that never spoils. They choose a piece of cake, $c_t$, and the remaining size of the cake, $k_t$, to maximize present value lifetime utility, keeping in mind that the cake is finite.

$$\max_{c_t, k_t} \sum_{j=0}^\infty \beta^j c_{t+j}$$

$$ c_t + k_t = k_{t-1}$$

where they start the day with cake, $k_{t-1}$. Note the optimal piece/size of cake will be independent of time since the planning horizon is infinite (i.e., always the same). Suppose the cake eater knew they would die at some future time, then how long they are from death would influence how much cake they eat. If they were one day away from dying, they might eat the whole cake. If they lived another 100 years, then they would only eat a sliver. Since their planning horizon is aways the same, then the only necessary information to solve the problem is the initial cake, $k_{t-1}$ (i.e., the state variable) and their discount factor, $\beta$ (i.e., the parameter). 

# Solution

Plug the resource constraint into the objective function.