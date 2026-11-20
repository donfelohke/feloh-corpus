# FELOH Research Note — GENJE Movement IR and Motion Systems

**Date:** 2026-11-20  
**Status:** RESEARCH / CROSS-DOMAIN INDEX  
**Canonical specialist home:** [GENJE](https://github.com/donfelohke/Genje)  
**Shared authority:** FELOH Corpus  
**Implementation status:** Research documentation only; no new runtime, dataset or product is claimed.

## Research position

GENJE owns the creative and embodied research: movement, choreography, notation, Genge and other music practices, livecoding, performance and choreohacking. The new [GENJE Movement IR and Motion Research specification](https://github.com/donfelohke/Genje/blob/main/docs/GENJE-MOVEMENT-IR-AND-MOTION-RESEARCH-2026-11-20.md) consolidates the recent LaMoGen audit and comparative motion research into a proposed human-authored Movement Intermediate Representation.

The recommendation is **not** to adopt LaMoGen/LabanLite as GENJE's canonical representation. Instead:
- GENJE owns a semantic, temporal and provenance-bearing Movement IR.
- Labanotation, Motif, LMA and other notation vocabularies remain distinct methods connected by explicit adapters.
- Music alignment, measured kinematics, observation, generated motion and authored choreography remain distinct artefacts.
- Every conversion records assumptions, uncertainty, unsupported concepts and information loss.
- Human authorship, performer correction, consent, context and community authority remain first-class.

## Key technical findings

1. **LaMoGen (CVPR 2026)** demonstrates the value of an LLM-guided symbolic layer between language and motion generation. Its LabanLite codebook is a computational adaptation, not full Labanotation or LMA. Its benchmark distribution is locomotion-heavy, and its evaluation does not establish cultural validity, groove or choreographic quality.
2. **LLaMo (CVPR 2026)** is a useful continuous-token counterpoint to discrete symbolic representations; its motion-generation performance does not make its latent space a human-readable choreography score.
3. **LAMP (CVPR 2026)** is a structured language-to-trajectory system for dynamic objects and cameras in controllable video generation. It is a motion-DSL reference, not a human-dance generation model.
4. **FACT / AI Choreographer (ICCV 2021)** established music-conditioned 3D dance generation alongside the AIST++ dataset. AIST++ is a technical benchmark, not a culturally representative African movement corpus.
5. **FineDance (ICCV 2023), DanceLDM (2026) and ChoreDiffusion (2026)** extend full-body, music-conditioned, multi-style and beat-aware generation. Their datasets, terms and evaluation regimes require individual review.
6. Motion-capture-to-Labanotation studies address the reverse direction from LaMoGen's text-to-motion pipeline. Automated outputs must remain candidate annotations subject to practitioner review.

## Method and cultural boundaries

- No universal African movement grammar is assumed.
- Turkana, Ateker, Genge and other locally situated work requires practitioner-led terminology, context and review.
- A measured velocity is not a qualitative Effort judgement; a pose estimate is not a semantic event; a generated sequence is not an authored performance.
- No identity recognition, person scoring, hidden profiling or inference of health, emotion, personality, intention or capability from movement.
- Camera/MoCap research is a later optional track. Begin with manual scores, participant-authored annotations and synthetic examples.
- Dataset and media access is not permission to reuse or publish. Record licences, consent, retention and restrictions.

## Ecosystem routing

| Responsibility | Canonical home |
|---|---|
| Movement IR, notation adapters, choreography, music/performance mappings and GENJE research | [GENJE](https://github.com/donfelohke/Genje) |
| Shared source evidence, research taxonomy, claim status and cross-domain governance | FELOH Corpus |
| Participant-directed reflection on chosen records; no authoritative performer interpretation | [IKAI](https://github.com/donfelohke/Ikai) |
| Reproducible local infrastructure and isolated technical adapters | [WARENA](https://github.com/donfelohke/WARENA) |

This is a research routing decision, not a new practice domain or product. The four-domain F3L0H architecture remains unchanged.

## Selected source register

- Jiang et al., [LaMoGen (arXiv:2603.11605)](https://arxiv.org/abs/2603.11605), CVPR 2026; [source repository](https://github.com/jjkislele/LaMoGen).
- Li et al., [LLaMo — CVPR 2026](https://openaccess.thecvf.com/content/CVPR2026/html/Li_LLaMo_Scaling_Pretrained_Language_Models_for_Unified_Motion_Understanding_and_CVPR_2026_paper.html).
- Kizil et al., [LAMP — CVPR 2026](https://openaccess.thecvf.com/content/CVPR2026/html/Kizil_LAMP_Language-Assisted_Motion_Planning_for_Controllable_Video_Generation_CVPR_2026_paper.html).
- Li et al., [AI Choreographer / FACT and AIST++ — ICCV 2021](https://openaccess.thecvf.com/content/ICCV2021/html/Li_AI_Choreographer_Music_Conditioned_3D_Dance_Generation_With_AIST_ICCV_2021_paper.html); [AIST++ documentation and terms](https://google.github.io/aistplusplus_dataset/).
- Li et al., [FineDance — ICCV 2023](https://li-ronghui.github.io/finedance); [dataset/software licence](https://github.com/THUSIGSICLAB/FineDance/blob/main/LICENSE).
- Su et al., [DanceLDM (2026)](https://doi.org/10.1007/s00530-026-02311-z).
- Gao et al., [ChoreDiffusion (2026)](https://doi.org/10.3390/info17080808).
- [LMA reliability study — PLOS ONE (2019)](https://journals.plos.org/plosone/article?id=10.1371/journal.pone.0218179).
- Osei (2020), [Documenting Ghanaian dances through Labanotation](https://www.uew.edu.gh/theatre-arts/staff/laosei/publications/29001/detail).
- Grim-Feinberg and Wong Santos, [Movement Notation and the Analysis of Embodied Knowledge](https://jashm.press.uillinois.edu/22.2/grim-feinberg.html).

African movement documentation leads are not a complete literature survey. Further source discovery must include African-led institutions, practitioners, languages and region-specific archives. Do not claim an absence of systems based only on this research pass.
