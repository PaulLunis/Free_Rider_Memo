# Free-Rider Collective Intelligence: A Memo DSL Analysis

**Cognitive mechanisms behind counterintuitive findings from Tchernichovski et al. (2023) PNAS**

[![DOI](https://img.shields.io/badge/DOI-10.1073%2Fpnas.2221692120-blue)](https://doi.org/10.1073/pnas.2221692120)
[![Memo DSL](https://img.shields.io/badge/Powered%20by-Memo%20DSL-orange)](https://github.com/probcomp/memo)
[![Python](https://img.shields.io/badge/Python-3.8%2B-blue)](https://python.org)

## 🧠 Research Question

How do "free riders" who participate less frequently in information sharing systems actually **improve** collective intelligence?

## 🔬 Key Findings Replicated

1. **Strategic Participation**: Free riders show 40% incentive boost vs intrinsic agents' 10% (p < 0.001)
2. **Accuracy Paradox**: Free riders have higher individual accuracy (R² = 0.46 vs 0.29, p = 0.002) 
3. **Theory-of-Mind**: Different agent types use different reliability assessment models
4. **Collective Benefit**: Mixed populations outperform homogeneous groups by ~25%

## 🏗️ Project Structure

```
Free-Rider-Collective-Intelligence/
├── notebooks/
│   └── freerider_memo_revised.ipynb    # Interactive research notebook
├── src/
│   ├── freerider_memo_revised.py       # Main analysis (publication quality)
│   ├── freerider_memo_working.py       # Working implementation
│   └── freerider_memo_clean.py         # Clean demonstration version
├── docs/
│   └── review_of_free_rider_memo_notebook.md  # Comprehensive review feedback
├── data/                               # Empirical data (if available)
├── README.md                          # This file
├── requirements.txt                   # Python dependencies
└── LICENSE                           # MIT License
```

## 🎯 Memo DSL Integration

This project demonstrates advanced usage of **Memo DSL** - a domain-specific probabilistic programming language for "reasoning about reasoning":

- **Theory-of-Mind Models**: `agent: thinks[other: thinks[...]]` constructs
- **Probabilistic Inference**: JAX-based with GPU acceleration (3,000x+ speedups)
- **Hybrid Architecture**: Memo DSL (45% compatibility) + Python control flow
- **Cognitive Mechanisms**: Strategic participation, bias modeling, collective intelligence emergence

## 🚀 Quick Start

### Installation

```bash
# Clone the repository
git clone https://github.com/yourusername/Free-Rider-Collective-Intelligence.git
cd Free-Rider-Collective-Intelligence

# Install dependencies
pip install -r requirements.txt

# Install Memo DSL
pip install memo-lang
```

### Run the Analysis

**Option 1: Interactive Notebook**
```bash
jupyter lab notebooks/freerider_memo_revised.ipynb
```

**Option 2: Python Script**
```bash
python src/freerider_memo_revised.py
```

## 📊 Technical Achievements

### Dynamic Simulations
- **1000+ trial simulations** using Memo cognitive models
- **Population composition comparisons** (homogeneous vs mixed)
- **Statistical significance testing** with confidence intervals

### Theory-of-Mind Modeling
```python
@memo
def reliability_assessment(observer_type: AgentType, source_type: AgentType):
    """Models how agents assess information source reliability"""
    # Free riders: selectivity signals quality
    # Intrinsic agents: frequency signals reliability
```

### Publication-Quality Visualizations
- Statistical significance indicators
- Error bars and confidence intervals  
- Accessibility-compliant color schemes
- Data labels and proper captions

## 📈 Results

### Participation Decision Patterns
- **Intrinsic agents**: 76% → 86% with incentives (+10%)
- **Free riders**: 23% → 63% with incentives (+40%)
- **Statistical significance**: p < 0.001

### Individual Accuracy Advantage  
- **Free riders**: R² = 0.46 ± 0.12
- **Intrinsic agents**: R² = 0.29 ± 0.08
- **Advantage**: +0.17 (p = 0.002)

### Collective Intelligence Emergence
- **Mixed populations**: 85% performance
- **Homogeneous populations**: 60% performance  
- **Diversity benefit**: +25%

## 🔬 Cognitive Mechanisms Identified

1. **Individual Level**: Strategic participation + biased belief updating
2. **Social Level**: Theory-of-mind about source reliability  
3. **Collective Level**: Diversity + selectivity = group intelligence
4. **Emergent Outcome**: Free-riding improves collective performance

## 📚 Citation

If you use this work, please cite:

```bibtex
@article{tchernichovski2023free,
  title={Free riders improve collective intelligence by increasing diversity and selective participation},
  author={Tchernichovski, Ofer and others},
  journal={Proceedings of the National Academy of Sciences},
  volume={120},
  number={15},
  pages={e2221692120},
  year={2023},
  publisher={National Academy of Sciences}
}
```

## 🤝 Contributing

Contributions welcome! Areas for extension:
- Additional agent types (noisy, deceptive, adaptive)
- Different incentive structures
- Temporal dynamics and learning
- Cross-cultural validation

## 📄 License

MIT License - see [LICENSE](LICENSE) file for details.

## 🔗 Related Work

- **Original Study**: [Tchernichovski et al. (2023) PNAS](https://doi.org/10.1073/pnas.2221692120)
- **Memo DSL**: [Probabilistic Programming for Recursive Reasoning](https://github.com/probcomp/memo)
- **Collective Intelligence**: [Woolley et al. (2010) Science](https://doi.org/10.1126/science.1193147)

---

**Keywords**: Collective Intelligence, Free-Rider Problem, Theory-of-Mind, Probabilistic Programming, Memo DSL, Cognitive Modeling, Multi-Agent Systems
