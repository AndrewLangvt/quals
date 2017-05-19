#Week 
##Paper Casillas & Barbadilla, 2016

**Table 1 is an awesome compilation of many symbols and their meanings in evolutionary formulas.**

Intitially, much of the field was mostly general and theoretical.  Surprisingly, many of the fundamental forces initially described during this time (natural selection, mutation, recombination, genetic drift, and gene flux) are still essential today in evaluating the population genetic basis of evolution. 

During the beginning stages two hypotheses arose to explain natural selections effects on evolution. 

- Classical hypothesis supported the role of natural selection in purging the population of most genetic variation, predicting that most loci are homozygous for the WT allele
- Balance hypothesis postulated that natural selection actively maintained high levels of genetic diversity in populations

**Allozyme Era**
Beginning analyses observed allozymes, different allele variants of the same proteins, via gel electrophoresis. In observing allozymes across many taxa, reserachers observed less variation that was expected if genetic variation were a function of population size (Lesintons Paradox). Gel electrophoresis was quickly deemed incapable of having the power to assess the true foundational level from which evolution is driven- DNA.  From here, sequencing began and researchers quickly identified a great deal of variation

**Nucleotide Sequence Era**
Researchers found that regions of the genome with low recombination have very low levels of genetic variability.  Further, levels of divergence were shown to be independent of local recombination rates, and thus the correlation between recombination rate and levels of polymorphism was attributed to the fixation of advantageous mutations and the associated hitchhiking effect. In 1983, Kreitman sequenced *D. melanogaster* and identified a single SNP resulting in the two allozyme variations, and 42 others that were silent. This revealed a great deal of variation within a population, supporting the view that most amino acid changes are deleterious. 

We now know that autosomal nucleotide diversity varies by 2-3 levels of magnitude, reproductive strategy is strongly correlated to genetic diversity of species, and are able to observe haplotypes directly in *D. melanogaster* by extraction with balancers. We also know that nucleotide sites are not independent of one another, with alleles clustered into blocks of 100-150bp to 2kb (*Drosophila*) to >100kb (Humans). This all, while fascinating, still only characterized discrete genes, failing to provide unbiased perspective on the entire genome. 

**Genome Era**

*Variation* -- The emergence of NGS methods has provided the field with rapidly filling databases of genomic sequences from many taxa.  The issue has become not how to analyze the data as much of the statistical methods for measuring genetic variation are the same, but how to preprocess and manage the data (assembly, mapping, read representation of whole genome, noisy sequencing, missing nucleotides, and sequencing errors). Methods have been developed to cut costs (whole-genome sequencing of pools of individuals, exome sequencing, and Restriction site-associated DNA sequencing).  Technological advances have revolutionized the field, yet we still remain focused on characterizing inter-and intra-population genomic variation.

*Recombination* -- Understanding recombination rates is still crucial to our understanding of linked selection.  Programs such as LDhat assume a neutrally evolving population at a constant size to estimate recombination rates. LDhelmet was then developed to account for effects of natural selection. Using recombinant advanced intercross lines (RAIL) flies, a study in 2012 was able to identify *hot* and *cold spots* of recombination along chromosomes, while gene conversion exhibited a more uniform distribution. 	Broad-scale maps present an overview of distribution of recombination along chromosome arms, while fine-scale recombination rate varies across genomes, along chromosome arms, and within populations. -- "Fine-scale analyses relating selection and linkage implicitly assume that the recombination map is a fixed genome property. Consequently, linked selection could be obscured if polymorphism from one species is analyzed with recombination rates calculated from a different species."

**Neutral Therory**

- Kimura - the bulk of existing polymorphisms and fixed differences between species are selectively neutral and functionally equivalent. The frequency dynamics of neutral variants in the population is determined by the rate of mutation and random genetic drift (intrapopulation polymorphism is just a random walk of variants in their process to fixation or loss.)
- Ohta - nearly neutral mutations are mostly eliminated by natural selection in large populations, but that a substantial fraction of them behave as effectively neutral and are randomly fixed in small populations. As a result of this process, the strength of purifying selection acting on slightly deleterious mutations and the generation time effect compensate, and protein evolution is fairly insensitive to generation time.

	Ohta then developed a model including both slightly deleterious and slightly beneficial mutations (Ne- effective population size s- selection coefficient)
	- Mutations w/fitness effects smaller than 1/Ne- effectively neutral
		- at the mercy of genetic drift 
	- Mutations w/fitness effects ~1/Ne- nearly neutral
		- combination of natural selection and drift
	- Mutations w/fitness effects > 1/10Ne - strongly deleterious or advantageous
		- natural selection

*In a small population, range from -1/Ne to 1/Ne is greater than a large population, meaning there are more neutral mutations.  In a larger population, most mutations are subject to natural selection of some sort. The range |Nes| = 1 delimitates the decisive borderline: if Nes is <1, genetic drift dominates; if it is <1, selection dictates the fate of mutations.*
 
Now, rather than characterizing fitness effects as advantageous, neutral, or deleterious, we have adopted a distribution of fitness effects continuum.  Where the mutation falls on this DFE continuum plays a direct role in the rate of molecular evolution. 

The coalescence theory seems like an afterthought... 

**Genetic hitchiking and selective sweep** -- neutral alleles that are tightly linked to a favorable mutation rise to fixation with the mutation, resulting in decreased linked genetic variation at this region.  

**Genetic Draft** -- similar to drift, except the effect is increased with population size.  As *Ne* increases, drift is less effective at removing alleles and variation increases. In parallele, more mutations occur (more adaptive ones as well), meaning selection has more loci upon which to act which means more hitchhiking. Once *Ne* is large enough, genetic draft superscedes drift and genetic variation is no longer sensitive to population size. Draft is more prominent in regions with lower recombination as it leaves a trace in a larger region. 

**Background Selection (BGS)** -- essentially the reverse of hitchiking.  A region of genetic variation is lost due to purifying selection of a linked deleterious allele

**Through analysis of more recent genomic data, researchers have determined that "natural selection has a greater impact on the levels of linked neutral variation in species with large *Nc* than those with small *Nc*."**

Michael Lynch-- "Not only genetic variation, but also the very complexity of the genome is a consequence of population genetic processes. In very large populations, selection is so efficient that genomes cannot leave their adaptive peak to investigate new landscapes. In contrast, in small eukaryotic populations, inefficient selection allows the genome to accumulate slightly deleterious mutations that will eventually be the source for adaptive innovations. Thus, the complexity of the eukaryotic genome would be initiated by nonadaptive processes, which in turn would provide a new substrate to secondarily build novel forms of organismal complexity through the action of natural selection."

Recent study has shown polymorphic rates to be:

*$\pi$* synonymous > *$\pi$* intron > *$\pi$* intergenic > *$\pi$* pUTR > *$\pi$* pnonsynonymous

natural selection acts differently on insertions and deletions, with stronger purifying selection on deletions- consistent with the mutational equilibrium theory for genome size evolution (Petrov 2002), where optimal genome size is maintained by purifying selection on small deletions and less selection on long insertions, compensating for sequence loss.

**Transposable Elements**

*Transposition selection balance model*

- suggests an equilibrium between an increase in copy number by a constant transposition rate and the elimination of TE copies from the population by purifying selection 

*Burst transposition model*

- Assumes some families can experience periods of transposition bursts (purifying selection not so intense), such that recently active families show low population frequencies compared to long-time inactive families with fixed copies, resulting in TE age determining TE frequency to a large extent.

**Adaptive Evolution** -- Nucleotide variation shows substantial evidence for positive selection (adaptive fixation) in autosomal noncentromeric regions and in the X chromosome. Even some TE insertions have shown adaptive effects (addition of reg regions). 

**Faster-X hypothesis** -- X chromosomes evolve more rapidly than autosomes because X-linked genes with favorable mu- tations that are recessive or partially recessive are more exposed to selection in hemizygous males than similar genes on autosomes.-- also, the effective recombination rate is ~1.8-fold greater on the X chromosome than autosomes

Recombination itself, rather than any other factor, seems to be the main process determining the pattern of nucleotide diversity along the genome.

This evidence can be interpreted as the vindica- tion of the selective hitchhiking hypothesis vs. the (nearly) neutral hypothesis (Hahn 2008), such that the positive cor- relation between polymorphism and recombination reflects the footprint of natural selection in the genome. The degree to which linked selective sweeps reduce genetic diversity de- pends primarily on the rate of sweeps per genetic map length

**HRi** -- If an advantageous mutations A arises in one individual, while an advantageous mutation B arises in another, selection will be acting upon both, and they will be in competition.  Without recombination, fixation of A and B would only occurr upon a mutation of the second gene in either individual.  With recombination, AB would rise to fixation much faster. This process tends to slow down evolution by natural selection due to the introduction of competition. 


How did introns evolve function? intron first or function resulting in intron?

this paper doesnt address the different environments at all
