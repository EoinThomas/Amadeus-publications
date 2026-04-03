# How to Update BibTeX Citations

Due to network restrictions, I couldn't fetch BibTeX from Google Scholar or conference sites automatically. Here's how to update them manually:

## Publications Needing BibTeX Updates

### 1. Variational Inference for Quantum HyperNetworks
- **File:** `publications/variational-inference-quantum-hypernetworks.md`
- **Search:** https://scholar.google.com/scholar?q=Variational+Inference+for+Quantum+HyperNetworks+Nepote
- **Current:** arXiv citation
- **Prefer:** IJCNN Workshop proceedings if available

### 2. Semantic Adapter for Universal Text Embeddings
- **File:** `publications/semantic-adapter-universal-text-embeddings.md`
- **Search:** https://scholar.google.com/scholar?q=Semantic+Adapter+Universal+Text+Embeddings+Cao+ECAI
- **Current:** arXiv citation
- **Prefer:** ECAI 2025 proceedings

### 3. Diverse and Private Synthetic Datasets for RAG
- **File:** `publications/diverse-private-synthetic-datasets-rag.md`
- **Search:** https://scholar.google.com/scholar?q=Diverse+Private+Synthetic+Datasets+RAG+Driouch
- **Current:** arXiv citation
- **Prefer:** TRUST-AI workshop proceedings

### 4. Multi-Agent LLM Judge
- **File:** `publications/multi-agent-llm-judge.md`
- **Search:** https://scholar.google.com/scholar?q=Multi-Agent+LLM+Judge+Cao+ECAI
- **Current:** arXiv citation
- **Prefer:** LLAIS workshop proceedings

### 5. Recent Advances in Text Embedding
- **File:** `publications/recent-advances-text-embedding.md`
- **Search:** https://scholar.google.com/scholar?q=Recent+Advances+Text+Embedding+MTEB+Cao
- **Current:** arXiv citation (may stay as arXiv if not published elsewhere)

### 6. Cramér Distance Distributional RL
- **File:** `publications/cramer-distance-distributional-rl.md`
- **Search:** https://scholar.google.com/scholar?q=Cramér+Distance+Quantile+Regression+Lheritier+AISTATS
- **Current:** Placeholder
- **Prefer:** AISTATS 2022 proceedings

### 7. Low-Complexity Bayesian Online Prediction
- **File:** `publications/low-complexity-bayesian-online-prediction.md`
- **Search:** https://scholar.google.com/scholar?q=Low-Complexity+Nonparametric+Bayesian+Lheritier+NeurIPS
- **Current:** Placeholder
- **Prefer:** NeurIPS 2019 proceedings

### 8. Deep Choice Model Using Pointer Networks
- **File:** `publications/deep-choice-model-pointer-networks.md`
- **Search:** https://scholar.google.com/scholar?q=Deep+Choice+Model+Pointer+Networks+Mottini+SIGKDD
- **Current:** Placeholder
- **Prefer:** SIGKDD 2017 proceedings

## How to Update

1. **Go to Google Scholar** and search for the paper
2. **Click "Cite"** under the paper
3. **Click "BibTeX"** at the bottom of the citation popup
4. **Copy the BibTeX** entry
5. **Edit the publication markdown file** and replace the BibTeX between the `{% raw %}` and `{% endraw %}` tags
6. **Commit and push** the changes

## Quick Commands

```bash
# Edit a file
open publications/[filename].md

# Or use your editor
code publications/[filename].md

# After editing, commit and push
git add publications/[filename].md
git commit -m "Update BibTeX citation for [paper name]"
git push origin main
```

## Alternative: Shell Script

You can also manually paste BibTeX entries and I can update the files for you. Just provide them in this format:

```
FILE: publications/filename.md
BIBTEX:
@inproceedings{...
}
```
