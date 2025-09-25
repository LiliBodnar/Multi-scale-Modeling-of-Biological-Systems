1. Which mutation is most dangerous and why? Provide quantitative evidence.
    * (Angelos note: i would mention that A,B,C are all equally dangerous as they dont allow the cell to die when there is DNA damage - for graphs you can use the pie charts at the end of the notebook)

2. Explain the role of feedback loops (e.g., MYC → MDM2 → p53)
    
3. What are the limitations of this Boolean network model? Discuss 3 specific limitations.
    * Binary States:
        - One key limitation of this Boolean network is that it only allows each component to be either fully ON or fully OFF. In reality, molecules such as p53 or MYC can exist at different concentration levels, and their effects often depend on thresholds or gradual changes. By reducing these dynamics to binary states, the model cannot capture dose-dependent regulation or partial inhibition that occurs in real cells.
    * Lack of Temporal Dynamics:
        - Another limitation is that the network assumes all nodes update synchronously at each step. Biological processes, however, operate on very different timescales—phosphorylation happens quickly, while gene transcription and protein accumulation can take much longer. This simplification means the model cannot reflect transient dynamics, time delays, or oscillatory behaviors.
    * Simplified and Incomplete Topology:
        - Finally, the network structure is highly simplified and incomplete. Only a small set of genes and interactions are represented, while many other regulators of cell fate are excluded. Because the rules are manually specified, the model’s predictions strongly depend on these assumptions, and important pathways or feedback loops may be missing.