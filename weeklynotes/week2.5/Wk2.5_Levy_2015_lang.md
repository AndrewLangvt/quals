#Week 3- Lang

## Paper- Levy et al. 2015

### Reasoning:
Levy et al. recognized the shallow understanding, at the present time, of the mechanisms underlying adaptation by mutation, specifically in bacterial cells (pathogens, cancer, drug resistance). The genetic underpinnings driving selective pressure acting upon genetic drift to result in a beneficial was not well characterized. To bridge this gap, they decided to look at all mutations occurring in populations of 100,000,000 cells, tracking 25K lineages over 168 generations. 

### Methods:
By labeling a clonal yeast population with 500k DNA barcodes and growing this population out in two replicates to 168 generations, researchers were able to uniquely track the growth and mutation rate of individual lineages.  By introducing bottlenecks every 8 generations, they were able to identify those lineages that were flourishing and deemed beneficial lineages (adaptive mutation), and those that were maintaining the status quo, or were declining, and deemed neutral lineages (neutral adaptations). The rate at which a lineage grew is a measure of the fitness effect (*s*), and they were able to extrapolate back to deterine the time (*t*) that this mutation was established. To validate their findings of *s* and *t*, analysis of a simulated dataset was performed, which matched very well to the inferred values of both replicates E1 and E2.   

discuss the math behind calculating the probability that a mutation is adaptive, rather than simply genetic drift



### Findings:

In this strain of yeast benefical mutations with a fitness benefit greater than 5% occurr at 1x10^-6 per cell generation. By determining the mutation rate in non-repeat regions, the researchers were able to then calculate that mutations in ~0.04% of the genome (5k bases) confer a beneficial fitness effect >5%. Most mutation benefits fell between 2 and 5% advantage. 

Beneficial mutations of greater fitness effect, will have a longer time "allowed" to establish before it begins to decline and the population does not grow exponentially. If the mean fitness surpasses the fitness advantage presented by the mutation, it will not establish. Mutations of smaller benefit must drift to higher numbers to establish, and is overtaken by the mean fitness of the population faster than mutations of larger benefit. Although these mutations are beneficial, due to their smaller effect, are rapidly outcompeted and unlikely have significant effect upon population dynamics. 

They found that in the earlier generations (<72), the mean fitness is driven by smaller benefit mutations. As generation time progresses, so does the likelihood of larger benefit mutations having arisen, which quickly outcompete mutations with smaller *s*. These larger benefit mutations are rare, yet show larger effect once established. 

### Importance:

By tracking a large number of lineages over generations, the researchers were able to characterize the effects of large and small fitness benefit mutations over time, and also identify many small-benefit mutations that otherwise go unnoticed when looking at the end state of the population.  The authors suggest that while an emphasis is placed on high frequency mutations (usu from high benefit mutation event) in pathogenic or cancer research, the large number of low frequency mutations (smaller benefit mutation event) can likely play as important of a role in disease progression and drug resistance.  The use of DNA barcode tracking to trace lineages, one can generate a much deeper understanding of the evolutionary mechanisms underlying population growth.

Fig 3b shows the interpaly between individual fitness and community fitness as a result of small vs larger mutation.  The smaller mutations will continue to rise until the mean fitness of the population surpasses individual fitness, and get outcompeted. Less than 2% of mutations will actually lead to true fixation and evolution. 

Many small mutations vs single large mutation- large mutation events will drive evolutionary change, but identifying how you truly arrived there will not be visualized because the smaller mutations can go unnoticed and easily are outcompeted by mutations of large effect. Large benefit mutations are inconsequential if they are not larger than the mean fitness, otherwise they get washed away by genetic drift.