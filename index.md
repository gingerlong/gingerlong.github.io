<style>
:root {
  --accent: #2f5d7c;
  --accent-soft: #edf5fb;
  --ink: #253040;
  --muted: #5f6b7a;
  --line: #dbe6ef;
  --card: #ffffff;
}

body {
  color: var(--ink);
  line-height: 1.65;
}

a {
  color: var(--accent);
  text-decoration: none;
}

a:hover {
  text-decoration: underline;
}

.hero {
  display: flex;
  align-items: flex-start;
  justify-content: space-between;
  gap: 2rem;
  padding: 1.4rem 1.6rem;
  margin: 0.5rem 0 1.4rem;
  border: 1px solid var(--line);
  border-radius: 18px;
  background: linear-gradient(135deg, #ffffff 0%, #f4f8fb 100%);
  box-shadow: 0 12px 32px rgba(47, 93, 124, 0.10);
}

.hero-text {
  flex: 1 1 auto;
  min-width: 0;
}

.hero h1 {
  margin: 0 0 0.35rem;
  font-size: 2.35rem;
  line-height: 1.15;
  letter-spacing: -0.03em;
}

.cn-name {
  font-weight: 600;
  color: var(--muted);
}

.subtitle {
  margin: 0.25rem 0 0.85rem;
  font-size: 1.05rem;
  color: var(--muted);
}

.contact-line {
  margin: 0.15rem 0;
}

.profile-photo {
  width: 230px;
  max-width: 34vw;
  border-radius: 18px;
  border: 4px solid #ffffff;
  box-shadow: 0 14px 30px rgba(37, 48, 64, 0.18);
}

.quick-links {
  margin-top: 0.9rem;
  display: flex;
  flex-wrap: wrap;
  gap: 0.45rem;
}

.quick-links a,
.quick-links span {
  display: inline-block;
  padding: 0.32rem 0.62rem;
  border: 1px solid var(--line);
  border-radius: 999px;
  background: #ffffff;
  font-size: 0.9rem;
}

.toc {
  margin: 0.6rem 0 1.6rem;
  padding: 0.75rem 1rem;
  border-left: 4px solid var(--accent);
  background: var(--accent-soft);
  border-radius: 12px;
}

.toc a {
  margin-right: 0.75rem;
  white-space: nowrap;
}

h2 {
  margin-top: 2.1rem;
  padding-bottom: 0.35rem;
  border-bottom: 1px solid var(--line);
  color: var(--accent);
}

h3 {
  margin-top: 1.35rem;
  color: #31465c;
}

.chips {
  display: flex;
  flex-wrap: wrap;
  gap: 0.5rem;
  margin: 0.8rem 0 1rem;
}

.chips span {
  padding: 0.35rem 0.65rem;
  border-radius: 999px;
  background: var(--accent-soft);
  border: 1px solid var(--line);
  font-size: 0.95rem;
}

table {
  width: 100%;
  border-collapse: collapse;
  margin: 1rem 0 1.2rem;
}

th, td {
  padding: 0.65rem 0.75rem;
  border: 1px solid var(--line);
  vertical-align: top;
}

th {
  background: var(--accent-soft);
  color: #31465c;
}

.publication-list li,
.compact-list li {
  margin-bottom: 0.75rem;
}

.note {
  padding: 0.85rem 1rem;
  border: 1px solid var(--line);
  border-radius: 14px;
  background: #fbfdff;
}

.footer {
  margin-top: 2.4rem;
  padding-top: 1rem;
  border-top: 1px solid var(--line);
  color: var(--muted);
  font-size: 0.92rem;
}

@media (max-width: 760px) {
  .hero {
    flex-direction: column-reverse;
    align-items: flex-start;
    padding: 1rem;
  }

  .profile-photo {
    width: 180px;
    max-width: 70vw;
  }

  .hero h1 {
    font-size: 1.9rem;
  }
}
</style>

<div class="hero">
  <div class="hero-text">
    <h1>Yangjing Long <span class="cn-name">龙旸靖</span></h1>
    <p class="subtitle"><strong>Associate Professor</strong> · School of Mathematics and Statistics · Central China Normal University</p>
    <p class="contact-line">📍 152 Luoyu Road, Wuhan 430079, China</p>
    <p class="contact-line">✉️ yangjing(at)mail(dot)ccnu(dot)edu(dot)cn</p>
    <div class="quick-links">
      <a href="http://maths.ccnu.edu.cn/English/HO.htm/">School Homepage</a>
      <a href="https://orcid.org/0000-0001-5934-1326">ORCID: 0000-0001-5934-1326</a>
      <a href="https://arxiv.org/abs/1404.5334">Dissertation</a>
      <span>Erdős number: 2</span>
    </div>
  </div>
  <img class="profile-photo" src="./profile.png" alt="Portrait of Yangjing Long">
</div>

<div class="toc">
  <strong>Contents:</strong>
  <a href="#personal-information">About</a>
  <a href="#research-interests">Research</a>
  <a href="#grants">Grants</a>
  <a href="#selected-publications">Selected Publications</a>
  <a href="#other-publications">Other Publications</a>
  <a href="#preprints">Preprints</a>
  <a href="#competition-guidance">Guidance</a>
  <a href="#service">Service</a>
</div>

## Personal Information

I am currently an associate professor at the [School of Mathematics and Statistics, Central China Normal University](http://maths.ccnu.edu.cn/English/HO.htm/). I received my PhD from the [Max Planck Institute for Mathematics in the Sciences](https://www.mis.mpg.de/). My advisors were [Jürgen Jost](https://www.mis.mpg.de/jjost/juergen-jost.html) and [Peter F. Stadler](http://www.bioinf.uni-leipzig.de/~studla/). My dissertation defense was on October 18, 2014.

I completed my BS in mathematics at [Shanghai Jiao Tong University](https://www.math.sjtu.edu.cn). My Erdős number is 2 (optimal).

## Research Interests

My research interests are in graph theory and phylogenetic combinatorics, including combinatorics in the application of biology and quantum information, as well as AI for mathematics and science.

<p class="chips">
  <span>Graph Theory</span>
  <span>Phylogenetic Combinatorics</span>
  <span>Combinatorics in Biology</span>
  <span>Quantum Information</span>
  <span>AI for Math and Science</span>
</p>

<div class="note">
  Dissertation: <a href="https://arxiv.org/abs/1404.5334"><em>Relations Between Graphs</em></a>.
</div>

## Grants

| Period | Role | Project | Funding |
|---|---|---|---:|
| 2025–2027 | Principal Investigator | Open Research Project of Fuzhou University | 50,000 RMB |
| 2024–2026 | Collaborator | Open Research Project of Central China Normal University, cooperated with Chongqing University of Technology | 50,000 RMB |
| 2025–2027 | Collaborator | Open Research Project of Central China Normal University, cooperated with Zhejiang Normal University | 20,000 RMB |
| 2025–2026 | Principal Investigator | Huawei Horizontal Project, Ascend Program | 40,000 RMB |
| 2020–2022 | Principal Investigator | *Path Systems of Edge-Labeled Phylogenetic Trees*, No. 20201191803; Youth Fund, National Natural Science Fund for Chinese Postdocs, China | 250,000 RMB |
| 2019–2020 | Principal Investigator | Fundamental Research Funds for the Central Universities | 100,000 RMB |
| 2018–2019 | Principal Investigator | Fundamental Research Funds for the Central Universities | 100,000 RMB |
| 2018–2021 | Main Participant | *Contextuality as a Resource in Quantum Computation* (61771011), National Natural Science Fund, China | 520,000 RMB |
| 2017–2020 | Main Participant | *Discrete Dynamics and Beyond* (11671258), National Natural Science Fund, China | 480,000 RMB |
| 2016–2017 | Principal Investigator | *Some Problems on Graph Homomorphisms*, No. 154463, National Natural Science Fund for Chinese Postdocs, China | 50,000 RMB |

## Selected Publications

<ol class="publication-list">
  <li><a href="https://www.ncbi.nlm.nih.gov/pubmed/29218395">Inference of Phylogenetic Trees from the Knowledge of Rare Evolutionary Events</a>, joint with M. Hellmuth, M. Hernandez-Rosales, and P. F. Stadler, <em>Journal of Mathematical Biology</em>, 2018, 76(7): 1623–1653.</li>
  <li><a href="https://www.sciencedirect.com/science/article/pii/S0195669817300914">Fractal Property of Homomorphism Order</a>, joint with J. Fiala, J. Hubicka, and J. Nešetřil, <em>European Journal of Combinatorics</em>, 2017, 66: 101–109.</li>
  <li><a href="https://www.sciencedirect.com/science/article/pii/S0195669814000705">Universality of Intervals of Line Graph Order</a>, joint with J. Fiala and J. Hubicka, <em>European Journal of Combinatorics</em>, 2014, 41: 221–231.</li>
  <li><a href="https://ieeexplore.ieee.org/document/4587889">Demosaicking Recognition with Applications in Digital Photo Authentication Based on a Quadratic Pixel Correlation Model</a>, joint with Y. Huang, <em>CVPR</em>, 2008.</li>
</ol>

## Other Publications

<ul class="publication-list">
  <li><a href="https://onlinelibrary.wiley.com/doi/10.1002/jgt.70006">A Characterization of Multigraphs Reaching Goldbuer’s Bound of Chromatic Index</a>, joint with Qiong Fan, Chunxiang Wang, and Shijing Wang, <em>Journal of Graph Theory</em>, 2026, 111(4): 99–112.</li>
  <li><a href="https://link.springer.com/article/10.1007/s10878-025-01309-z">Neighbor Sum Distinguishable <em>k</em>-Edge Colorings of Joint Graphs</a>, joint with Xiangzhi Tu, Peng Li, and Aifa Wang, <em>Journal of Combinatorial Optimization</em>, 2025, 49(1): 123–135.</li>
  <li><a href="https://www.worldscientific.com/doi/10.1142/S1793830923501057">On the Unit Interval Graphs Which Are Paired-Disjoint Path Coverable</a>, joint with P. Li and T. Liu, <em>Discrete Mathematics, Algorithms and Applications</em>, 2024, 16(08), 2350105.</li>
  <li><a href="https://arxiv.org/abs/1709.09725">Word-Representability of Split Graphs</a>, joint with S. Kitaev, J. Ma, and H. Wu, <em>Journal of Combinatorics</em>, 2022, 12(4): 725–746.</li>
  <li><a href="https://www.sciencedirect.com/science/article/pii/S0166218X21000135">Unrooted Non-Binary Tree-Based Phylogenetic Networks</a>, joint with Mareike Fischer, Michelle Galla, Lina Herbst, and Kristina Wicke, <em>Discrete Applied Mathematics</em>, 2021, 294: 10–30.</li>
  <li><a href="https://www.sciencedirect.com/science/article/abs/pii/S0166218X20302638">Exact-2-Relation Graphs</a>, joint with P. F. Stadler, <em>Discrete Applied Mathematics</em>, 2020, 285: 212–226.</li>
  <li><a href="https://pubmed.ncbi.nlm.nih.gov/32415350/">Classes of Tree-Based Networks</a>, joint with Mareike Fischer, Michelle Galla, Lina Herbst, and Kristina Wicke, <em>Visual Computing for Industry, Biomedicine, and Art</em>, 2020, 3(1): 12.</li>
  <li><a href="https://adam-journal.eu/index.php/ADAM/article/view/1245">A Short Note on Undirected Fitch Graphs</a>, joint with M. Geiß, M. Hellmuth, and P. F. Stadler, <em>The Art of Discrete and Applied Mathematics</em>, 2018, 1(1).</li>
  <li><a href="https://link.springer.com/article/10.1007/s11538-018-0413-7">Reconstructing Unrooted Phylogenetic Trees from Symbolic Ternary Metrics</a>, joint with S. Grünewald and Y. Wu, <em>Bulletin of Mathematical Biology</em>, 2018, 80: 1563–1577.</li>
  <li><a href="https://www.sciencedirect.com/science/article/pii/S1571065317301555">Gaps in Full Homomorphism Order</a>, joint with J. Fiala and J. Hubicka, <em>Electronic Notes in Discrete Mathematics</em>, 2017, 61: 429–435.</li>
  <li><a href="https://www.sciencedirect.com/science/article/pii/S157106531500133X">An Universality Argument for Graph Homomorphisms</a>, joint with J. Fiala and J. Hubicka, <em>Electronic Notes in Discrete Mathematics</em>, 2015, 49: 643–649.</li>
  <li><a href="https://amc-journal.eu/index.php/amc/article/download/335/603">Relations Between Graphs</a>, joint with J. Hubicka, J. Jost, P. Stadler, and L. Yang, <em>Ars Mathematica Contemporanea</em>, 2012, 6(2): 323–350.</li>
  <li><a href="https://www.sciencedirect.com/science/article/pii/S1007570406000591">On Orthogonal Polynomial Approximation with the Dimensional Expanding Technique for Precise Time Integration in Transient Analysis</a>, joint with Y. Huang, <em>Communications in Nonlinear Science and Numerical Simulation</em>, 2007, 12(8): 1584–1603.</li>
  <li><a href="https://www.worldscientific.com/doi/10.1142/S021949880700220X">The Correspondence Between Zero-Divisor Graphs with 6 Vertices and Their Semigroups</a>, joint with Y. Huang, <em>Journal of Algebra and Its Applications</em>, 2007, 6(2): 287–290.</li>
</ul>

## Preprints

<ul class="compact-list">
  <li><em>Semantic Cues, Rather Than Scores, Drive LLM-Simulated ADHD-like Participants: A Human-Benchmark, Cue-Contribution, and Individual-Prediction Study</em>, joint with Wei Zhang, Songjie Tian, and Chenguang Zhao, submitted.</li>
  <li><a href="https://arxiv.org/abs/2606.06905">An Explicit O(r\log r) Threshold for Attaining the Semple--Steel Bound with r-State Characters</a>, joint with P. Li, submitted.</li>
  <li><a href="https://arxiv.org/abs/2606.02271">Exact Leaf Powers on Cycles, Ladders, Crowns, and Multipartite Block Graphs</a>, joint with P. Li, submitted.</li>
  <li><em>Fixed-Charge Saturation and Two-Weight Domination for the k-th Roman Domination Problem on Interval Graphs</em>, joint with P. Li, submitted.</li>
  <li><em>A Unified BFS-Layer Framework for K-Feasible Domination Problems</em>, joint with Peng Li, submitted.</li>
  <li><a href="https://arxiv.org/abs/2508.15533">Defining a Phylogenetic Tree with the Minimum Number of Small-State Characters</a>, joint with T. Wang, submitted.</li>
  <li><em>The AT-Number of the Line Graph of Multicircuits and Multicomplete Bipartite Graphs</em>, joint with G. Chen, J. Kozik, X. Zhu, and J. Zhu, submitted.</li>
  <li><a href="https://arxiv.org/abs/2605.19543">The Quantum Homomorphism Orders Are Universal</a>, submitted.</li>
  <li><a href="https://arxiv.org/abs/2605.21945">A Characterization of Level-k Realizability for Clustering Systems</a>, joint with S. Dai, submitted.</li>
    <!--返修重投-->
  <li><a href="https://arxiv.org/abs/2605.19962">Computing the Arc-Deletion Distance to Orchard Networks Is NP-Hard</a>, joint with Z. Liu and P. Li, submitted.</li>
  
  <li><em>On the Generalized Nearest Neighbor Interchange Operations</em>, joint with Stefan Grünewald, Peter Humphries, and Taoyang Wu.</li>
  <li><a href="https://arxiv.org/abs/2606.09231">Constrained Homomorphism Partial Orders</a>, joint with J. Fiala and J. Hubicka.</li>
    <!--with Honza-->
  <li><em>Proximity Measures for Classes of Phylogenetic Networks</em>, joint with L. van Iersel, M. Jones, E. Julien, and Y. Murakami.</li>
</ul>

## Competition Guidance

- First Prize, 2023 Postgraduate Mathematical Modeling Competition, Top 1%.

## Service

- Member, Specialized Committee on Math and AI, Chinese Mathematical Society.
- Reviewer for MathSciNet, 2018–present.

<div class="footer">
Last updated: 2026. Built with Markdown for GitHub Pages.
</div>
