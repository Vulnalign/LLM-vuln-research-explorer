LLM Vulnerability Research Explorer
An interactive visualization tool for exploring research papers on LLM-based vulnerability detection. Browse 87+ papers with rich metadata on methodologies, datasets, and code availability.


Features
Interactive Filtering: Search and filter by year, methodology, paper type, and code availability
Rich Metadata: Each paper tagged with methods (LLM-based, Static Analysis, RAG, etc.), datasets used, and research focus areas
Reproducibility Tracking: Easily identify papers with publicly available code
Real-time Search: Find papers by title, venue, method, or dataset
Clean Visualization: Modern, responsive interface for exploring the research landscape

Statistics

- 87 papers from 2018-2026
- 41% with code available
- 56 LLM-based approaches
- Coverage of major venues: ICSE, NDSS, Usenix, NeurIPS, ACL, and more

Methodology Tags
Papers are categorized by approach:

- LLM-based (prompting, fine-tuning, agents)
- Static Analysis (AST, CPG, dataflow)
- Graph-based (GNN)
- Multi-modal
- RAG (Retrieval-Augmented Generation)
- Benchmark/Survey papers

Dataset Coverage
Tracks usage of major vulnerability datasets: CVEfixes, BigVul, SVEN, Devign, DiverseVul, VulDeePecker, And more

Usage
- Simply open index.html in your browser, or visit the live version.
- Local Development

bash

git clone https://github.com/yourusername/LLM-vuln-research-explorer.git
cd LLM-vuln-research-explorer
# Open index.html in your browser

Data Source
- Papers curated from Awesome-LLMs-for-Vulnerability-Detection with additional metadata enrichment.
- Contributing

Found a paper that should be included? Have metadata corrections?

- Open an issue
- Submit a pull request
- Suggest new filtering categories

Motivation
This tool was built to address the challenge of navigating the rapidly growing landscape of LLM-based vulnerability detection research. With dozens of papers published each year, researchers need better tools to:

- Identify relevant prior work
- Understand methodological trends
- Find reproducible implementations
- Track dataset usage and quality

License
MIT License - feel free to use, modify, and share.

Citation
If you find this tool useful in your research, please cite:

bibtex

@misc{vuln-research-explorer,
  title={LLM Vulnerability Research Explorer},
  author={Your Name},
  year={2025},
  url={https://github.com/yourusername/LLM-vuln-research-explorer}
}

Contact
Questions or suggestions? Open an issue or reach out at 

Built with ❤️ for the vulnerability detection research community.
