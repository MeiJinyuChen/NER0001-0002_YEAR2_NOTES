
## Summary
Tsien et al. have produced a mouse strain CA1-restricted NMDAR1 gene knock out. 

 Mutant mice:
 - Grow into adulthood without obvious abnormalities
 - Show impaired spatial memory but unimpaired nonspatial learning
 - Lack NMDA receptor-mediated synaptic currents
 - Lack LTP in CA1 synapses
         ↓
 Strong support for hypothesis:
 NMDAR-mediated LTP in CA1 is crucially involved in the formation of certain types of memory


## Research background
### synaptic plasticity and memory
- Hebb: Memory is stored through changes in synaptic strength between neurons.
- Hebb rule = correlated activity: When the presynaptic and the postsynaptic neurons are active simultaneously, their connections become strengthened.
### role of NMDARs
- NMDARs are crucial for LTP induction:
    - act as coincidence detectors: require both presynaptic activity (glutamate release) and postsynaptic activity (depolarization that releases Mg<sup>2+ </sup> block) as a condition for channel opening.
-  When activated, they allow Ca²⁺ influx, triggering biochemical cascades that results in plasticity changes.
- The induction of LTP requires the activation of NMDARs.
### previous studies
1. Morris et al.
   Rats that received infusion of AP5 into the hippocampus were deficient in performing a spatial memeory task in Morris water maze.
   #### limitations: 
   Target of AP5 infusion is not restricted to the hippocampus. It may also impair the spatial-memory-related ability of other neocortical regions.
2. Mice with the knockout of a gene encoding a downstream component of activated NMDRs display impaired LTP in CA1 and a deficit in spatial learning.
   #### limitations:
   Genes are deleted in all cells. The impairement in spatial memory may result from developmental defects.

## Method

### 1. Cre/loxP CA1-specific NMDAR1 knockout
Modify the gene knockout method → Exploit the Cre/loxP recombination system (derived from phage P1) → The gene deletion can be restricted to CA1 pyramidal cells
Gene deleted: NMDAR1 gene (encode the essential subunit for NMDAR)

(Traditional NMDAR1 KO mice produced by conventional gene knockout: perinatal lethality)
#### Step
1. Insert 2 loxP sequences into the NMDAR1 gene:
   - the first loxP sequence: placed in the intron that lies between exon 10 and 11
   - the second loxP sequence: placed in the downstream region of the 3' end of the NMDAR1 gene
   The 2 loxP sequences flank a region of the NMDAR1 gene that encodes: the 4 transmembrane domains + the entire C-erminal sequuences of the polypeptide chain
2. Embryonic stem cells were transfected with the linearized targeting vector
   (Verified for homologous recombination by Sounthern blot)
3. Targeted ES cells were injected into blastocytes -- fNR1 (homozygous for the loxP-NMDAR1-loxP) mice were generated
4. Cross fNR1 mice with T29-1 = Cre/+ (heterozygous Cre) transgene mice
5. Offspring: CA1-KO (Cre/+, fNR1/fNR1) mice, ...
   Homozygous fNR1 (+/+, fNR1/fNR1) mice were used as experimental controls
#### Confirmation: knockout is restricted in CA1
- Histochemical examination → Brains from CA1-KO mice did not exhibit any obvious abnormalities <span style="background:#fdbfff">(Figure 2)</span>
- Examine the neuronal patterns of the "whisker-to-barrels" system (the formation of which is dependent on NMDAR function at brainstem, thalamus and neocortex) → CA1-KO mice exhibited well-formed patterns <span style="background:#fdbfff">(Figure 2G, H, I)</span>
  e.g. in brainstem trigeminal nucleus, ventrobasal nucleus of the thalamus, primary somatosensory neocortex
- In situ hybridization with a probe → confirm absence of NMDAR1 mRNA in CA1, while distinguishable in other regions <span style="background:#fdbfff">(Figure 3)</span>

### 2. Electrophysiology, snyaptic transmission: NMDAR is knocked out + knockout is restricted in CA1 + presynaptic terminal operate normally in CA1

Stimulation of Schaffer collateral/commissural (Scc) afferents in acute slices causes responses in CA1 pyramidal cells.

-  Whole-cell recordings of CA1 pyramidal cells <span style="background:#fdbfff">(Figure 4)</span>: 
   1. CA1-KO cells lacked the slow component of EPSC that is mediated by NMDARs
   2. Early AMPA-mediated component is intact in both group - Can be blocked by CNQX - Complete inhibition of EPSC in mutant cells
   3. Early AMPA-mediated component is identical between 2 groups
   4. NMDAR-dependent EPSC in control group

- Field recordings of EPSPs <span style="background:#fdbfff">(Figure 5A)</span>:
  1. Similar timecourses of EPSPs between 2 groups when bathed in standard saline solution
  2. Additon of a solution that isolates NMDARs:
     - Mutant group: complete blockade of EPSPs
     - Control group: distinct isolated NMDA EPSPs
3. Normal timecourse and distinct isolated NMDA EPSPs of granule cells in the dentate gyrus in mutant group

- Efficiency of synaptic transmission in CA1  <span style="background:#fdbfff">(Figure 5B, C)</span>:
  Measured by input-output relations (the amplitude of the fiber volley (presynaptic action potential) that precedes the postsynaptic response / the initial slope of the EPSP) of the field EPSPs
  1. No differences between 2 groups
              ↓
    presynaptic terminal operate normally in CA1

### 3. Electrophysiology, synaptic plasticity: impaired plasticity in mutant mice CA1
 <span style="background:#fdbfff">(Figure 6)</span>
Tetanic stimulation normally induces LTP in CA1.
- In CA1-KO mice, LTP, LTD or short-term potentiation cannot be induced.
- Able to elicit NMDAR-independent LTP by giving a very high frequency tetanus
However:
- Dentate gyrus LTP remains normal.
- Control group LTP remains normal.

### 4. Behaviourral experiment, spatical memory
- The suitness of apparatus is tested using homozygous αCaMKII knockout mice.

CA1-KO mice: 
1. Longer time required to find routes
2. Longer escape latency over training blocks
3. Latency reduced after 12 blocks (veryfied by ANOVA) -- However, could be relying on nonspatial strategies -- Examined by transfer test (TT)
#### TT:
- The platform is absent and the mice swim for 60s in the pool
##### Time spending in searching for platform in the location where they were trained to find it (target quadrat)
CA1-KO mice: No preference for the target quadrat
Control mice: TT1, 2, 3 -- N, Y, Y
##### Crossing: 
- The number of times the mice cross the correct location of the platform.
CA1-KO mice: Significantly fewer than control mice during TT3
##### Platform search
CA1-KO mice: Significantly fewer average time searching in the exact location of the platform

#### Landmark test:
- To assess whether the result was not due to sensorimotor or motivational deficit
- Require the mice to find a slightly submerged platform whose location is marked by a large proximal cue
CA1-KO mice: Learned the task at a slightly slower rate but reached the same level of optimal performance as the control mice  <span style="background:#fdbfff">(Figure 7B)</span>

