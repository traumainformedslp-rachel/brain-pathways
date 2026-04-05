# Neural Pathways of Literacy, Learning & Trauma

**An interactive, evidence-based brain diagram for trauma-informed literacy intervention education.**

![License: CC BY-NC 4.0](https://img.shields.io/badge/License-CC%20BY--NC%204.0-lightgrey.svg)
![No Build Required](https://img.shields.io/badge/Build-None_Required-green.svg)

---

## Overview

This interactive medial sagittal brain diagram visualizes three overlapping functional connectivity networks:

| Network | Color | Key Circuits |
|---------|-------|-------------|
| **The Reading Brain** | Blue | Frontal (L-IFG), Parietal (angular gyrus, SMG), Occipitotemporal (vOT/VWFA) |
| **The Learning Brain** | Gold | dlPFC, ACC, thalamus, basal ganglia, hippocampus, cerebellum |
| **The Trauma Brain** | Red (dashed) | Amygdala, mPFC/vmPFC, ACC, insula, MCC, hippocampus, PCC |

The diagram highlights **overlap zones** where these networks share neural real estate — particularly the **anterior cingulate cortex (ACC)**, which Langer et al. (2019) identified as showing reduced cortical thickness across *all* clinical groups (reading disability, ADHD, and their comorbid form).

## Features

- **Dark/light theme** toggle with persistent preference (Outfit + Space Mono typography)
- **Guided tour** on first visit — walks through the three networks, region exploration, and clinical implications
- **Toggle pathways** on/off to isolate or compare any combination of networks
- **Click any region** for a detail card with functional role, pathway membership, and peer-reviewed evidence
- **Searchable region list** — filter 20 brain regions by name
- **Medial/lateral view toggle** — switch between sagittal and lateral perspectives
- **Clinical implications panel** synthesizing intervention-relevant findings
- **Reading circuit labels** (F, P, OT) mapped to Marks' (2025) three-circuit model
- **Keyboard accessible** — regions are focusable and activatable via Enter/Space
- **Zero build tools** — single HTML file, open in any browser or deploy to GitHub Pages
- **Responsive** — works on desktop, tablet, and mobile
- **Print-friendly** — controls hidden, cards styled for paper output

## Usage

### Local
```
Open index.html in any modern browser.
```

### GitHub Pages
1. Push this repo to GitHub
2. Go to **Settings → Pages → Source: main branch**
3. Your diagram is live at `https://yourusername.github.io/brain-pathways/`

### Embed
```html
<iframe src="https://yourusername.github.io/brain-pathways/"
        width="100%" height="800" frameborder="0"></iframe>
```

## Evidence Base

Every region description and connection is grounded in peer-reviewed neuroimaging and neuropsychological research. No region is included without supporting fMRI, structural MRI, or meta-analytic evidence.

### Primary Sources

| Citation | Contribution |
|----------|-------------|
| **Boccia, M., et al. (2016).** Different neural modifications underpin PTSD after different traumatic events. *Brain Imaging and Behavior, 10*, 226–237. | ALE meta-analysis defining the PTSD neural network. |
| **Langer, N., et al. (2019).** Comorbidity of reading disabilities and ADHD. *Human Brain Mapping, 40*, 2677–2698. | ACC reduced in ALL clinical groups — shared risk factor. |
| **Sun, D., et al. (2024).** The role of occipitotemporal network for speed-reading. *Neuroscience Bulletin, 40*(9), 1261–1273. | Occipitotemporal connectivity during speed reading. |
| **Carrion, V. G., Wong, S. S., & Kletter, H. (2013).** Neuroimaging and cognitive functioning in pediatric PTSD. *J. Family Violence, 28*, 53–61. | Review of pediatric PTSD neuroimaging. |
| **Nijdam, M. J., et al. (2018).** Neurocognitive functioning over trauma-focused psychotherapy. *Br. J. Clinical Psychology, 57*, 436–452. | Reversibility evidence: cognition improved after therapy. |
| **Marks, R. A. (2025).** Neurodiversity in Action: Understanding the brain basis of dyslexia. Purdue CLLER Practice Brief. | Three-circuit reading brain model (frontal, parietal, OT). |

### Additional References

| Citation | Contribution |
|----------|-------------|
| Carrion, V. G., et al. (2007). Stress predicts brain changes in children. *Pediatrics, 119*, 509–516. | PTSD severity + cortisol predict hippocampal volume reduction. |
| Carrion, V. G., et al. (2008). PTSD symptoms and brain function during response-inhibition. *Depression and Anxiety, 25*, 514–526. | Decreased middle frontal, increased ACC in PTSD during Go/No-Go. |
| D'Mello, A. M., & Gabrieli, J. D. (2018). Cognitive neuroscience of dyslexia. *LSHSS, 49*(4), 798–809. | Comprehensive review of dyslexia neuroscience. |
| Dehaene, S., & Cohen, L. (2011). The unique role of the VWFA in reading. *Trends in Cognitive Sciences, 15*(6), 254–262. | VWFA specialization for orthographic processing. |
| De Bellis, M. D., et al. (2002). STG volumes in maltreated children with PTSD. *Biological Psychiatry, 51*, 544–555. | Larger STG volumes in pediatric PTSD. |
| De Bellis, M. D., & Kuchibhatla, M. (2006). Cerebellar volumes in pediatric PTSD. *Biological Psychiatry, 60*, 697–703. | Reduced cerebellar volume in pediatric PTSD. |
| Kovelman, I., et al. (2012). Brain basis of phonological awareness in dyslexia. *Cerebral Cortex, 22*(4), 754–764. | Phonological processing differences present in auditory domain. |
| Pugh, K. R., et al. (2001). Neurobiological studies of reading and reading disability. *J. Communication Disorders, 34*(6), 479–492. | Dorsal and ventral reading pathways. |
| Naegeli, C., et al. (2018). Locus coeruleus volume and functional connectivity in PTSD. *Biological Psychiatry, 83*, 158–167. | LC structural correlates of PTSD. |
| Clewett, D., et al. (2020). Locus coeruleus and memory. *Annals of the NY Academy of Sciences, 1473*, 26–37. | LC-NE modulation of memory encoding. |

## Design Decisions

- **Medial sagittal view** chosen to show subcortical structures (hippocampus, thalamus, amygdala, cingulate) invisible in lateral views but central to the trauma and learning networks.
- **Lateral view** available for cortical surface regions.
- **Dashed lines** for trauma pathways to visually distinguish disruption/dysregulation.
- **Triple-overlap highlighting** on ACC with distinct visual treatment.
- **Dark/light mode** with Outfit + Space Mono typography, matching the RTN Communication & Literacy design system.

## Important Caveats

This diagram represents **simplified functional connectivity** based on group-level neuroimaging findings. As Marks (2025) emphasizes:

> An individual brain image is insufficient to diagnose dyslexia. There is so much variability in the patterns of brain activity within groups of readers, both skilled and impaired.

The same principle applies to all three networks. Region placements represent approximate functional zones, not precise anatomical boundaries. Pathways represent functional connectivity patterns, not literal white matter tracts.

## License

This work is licensed under [Creative Commons Attribution-NonCommercial 4.0 International (CC BY-NC 4.0)](https://creativecommons.org/licenses/by-nc/4.0/).

You are free to share and adapt this work for non-commercial purposes, provided you give appropriate credit. If you use or adapt this diagram, please cite as:

> Norton, R. T. (2025). *Neural Pathways of Literacy, Learning & Trauma: Interactive Diagram.* RTN Communication & Literacy. https://github.com/traumainformedslp-rachel/brain-pathways

For commercial licensing inquiries, contact via [rachelslp.org](https://rachelslp.org).

## Author

Created for **RTN Communication & Literacy** — a trauma-informed, neurodiversity-affirming speech-language pathology practice.

For questions about the research basis or educational use, contact via [rachelslp.org](https://rachelslp.org).
