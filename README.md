# 🎭✨ Poetic Prompting Research

[![Research Status](https://img.shields.io/badge/Status-Active%20Research-brightgreen)](https://axisdynamics.cl)
[![Language](https://img.shields.io/badge/Language-Spanish%20%7C%20English-blue)](#)
[![Model](https://img.shields.io/badge/Tested-Claude%20Sonnet%204.5-orange)](https://www.anthropic.com/)
[![Improvement](https://img.shields.io/badge/Performance%20Gain-+11.9%25-success)](https://github.com/exis-research)

> **Empirical validation that poetic/metaphorical prompts significantly outperform traditional instructional approaches in Large Language Models**

## 📖 Overview

This repository contains research demonstrating that LLMs produce **superior outputs** when prompted with poetic, metaphorical, and narrative structures rather than purely technical instructions.

### 🔬 Key Findings

```
Instructional:  8.87/10 (baseline)
Hybrid:         9.47/10 (+6.8%)  ⭐ OPTIMAL PRACTICAL SOLUTION
Poetic:         9.93/10 (+11.9%) 
```

**Statistical significance:** p < 0.001 across all comparisons  
**Tasks tested:** 10 diverse domains (technical, analytical, creative, strategic)

## 🚀 Quick Start

### Want to try poetic prompting?

**Traditional prompt:**
```
Analyze the quarterly financial data and provide key insights.
```

**Hybrid approach:** 
```
You're a financial detective uncovering the story hidden in numbers. 
Examine this quarterly data as if you're reading the company's pulse—
what narrative emerges from the financial heartbeat?
```

**Results:** Consistently richer analysis, better structure, maintained accuracy.

## 📊 Research Results

| Metric | Instructional | Hybrid | Poetic | Hybrid vs Inst | Poetic vs Inst |
|--------|---------------|---------|---------|----------------|----------------|
| Overall Quality | 8.87 | **9.47** | 9.93 | +6.8% | +11.9% |
| Token Efficiency | 100% | 149% | 179% | +49% | +79% |
| Quality/Token Ratio | 1.00 | **0.95** | 0.87 | Best | Good |

### 💡 Why Hybrid Wins
- Captures **57%** of poetic quality gains
- Uses only **35%** of additional token cost
- Maintains technical precision
- Practical for production use

## 📁 Repository Structure

```
├── papers/
│   ├── prompt_poetry_paper_english.md      # Full research paper (English)
│   └── prompt_poetry_resumen_spanish.md    # Executive summary (Spanish)
├── experiments/
│   ├── prompts/                            # All 30 experimental prompts
│   ├── outputs/                            # Complete AI responses
│   └── evaluation/                         # Scoring data and analysis
├── methodology/
│   ├── evaluation_rubrics.md
│   ├── statistical_analysis.R
│   └── token_analysis.py
└── examples/
    ├── hybrid_prompt_templates.md
    └── use_case_gallery.md
```

## 🔬 Methodology

- **Model:** Claude Sonnet 4.5
- **Tasks:** 10 diverse prompts across domains
- **Conditions:** 3-point continuum (Instructional → Hybrid → Poetic)
- **Evaluation:** 5-dimensional scoring (Adherence, Quality, Clarity, Creativity, Structure)
- **Statistical Analysis:** Paired t-tests with Bonferroni correction

## 🤝 How to Contribute

### 🎯 High Priority Needs

1. **Multi-Model Replication**
   - Test with GPT-4, Gemini, Llama, etc.
   - Contribute results via PR

2. **Task Domain Expansion**
   - Add prompts from your expertise area
   - Follow our methodology template

3. **Evaluation Enhancement**
   - Multi-evaluator scoring
   - Automated metrics development
   - User preference studies

### 📝 Contribution Guidelines

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/new-model-test`)
3. Follow our [experimental protocol](methodology/protocol.md)
4. Submit a Pull Request with results

## 🧪 Research Roadmap

### Phase 1 (Q1 2025) - Current
- [x] Initial validation (10 prompts, Claude Sonnet)
- [ ] Multi-evaluator replication
- [ ] Community outreach

### Phase 2 (Q2 2025) - Expansion
- [ ] Multi-model validation (GPT-4, Gemini, Llama)
- [ ] Cross-linguistic replication
- [ ] Production deployment studies

### Phase 3 (Q3 2025) - Application
- [ ] Automated hybrid prompt generation
- [ ] Industry-specific optimizations
- [ ] Real-world A/B testing

## 📚 Theoretical Foundation

Built on decades of cognitive science:

- **Lakoff & Johnson (1980):** Conceptual Metaphor Theory
- **Paivio (1971):** Dual Coding Theory  
- **Green & Brock (2000):** Narrative Transportation Theory
- **Gallese & Lakoff (2005):** Embodied Cognition

**Core insight:** Metaphor isn't decorative—it's cognitive architecture.

## 🏆 Academic Impact

**Target Venues:**
- ACL, NeurIPS, EMNLP (AI/NLP conferences)
- Cognitive Science Society
- AI Magazine

**Broader Implications:**
- Challenges binary instructional/creative thinking
- Validates pre-Enlightenment knowledge traditions
- Provides practical engineering guidelines

## 📧 Contact & Collaboration

**Lead Researcher:** Marco Torres Yévenes  
**Organization:** Axisdynamics Spa & Exis Research  
**Email:** contacto@exis.cl  
**Website:** https://axisdynamics.cl  
**Co-researcher:** Jorge Castillo Sepúlveda

### 💬 Join Our Community

- **Research Discussions:** Open issues for methodology questions
- **Results Sharing:** Submit findings via Pull Requests  
- **Collaboration:** Email for co-research opportunities

---

## 📄 Citation

```bibtex
@article{torres2025poetic,
  title={Beyond Binary: Empirical Validation of the Poetic-Instructional Continuum in Large Language Model Prompting},
  author={Torres Yévenes, Marco and Castillo Sepúlveda, Jorge},
  journal={In preparation},
  year={2025},
  organization={Axisdynamics Spa \& Exis Research}
}
```

## 🔗 Links

- [Full Research Paper](papers/prompt_poetry_paper_english.md)
- [Spanish Summary](papers/prompt_poetry_resumen_spanish.md)
- [Axisdynamics Website](https://axisdynamics.cl)
- [Methodology Details](methodology/)

---

*"When knowledge must endure, when understanding must deepen, when insight must transform—you don't flatten it into prose. You sing it."*

**Ready to sing with the machines?** 🎵🤖

[![Star this repo](https://img.shields.io/github/stars/exis-research/poetic-prompting.svg?style=social&label=Star)](https://github.com/exis-research/poetic-prompting)
