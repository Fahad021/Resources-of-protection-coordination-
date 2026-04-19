# Python-Based Power-System Protection Coordination Resources

Here is a curated list of relevant resources for Python-based power-system protection coordination, with a short note for each repository and reference.[1][2][3]

## GitHub repos

- [sandialabs/Protection-settings-optimizer](https://github.com/sandialabs/Protection-settings-optimizer) — Python package for calculating optimal relay and recloser settings using network data, fault analysis, graph-based coordination pairing, and a genetic-algorithm solver.[1]

- [raheem-cs/Overcurrent-Relay-Coordination](https://github.com/raheem-cs/Overcurrent-Relay-Coordination) — Repository for time-graded overcurrent protection on a radial feeder using inverse relay characteristics.[3]

- [imsaumil/pyDSS_GUI_NCSU_ABB](https://github.com/imsaumil/pyDSS_GUI_NCSU_ABB) — Distribution System Protection Simulator built with Python and OpenDSS, with an interactive GUI for adding protection elements, DER penetration, and fault scenarios.[2]

- [dss-extensions/OpenDSSDirect.py](https://github.com/dss-extensions/OpenDSSDirect.py) — Python interface to OpenDSS that exposes circuit elements and identifies whether a circuit element has an overcurrent protection device such as a relay, recloser, or fuse.[4]

- [dss-extensions/dss_python](https://github.com/dss-extensions/dss_python) — Native Python bindings for DSS-Extensions/OpenDSS, useful as a backend for custom protection-coordination workflows.[5]

- [Energinet-SimTools/MTB](https://github.com/Energinet-SimTools/MTB/wiki/) — Contains PowerFactory automation utilities, including a Python script to extract relay data and settings from PowerFactory into Excel.[6]

- [YitianDai/Dynamic-cascading-failure-simulator](https://github.com/YitianDai/Dynamic-cascading-failure-simulator) — PowerFactory Python-API automation platform that includes functions to add and work with protection relays as part of cascading-failure studies.[7]

## Documentation and SDKs

- [Zepben Evolve Python SDK — Protection Relays](https://zepben.github.io/evolve/docs/python-sdk/next/sdk-protection/) — Python SDK documentation for CIM-based protection-relay objects, settings, sensors, thresholds, time limits, and schemes.[8]

- [ETAP etapPy](https://etap.com/product/etappy) — ETAP’s Python API for scripting, automation, reporting, and plotting in power-system studies.[9]

- [ETAP Protection & Coordination](https://etap.com/solutions/protection-coordination) — ETAP’s commercial protection and coordination solution that can be paired with Python automation through etapPy.[9]

## Papers and technical references with Python implementations

- [Adaptive Coordination of Time Overcurrent Relays in a Radial Distribution Network with Distributed Generation using a Modified LINKNET Pairing Algorithm](https://ieeexplore.ieee.org/document/10552953/) — Paper describing a Python-coded program for relay pairing and optimal relay settings under topology changes and DG presence.[10]

- [Nested Reinforcement Learning Based Control for Protective Relays](https://arxiv.org/pdf/1906.10815.pdf) — Research paper on relay-setting control architecture with Python-relevant algorithmic ideas for adaptive protection.[11]

## Practice tools and study references

- [A Step-by-Step Protection Coordination Study Example](https://elek.com/articles/step-by-step-protection-coordination-study-example/) — Practical coordination walkthrough showing TCC separation logic and coordination principles that are useful when writing your own Python implementation.[12]

- [eGrid Online Protection Coordination Tool & TCC Plotter](https://www.egrid.au/protection-coordination) — Online coordination and TCC plotting tool; useful as a reference point even though it is not a Python repo.[13]

## Most relevant first

If your goal is to get actual Python code quickly, start with these three:

1. [Protection-settings-optimizer](https://github.com/sandialabs/Protection-settings-optimizer) — strongest match for **actual coordination/setting optimization code** in Python.[1]
2. [Overcurrent-Relay-Coordination](https://github.com/raheem-cs/Overcurrent-Relay-Coordination) — smaller and simpler, useful for understanding relay-curve logic.[3]
3. [pyDSS_GUI_NCSU_ABB](https://github.com/imsaumil/pyDSS_GUI_NCSU_ABB) — useful if you want OpenDSS-based interactive simulation with protection elements and DER effects.[2]

## Notes

Only a small number of genuinely relevant public GitHub repos were identified; many search results for “protection coordination Python” point to papers, commercial tool APIs, or broader simulation frameworks rather than standalone open-source coordination engines. The Sandia PSO repo is the most complete verified open-source Python codebase specifically for automated protection setting optimization and coordination.[1][2][6][10]

## Sources

[1] sandialabs/Protection-settings-optimizer - GitHub - OSTI https://github.com/sandialabs/Protection-settings-optimizer  
[2] GitHub - imsaumil/pyDSS_GUI_NCSU_ABB: Distribution System Protection Simulator using Python and OpenDSS. https://github.com/imsaumil/pyDSS_GUI_NCSU_ABB  
[3] README.md - raheem-cs/Overcurrent-Relay-Coordination - GitHub https://github.com/raheem-cs/Overcurrent-Relay-Coordination/blob/main/README.md  
[4] OpenDSSDirect.py/opendssdirect/CktElement.py at master · dss-extensions/OpenDSSDirect.py https://github.com/dss-extensions/OpenDSSDirect.py/blob/master/opendssdirect/CktElement.py  
[5] Releases · dss-extensions/DSS-Python - GitHub https://github.com/dss-extensions/dss_python/releases  
[6] Home https://github.com/Energinet-SimTools/MTB/wiki/  
[7] GitHub - YitianDai/Dynamic-cascading-failure-simulator: A dynamic cascading failure simulation platform implemented in DIgSILENT PowerFactory via the Python API. It automatically develops cascading mechanisms, simulates sets of failure scenarios and processes results, and also has good scalability such that it can be easily applied to any power system model. https://github.com/YitianDai/Dynamic-cascading-failure-simulator  
[8] Protection Relays | Docs in test - GitHub Pages https://zepben.github.io/evolve/docs/python-sdk/next/sdk-protection/  
[9] etapPy | ETAP Python API & IDE | Scripting & Study Automation with ... https://etap.com/product/etappy  
[10] Adaptive Coordination of Time Overcurrent Relays (OCR) in a Radial Distribution Network with Distributed Generation using a Modified LINKNET Pairing Algorithm https://ieeexplore.ieee.org/document/10552953/  
[11] [PDF] Nested Reinforcement Learning Based Control for Protective Relays ... https://arxiv.org/pdf/1906.10815.pdf  
[12] A Step-by-Step Protection Coordination Study Example https://elek.com/articles/step-by-step-protection-coordination-study-example/  
[13] Online Protection Coordination Tool & TCC Plotter - eGrid https://www.egrid.au/protection-coordination  
[14] Protection, Fault Location and Isolation in Smart Grids https://theses.fr/2020GRALT026  
[15] Cyber-Physical Testbed Integrating RTAC with RTDS for Game-Theoretic Topology Control Under Load Altering Attacks https://arxiv.org/pdf/2312.05727.pdf  
[16] multiSyncPy: A Python package for assessing multivariate coordination dynamics https://pmc.ncbi.nlm.nih.gov/articles/PMC10027834/  
[17] PyCSP3: Modeling Combinatorial Constrained Problems in Python https://arxiv.org/pdf/2009.00326.pdf  
[18] DyPyBench: A Benchmark of Executable Python Software http://arxiv.org/pdf/2403.00539.pdf  
[19] Towards Energy-, Time- and Security-Aware Multi-core Coordination https://pmc.ncbi.nlm.nih.gov/articles/PMC7282835/  
[20] Automating Distribution Network Protection with Python in ... - LinkedIn https://www.linkedin.com/posts/alireza-saadati-43a490171_medium-voltage-distribution-network-protection-activity-7405633196505395201-U2y-  
[21] Best practices for securely consuming open source in Python https://ep2024.europython.eu/session/best-practices-for-securely-consuming-open-source-in-python/  
[22] The Ultimate Guide to Open-Source Security with Python and R https://www.anaconda.com/guides/the-ultimate-guide-to-open-source-security-with-python-and-r  
[23] PyPedia/Electrical-Engineering-with-Python - GitHub https://github.com/PyPedia/Electrical-Engineering-with-Python  
[24] Python Thread Safety: Using a Lock and Other Techniques https://realpython.com/python-thread-lock/  
[25] open-quantum-safe/liboqs-python: Python 3 bindings for ... - GitHub https://github.com/open-quantum-safe/liboqs-python  
[26] electricpy - PyPI https://pypi.org/project/electricpy/  
[27] An Overview of the Water Network Tool for Resilience (WNTR) https://www.semanticscholar.org/paper/75c4629f0779f9e634f37b88b5b915c29af2734a  
[28] Distributed learning from multiple EHR databases: Contextual embedding models for medical events https://linkinghub.elsevier.com/retrieve/pii/S1532046419300565  
[29] Trends in Use of Scientific Workflows 1 7 th International Digital Curation Conference December 2011 Trends in Use of Scientific Workflows : Insights from a Public Repository and Recommendations for Best Practices https://www.semanticscholar.org/paper/bbf16dd96fa6d92c02d67ad31b127eba3e64706a  
[30] An Adaptive Protection Scheme Based on a Modified Heap-Based Optimizer for Distance and Directional Overcurrent Relays Coordination in Distribution Systems https://www.mdpi.com/2227-7390/10/3/419/pdf?version=1643535794  
[31] Multi‐agent based protection scheme using current‐only directional overcurrent relays for looped/meshed distribution systems https://scholar.uwindsor.ca/cgi/viewcontent.cgi?article=1068&context=electricalengpub  
[32] ADAPTIVE OVERCURRENT DISTRIBUTION PROTECTION SCHEME COORDINATION IN THE PRESENCE OF DISTRIBUTED GENERATION USING ARTIFICIAL NEURAL NETWORK https://jesr.ub.ro/index.php/1/article/view/446  
[33] Process-and-Forward: Deep Joint Source-Channel Coding Over Cooperative Relay Networks http://arxiv.org/pdf/2403.10613.pdf  
[34] Optimal Coordination of Directional Overcurrent Relays Using Hybrid Firefly–Genetic Algorithm https://www.mdpi.com/1996-1073/16/14/5328/pdf?version=1689154345  
[35] AgentWorkforce/relay: Real-time agent to agent communication https://github.com/AgentWorkforce/relay  
[36] Summoner-Network/summoner: The coordination protocol ... - GitHub https://github.com/Summoner-Network/summoner  
[37] GitHub - automateyournetwork/netclaw: An AI agent that claws ... https://github.com/automateyournetwork/netclaw  
[38] Dicklesworthstone/flywheel_connectors: Mesh-native protocol and ... https://github.com/Dicklesworthstone/flywheel_connectors  
[39] win4r/ClawTeam-OpenClaw - GitHub https://github.com/win4r/ClawTeam-OpenClaw  
[40] PowSyBl - GitHub https://github.com/powsybl  
[41] VoltAgent/awesome-openclaw-skills - GitHub https://github.com/VoltAgent/awesome-openclaw-skills  
[42] Releases · dss-extensions/OpenDSSDirect.py - GitHub https://github.com/dss-extensions/OpenDSSDirect.py/releases
