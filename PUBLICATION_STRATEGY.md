# Publication Strategy - PP25 Chaotic Attractor Compression

**Author**: Francisco Molina Burgos (ORCID: 0009-0008-6093-8267)
**Date**: 2025-11-22
**Status**: Pre-print ready

---

## Current State

✅ **GitHub Repository**: Source code + Markdown paper (pre-print format)
✅ **Zenodo Integration**: Will provide DOI for pre-print version
⏳ **Journal Submission**: Requires LaTeX conversion

---

## Publication Venues & Formats

### 1️⃣ **Immediate: GitHub + Zenodo (Pre-print)**

**Status**: READY NOW
**Format**: Markdown + Code
**DOI**: Zenodo assigns automatically (10.5281/zenodo.XXXXXX)

**Purpose**:
- Establish priority and timestamp
- Citable immediately
- Permanent archival
- Show reproducible research

**Action**:
```bash
# 1. Publish to GitHub
git init
git add .
git commit -m "feat: initial release v1.0.0"
gh repo create Yatrogenesis/PP25-CHAOTIC_ATTRACTOR_COMPRESSION --public --source=. --push

# 2. Create release
git tag -a v1.0.0 -m "Release v1.0.0"
git push origin v1.0.0

# 3. Enable Zenodo at https://zenodo.org/account/settings/github/
```

---

### 2️⃣ **Short-term: arXiv (Pre-print)**

**Timeline**: 1-2 weeks after Zenodo
**Format**: **LaTeX required** (PDF generated from LaTeX)
**Category**: cs.LG (Machine Learning)
**arXiv ID**: Will be assigned (e.g., arXiv:2025.XXXXX)

**Requirements**:
- Convert Markdown → LaTeX
- Submit .tex files or PDF
- 10MB limit per file
- May require endorsement (first-time submitters)

**Benefits**:
- High visibility in ML community
- Indexed by Google Scholar
- No peer-review delay
- Free

**Action**:
1. Convert `paper/PAPER_CHAOTIC_ATTRACTOR_COMPRESSION.md` → LaTeX
2. Use standard article class or conference template
3. Submit at https://arxiv.org/submit
4. Update README with arXiv badge

---

### 3️⃣ **Medium-term: NeurIPS 2026 (Peer-reviewed Conference)**

**Deadline**: ~May 2026 (expected, not yet announced)
**Status**: ⚠️ NeurIPS 2025 deadline (May 2025) already passed
**Format**: **NeurIPS LaTeX template required**
**Page Limit**: 9 pages main text + unlimited references
**Acceptance Rate**: ~25%
**DOI**: Assigned by PMLR after acceptance

**Requirements**:
- Use `neurips_2025.sty` style file
- 10pt Times Roman, single column
- 5.5" × 9" text area
- Anonymous submission (blind review)
- Submit via OpenReview

**Template**:
- Download from https://neurips.cc/Conferences/2025/PaperInformation/StyleFiles
- Use `neurips_2025.tex` as shell
- Omit `\usepackage[final]{neurips_2025}` during submission (for anonymity)

**Benefits**:
- Top-tier venue (highest prestige in ML)
- Published in PMLR proceedings
- Conference presentation
- Highly cited

**Timeline** (expected for NeurIPS 2026):
- May 2026: Submission deadline (estimated)
- Jul 2026: Reviews
- Sep 2026: Decisions
- Dec 2026: Conference + publication

**Alternative**: ICLR 2026 (sooner!)
- Deadline: September 24, 2025 ❌ **ALREADY PASSED**
- Conference: April 24-28, 2026 in Rio de Janeiro

**Action**:
1. Wait for NeurIPS 2026 call for papers (early 2026)
2. Convert paper to NeurIPS LaTeX format (9 pages)
3. Condense to fit page limit
4. Anonymize (remove author names, affiliations)
5. Submit via OpenReview in ~May 2026

---

### 3️⃣-B **Alternative: ICMLT 2026 (Sooner!)**

**Deadline**: December 25, 2025 ⏰ **1 MONTH AWAY**
**Conference**: May 20-22, 2026 in Berlin, Germany
**Format**: LaTeX required
**Timeline**: Fast track to publication

**Benefits**:
- Immediate submission opportunity
- Acceptance notification: January 25, 2026
- Conference in May 2026
- Published proceedings

**Quality Assessment**:
- ⭐⭐⭐⭐ Tier: Regional/International (not top-tier)
- IEEE co-sponsored
- Indexed: Scopus, Ei Compendex
- NOT CORE ranked (unlike ICML A*, NeurIPS A*)
- Lower citation rate than top venues

**Why consider it?**:
- ✅ Fast publication (6 months from now)
- ✅ Legitimate IEEE proceedings
- ✅ Conference presentation opportunity
- ✅ Builds publication record

**Why NOT priority**:
- ❌ Lower prestige than JMLR/NeurIPS
- ❌ Less visibility in ML community
- ❌ Lower citation impact

**Action**:
1. Convert to LaTeX immediately
2. Submit by December 25, 2025
3. Present in Berlin if accepted

**IMPORTANT**: Can submit to ICMLT AND later to NeurIPS/JMLR if ICMLT rejects (no conflict)

---

### 4️⃣ **Long-term: JMLR (Peer-reviewed Journal)**

**Timeline**: Rolling submission (no deadline)
**Format**: **JMLR LaTeX template required** (`jmlr2e.sty`)
**Page Limit**: No limit
**Acceptance Rate**: ~20%
**DOI**: Assigned by JMLR after acceptance

**Requirements**:
- Use `jmlr2e.sty` style file
- 8.5" × 11" letter size (NOT A4)
- Single column, Times Roman
- 1.25" left/right margins
- Use natbib for citations (`\citep{}`, `\citet{}`)

**Template**:
- Download from http://www.jmlr.org/format/
- Use sample paper as template

**Benefits**:
- Open access (no publication fee!)
- Prestigious journal
- No page limit (can include full details)
- Indexed in major databases

**Timeline**:
- Submit anytime
- Review: 3-6 months
- Revisions: 1-2 rounds
- Publication: 6-12 months total

**Action**:
1. Convert paper to JMLR LaTeX format
2. Expand to include full mathematical details
3. Submit via JMLR website
4. Respond to reviews

---

## Format Comparison

| Venue | Format | Review | DOI | Timeline |
|-------|--------|--------|-----|----------|
| **GitHub/Zenodo** | Markdown | None | ✅ Zenodo | Immediate |
| **arXiv** | LaTeX → PDF | None | ❌ (uses arXiv ID) | 1-2 weeks |
| **NeurIPS 2025** | LaTeX (neurips_2025.sty) | Peer-review | ✅ PMLR | May → Dec 2025 |
| **JMLR** | LaTeX (jmlr2e.sty) | Peer-review | ✅ JMLR | 6-12 months |

---

## Recommended Strategy

### Phase 1: Pre-print (NOW)
1. ✅ Publish GitHub repo with Markdown paper
2. ✅ Get Zenodo DOI (10.5281/zenodo.XXXXXX)
3. ⏳ Convert paper to LaTeX
4. ⏳ Submit to arXiv (cs.LG)

### Phase 2: Peer-review (2026)
5. **First attempt**: Submit to ICMLT 2026 (deadline Dec 25, 2025)
   - Fast decision (Jan 25, 2026)
   - No conflict with arXiv preprint
6. **If ICMLT accepts**: Present in Berlin + submit extended version to JMLR
7. **If ICMLT rejects**: Submit to JMLR or wait for NeurIPS 2026

### Phase 3: Publication (2025-2026)
8. Address reviewer comments
9. Final publication with DOI
10. Update Zenodo/arXiv with link to published version

---

## ArXiv Preprint Policy - CRITICAL ✅

### **¿Todas las venues aceptan preprints de arXiv?**

**✅ SÍ - arXiv NO cuenta como "dual submission"**

**Confirmado para**:
- ✅ **NeurIPS**: "Existence of non-anonymous preprints (arXiv) will not result in rejection"
- ✅ **ICML**: "Publication at arXiv explicitly does not conflict with ICML"
- ✅ **JMLR/TMLR**: "You can submit even if a preprint already exists online"
- ✅ **ICMLT**: Standard practice (IEEE conferences accept arXiv preprints)

### **Dual Submission Policy**

**❌ NOT ALLOWED**: Submit to multiple **archival** venues simultaneously
- Cannot submit to NeurIPS + ICML at the same time
- Cannot submit to JMLR while under review at NeurIPS

**✅ ALLOWED**: arXiv + one archival venue
- Can post to arXiv + submit to NeurIPS
- Can post to arXiv + submit to JMLR
- Can post to arXiv + submit to ICMLT

### **Strategy Implications**

You can **safely**:
1. ✅ Publish to GitHub/Zenodo now
2. ✅ Post to arXiv in 1-2 weeks
3. ✅ Submit to ICMLT (Dec 25, 2025)
4. ✅ If ICMLT rejects → submit to JMLR
5. ✅ If JMLR rejects → submit to NeurIPS 2026

**This is the standard workflow in ML research!**

---

## Multiple DOIs Explained

You will have **multiple identifiers** that coexist:

1. **Zenodo DOI** (10.5281/zenodo.XXXXXX)
   - Pre-print version
   - Permanent archival
   - Citable immediately
   - Use in CV as "preprint"

2. **arXiv ID** (arXiv:2025.XXXXX)
   - Pre-print version
   - NOT a DOI (just an identifier)
   - Highly visible in ML community
   - Indexed by Google Scholar

3. **Journal/Conference DOI** (10.XXXX/venue.YYYY)
   - Peer-reviewed version
   - Assigned by PMLR (NeurIPS) or JMLR
   - Use in CV as "conference/journal paper"
   - Higher prestige

**Citation hierarchy**:
- Before publication: Cite Zenodo DOI or arXiv ID
- After publication: Cite journal/conference DOI
- In final published paper: Note "preprint available at..."

---

## Next Actions

### Immediate (this week):
- [x] Clean repository (remove workflow files)
- [ ] Publish to GitHub
- [ ] Enable Zenodo
- [ ] Get Zenodo DOI
- [ ] Update DOI in all files

### Short-term (1-2 weeks):
- [ ] Convert Markdown → LaTeX (basic article class)
- [ ] Submit to arXiv
- [ ] Update README with arXiv badge

### Medium-term (before May 2025):
- [ ] Convert to NeurIPS LaTeX format
- [ ] Condense to 9 pages
- [ ] Anonymize
- [ ] Prepare for NeurIPS submission

### Backup plan:
- [ ] Convert to JMLR LaTeX format (if NeurIPS rejects)
- [ ] Submit to JMLR

---

## Current Repository Structure

**Pre-print format** (Markdown):
```
PP25-CHAOTIC_ATTRACTOR_COMPRESSION/
├── README.md                       # Main documentation
├── LICENSE                         # MIT + CC-BY 4.0
├── CITATION.cff                    # Citation metadata
├── .zenodo.json                    # Zenodo metadata
├── CHANGELOG.md                    # Version history
├── PUBLICATION_STRATEGY.md         # This file
│
├── paper/
│   └── PAPER_CHAOTIC_ATTRACTOR_COMPRESSION.md  # Markdown (pre-print)
│
├── code/                           # Rust implementation
└── supplementary/                  # Additional materials
```

**After LaTeX conversion**, add:
```
├── paper/
│   ├── PAPER_CHAOTIC_ATTRACTOR_COMPRESSION.md  # Original Markdown
│   ├── paper.tex                               # LaTeX (arXiv)
│   ├── paper_neurips.tex                       # NeurIPS format (future)
│   └── paper_jmlr.tex                          # JMLR format (future)
```

---

**Contact**: Francisco Molina Burgos <pako.molina@gmail.com>
**ORCID**: 0009-0008-6093-8267
**Last updated**: 2025-11-22
