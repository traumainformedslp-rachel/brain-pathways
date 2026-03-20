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

The diagram highlights **overlap zones** where these networks share neural real estate — particularly the **anterior cingulate cortex (ACC)**, which Langer et al. (2019) identified as showing reduced cortical thickness across *all* clinical groups (reading disability, ADHD, and their comorbid form). These overlaps are the core argument for why **literacy intervention without trauma-informed consideration may be working against active neural competition**.

## Features

- **Toggle pathways** on/off to isolate or compare any combination of networks
- **Click any region** for a detail card with functional role, pathway membership, and peer-reviewed evidence
- **Clinical implications panel** synthesizing intervention-relevant findings across all cited studies
- **Reading circuit labels** (F, P, OT) mapped to Marks' (2025) three-circuit model of the reading brain
- **Keyboard accessible** — regions are focusable and activatable via Enter/Space
- **Zero build tools** — single HTML file, open in any browser or deploy to GitHub Pages
- **Print-friendly** — controls hidden, cards styled for paper output

## Usage

### Local
```
Open index.html in any modern browser.
```

### GitHub Pages
1. Push this repo to GitHub
2. Go to **Settings → Pages → Source: main branch**
3. Your diagram is live at `https://yourusername.github.io/brain-pathways-diagram/`

### Embed
```html
<iframe src="https://yourusername.github.io/brain-pathways-diagram/"
        width="100%" height="800" frameborder="0"></iframe>
```

## Evidence Base

Every region description and connection in this diagram is grounded in peer-reviewed neuroimaging and neuropsychological research. No region is included without supporting fMRI, structural MRI, or meta-analytic evidence.

### Primary Sources

| Citation | Contribution to Diagram |
|----------|------------------------|
| **Boccia, M., et al. (2016).** Different neural modifications underpin PTSD after different traumatic events: an fMRI meta-analytic study. *Brain Imaging and Behavior, 10*, 226–237. | ALE meta-analysis defining the PTSD neural network: bilateral ACC, MCC, insula, hippocampus, thalamus, STG. Trauma-type specificity (MCC in physical/sexual abuse; PCC/hippocampus in combat). Amygdala *not* consistent in ALE. |
| **Langer, N., et al. (2019).** Comorbidity of reading disabilities and ADHD: Structural and functional brain characteristics. *Human Brain Mapping, 40*, 2677–2698. | Four-group comparison (RD, ADHD, COM, TYP): ACC reduced in ALL clinical groups (shared risk factor). Fusiform/STG hypoactivation specific to RD. SMA/ACC shared across tasks. Multiple deficit model support. |
| **Sun, D., et al. (2024).** The role of occipitotemporal network for speed-reading: An fMRI study. *Neuroscience Bulletin, 40*(9), 1261–1273. | Occipitotemporal connectivity during speed reading: iO → vOT → pSTS/aSTS pathway. DCM effective connectivity modulated by reading speed (aSTS → vOT inhibition). |
| **Carrion, V. G., Wong, S. S., & Kletter, H. (2013).** Update on neuroimaging and cognitive functioning in maltreatment-related pediatric PTSD. *Journal of Family Violence, 28*, 53–61. | Review of pediatric PTSD neuroimaging: reduced PFC, hippocampus, cerebellar volumes. Cortisol-hippocampus link. Cognitive deficits in attention, memory, executive function. Treatment implications. |
| **Nijdam, M. J., et al. (2018).** Neurocognitive functioning over the course of trauma-focused psychotherapy for PTSD. *British Journal of Clinical Psychology, 57*, 436–452. | Reversibility evidence: verbal memory, processing speed, and executive functioning improved after EMDR/BEP (d = 0.16–0.68). Greater PTSD symptom reduction → better post-treatment cognition. |
| **Marks, R. A. (2025).** Neurodiversity in Action: Understanding the brain basis of dyslexia. Purdue University Center for Literacy and Language Education and Research. Practice Brief. | Three-circuit reading brain model (frontal, parietal, occipitotemporal). Developmental shift from frontal → posterior. Brain differences predate reading onset. Dyslexia linked to oral language, not vision. Guiding principles: explicit, sequenced, data-driven. |

### Additional References

| Citation | Contribution |
|----------|-------------|
| Barzilay, R., et al. (2020). Structural brain patterns associated with traumatic stress resilience and susceptibility. *Adversity and Resilience Science, 1*(3), 179–190. | Structural correlates of trauma resilience vs. susceptibility in youth. |
| Zuk, J., et al. (2019). Multifactorial pathways facilitate resilience among kindergarteners at risk for dyslexia. *bioRxiv*. | Resilience pathways in at-risk readers; behavioral and neuroimaging longitudinal data. |
| D'Mello, A. M., & Gabrieli, J. D. (2018). Cognitive neuroscience of dyslexia. *Language, Speech, and Hearing Services in Schools, 49*(4), 798–809. | Comprehensive review of dyslexia neuroscience; underactivation patterns in parietal and occipitotemporal regions. |
| Kovelman, I., et al. (2012). Brain basis of phonological awareness for spoken language in children and its disruption in dyslexia. *Cerebral Cortex, 22*(4), 754–764. | Phonological processing differences in dyslexia present in auditory domain without print. |
| Carrion, V. G., et al. (2007). Stress predicts brain changes in children. *Pediatrics, 119*, 509–516. | Longitudinal: PTSD severity + cortisol independently predict hippocampal volume reduction. |
| Carrion, V. G., et al. (2008). PTSD symptoms and brain function during a response-inhibition task. *Depression and Anxiety, 25*, 514–526. | fMRI: decreased middle frontal, increased ACC/medial frontal in PTSD during Go/No-Go. |
| Carrion, V. G., et al. (2010a). Reduced hippocampal activity in youth with PTSD. *Journal of Pediatric Psychology, 35*, 559–569. | fMRI: reduced right hippocampal activation during memory retrieval in PTSD. |
| De Bellis, M. D., et al. (2002). Superior temporal gyrus volumes in maltreated children with PTSD. *Biological Psychiatry, 51*, 544–555. | Larger STG volumes in pediatric PTSD. |
| De Bellis, M. D., & Kuchibhatla, M. (2006). Cerebellar volumes in pediatric maltreatment-related PTSD. *Biological Psychiatry, 60*, 697–703. | Reduced cerebellar volume in pediatric PTSD. |
| Dehaene, S., & Cohen, L. (2011). The unique role of the visual word form area in reading. *Trends in Cognitive Sciences, 15*(6), 254–262. | VWFA specialization for orthographic processing. |
| Pugh, K. R., et al. (2001). Neurobiological studies of reading and reading disability. *Journal of Communication Disorders, 34*(6), 479–492. | Dorsal and ventral reading pathways; IFG, SMG, fusiform roles. |

## Design Decisions

- **Medial sagittal view** chosen to show subcortical structures (hippocampus, thalamus, amygdala, cingulate) that are invisible in lateral views but central to the trauma and learning networks.
- **Dashed lines** for trauma pathways to visually distinguish them and convey disruption/dysregulation.
- **Triple-overlap highlighting** on ACC with distinct visual treatment (dashed ring + multi-colored pathway dots) to emphasize the shared-risk finding.
- **Dark background** chosen for visual clarity of colored pathways and to match the aesthetic of neuroimaging presentations.
- **Newsreader + Source Code Pro** typography pairing for an editorial/scientific feel distinct from generic web fonts.

## Important Caveats

This diagram represents **simplified functional connectivity** based on group-level neuroimaging findings. As Marks (2025) emphasizes:

> An individual brain image is insufficient to diagnose dyslexia. There is so much variability in the patterns of brain activity within groups of readers, both skilled and impaired.

The same principle applies to all three networks shown here. Region placements represent approximate functional zones on a schematic sagittal view, not precise anatomical boundaries. Pathways represent functional connectivity patterns reported in the literature, not literal white matter tracts.

## License

This work is licensed under [Creative Commons Attribution-NonCommercial 4.0 International (CC BY-NC 4.0)](https://creativecommons.org/licenses/by-nc/4.0/).

You are free to share and adapt this work for non-commercial purposes, provided you give appropriate credit. If you use or adapt this diagram in academic presentations, courses, or publications, please cite as:

> Norton, R. T. (2025). *Neural Pathways of Literacy, Learning & Trauma: Interactive Diagram.* RTN Communication & Literacy. https://github.com/[username]/brain-pathways-diagram

For commercial licensing inquiries, contact via [rachelslp.org](https://rachelslp.org).

## Author

Created for **RTN Communication & Literacy** — a trauma-informed, neurodiversity-affirming speech-language pathology practice.

For questions about the research basis or educational use, contact via [rachelslp.org](https://rachelslp.org).
