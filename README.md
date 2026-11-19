# *Macropus giganteus* Shaw, 1790 — Eastern Grey Kangaroo

**Repository:** `https://github.com/intenteco/macropus-giganteus`  
**Taxon Locators:** `urn:qualia:taxon:macropus_giganteus` · `did:q42:taxon:macropus_giganteus`  
**Work-Packet Status:** `ECO-WP-11A` (Species Ontology, `.q42` Compilation & Claims Dossier) and `ECO-WP-11B` (3-Layer Zoological CAD, 24-Joint PGA Rig, PBR, `.emf`, `.qac`, `.hmc` & Orthographic Previews) complete; `ECO-WP-GATE-W3` human domain/visual/rights review pending (`reported_status: "incomplete"`).

---

## 1. Taxonomic Concept & Verified Identifiers

*Macropus giganteus* Shaw, 1790 (Eastern Grey Kangaroo, Macropodidae) is Australia's largest living marsupial grazer of open grassy woodlands and sclerophyll forests across South-Eastern Australia, distinguished diagnostically from *Osphranter rufus* (bare black rhinarium) and *Macropus fuliginosus* (darker brown-grey pelage and more extensively dark muzzle) by its **finely haired rhinarium between the nostrils leaving only a narrow bare black rim around each nostril**.

| Scheme | Identifier / URI | Status | Notes |
|---|---|---|---|
| Qualia Taxon URN | `urn:qualia:taxon:macropus_giganteus` | Asserted | Primary QualiaDB concept URI |
| Q42 DID Locator | `did:q42:taxon:macropus_giganteus` | Asserted | Unallocated mathematical locator |
| Australian Faunal Directory (AFD) | `https://biodiversity.org.au/afd/taxa/f2f43ef9-89fd-4f89-8b06-0842e86cfe06` | Verified | Accepted taxon *Macropus giganteus* Shaw, 1790 |
| Atlas of Living Australia (ALA) | `https://bie.ala.org.au/species/https://biodiversity.org.au/afd/taxa/f2f43ef9-89fd-4f89-8b06-0842e86cfe06` | Verified | Species profile & regional records |
| GBIF Backbone (Species) | `https://www.gbif.org/species/5219981` (`GBIF:5219981`) | Verified | Accepted species (*Macropus* genusKey `2440171`, Macropodidae familyKey `9372`) |
| NCBI Taxonomy | `NCBITaxon:9317` | Verified | *Macropus giganteus* (nominal subsp. `NCBITaxon:39422`) |
| iNaturalist AU | `https://www.inaturalist.org/taxa/42888-Macropus-giganteus` (`42888`) | Verified | Verified regional citizen-science taxon |

---

## 2. Anatomical Subsystems (`UBERON`)

All anatomical parts are keyed to `UBERON` identifiers in [`ontology/taxon.ttl`](ontology/taxon.ttl) and [`ontology/index.ttl`](ontology/index.ttl):

- **Cranial & Facial System (`UBERON:0000975`):**
  - Elongated, finely sculpted grazing macropodid skull with arched cranial vault, distinct forehead stop, and long slender tapering muzzle.
  - **Finely haired rhinarium (`UBERON:0001756`)** between the nostrils with only a narrow bare black rim around each nostril.
  - Large dark liquid eyes (`UBERON:0000970`) beneath pronounced supraorbital ridges; tall, independently mobile oval-pointed cupped external pinnae (`UBERON:0001757`, `0.11–0.15 m`).
- **Bipedal Saltatorial Axial & Pelvic System (`UBERON:0001130`):**
  - Upright alert or pentapedal grazing posture; slender neck and narrow sloping shoulders broadening into a deep muscular lumbar/sacral spine.
  - Marsupial epipubic bones (`UBERON:0003661`) supporting a **forward-opening female marsupium pouch (`UBERON:0001831`, 4 teats)**.
  - Massive muscular tapered **pentapedal counterweight/propulsive tail (`UBERON:0002415` / `UBERON:0001095`)**, `0.95–1.15 m` long with a dark charcoal-tipped distal third.
- **Forelimb & Elastic-Tendon Hindlimb System (`UBERON:0002102` & `UBERON:0002103`):**
  - 5-clawed forelimbs (`UBERON:0002102`) for grooming, agonistic male boxing, pentapedal weight support, and evaporative **thermoregulatory forearm-licking** over a dense superficial ventral vascular plexus.
  - Hypertrophied gluteal, quadriceps, and gastrocnemius/plantaris hindlimbs coupled to long **Achilles / gastrocnemius & plantaris elastic tendons (`UBERON:0001388`, $k \approx 62{,}000\text{ N/m}$, max strain $\approx 7.8\%$, $\ge 54\%$ elastic energy recovery)**.
  - Elongated metatarsal IV, vestigial hallux absent, **syndactylous grooming digits II–III (`UBERON:0002389`)**, massive central load-bearing clawed **digit IV**, and lateral stabilizing clawed **digit V** (`UBERON:0002387`).
- **Osteology, Myology, Dentition & Pelage (`UBERON:0001434`, `UBERON:0001630`, `UBERON:0002199`):**
  - Diprotodont grazing dentition $I\frac{3}{1}\ C\frac{0}{0}\ PM\frac{1}{1}\ M\frac{4}{4}$ (`UBERON:0001759`) with conveyor-like forward-progressing molar progression.
  - Soft woolly silver-grey to mouse-grey dorsal pelage, pale silver-buff flanks, white-cream chest/belly, and dark charcoal-tipped paws, pes, ear margins, and distal tail third.

---

## 3. Biophysical, Morphometric, Allometric & ROM Parameters

| Parameter | Range / Value | Notes |
|---|---|---|
| Head–body length | `0.95 – 1.50 m` | Adult morphometric range |
| Tail length | `0.95 – 1.15 m` | Heavy pentapedal & dynamic counterweight tail |
| Erect standing height | `1.30 – 2.10 m` | Does `1.30–1.60 m`; alpha boomer bucks up to `2.10 m` |
| Adult mass | `24.0 – 85.0 kg` | Does `24.0–38.0 kg`; adult bucks `50.0–85.0 kg` (`alpha_boomer_buck` `66–85 kg`) |
| Basal Metabolic Rate (BMR) | `49.7 W` (at `45 kg`) / `66.2 W` (at `66 kg`) | $\text{BMR}(M) = 2.86 \cdot M^{0.75}\text{ W}$ ($T_b \approx 36.2^\circ\text{C}$) |
| Hindlimb & tail allometry | $L_{\text{pes}} = 0.112 M^{0.34}$, $L_{\text{tibia}} = 0.155 M^{0.35}$ | $L_{\text{femur}} = 0.089 M^{0.33}$, $L_{\text{tail}} = 0.305 M^{0.32}$ (metres) |
| Elastic tendon & bone mechanics | $E_{\text{bone}} = 18.0\text{ GPa}$, $E_{\text{tendon}} = 1.2\text{ GPa}$ | $U = \frac{1}{2} k_{\text{achilles}} \Delta L^2$, $k \approx 62{,}000\text{ N/m}$ |
| Locomotor modes | Pentapedal graze (`0.4–1.2 m/s`) / Saltatorial hop (`5.0–17.5 m/s`) | Cruising hop `6.5–10.0 m/s` with $\ge 54\%$ elastic recoil recovery |

### Joint Range of Motion (`q42:rom:*`, 24-Joint `macropodid_saltatorial` Rig, Radians)

| Joint | Healthy Min (rad) | Healthy Max (rad) | Injury Threshold (rad) | Post-Injury Guarding |
|---|---|---|---|---|
| `hip` | `-0.58` | `+1.48` | `1.68` | `q42:obligateInjuredAsymmetricLimpGait` |
| `knee` | `-1.78` | `-0.10` | `-1.98` | `q42:obligateInjuredAsymmetricLimpGait` |
| `ankle` | `-1.02` | `+1.24` | `1.42` | `q42:obligateInjuredAsymmetricLimpGait` |
| `pes_digit_iv` | `-0.62` | `+0.85` | `1.05` | `q42:obligateInjuredAsymmetricLimpGait` |
| `shoulder` | `-0.70` | `+1.22` | `1.42` | `q42:obligateForepawProtectiveGuarding` |
| `elbow` | `-1.68` | `-0.08` | `-1.88` | `q42:obligateForepawProtectiveGuarding` |
| `wrist` | `-0.85` | `+0.70` | `-1.05` | `q42:obligateForepawProtectiveGuarding` |
| `spine` | `-0.55` | `+0.68` | `0.85` | `q42:obligateNociceptiveEarPinBack` |
| `neck` | `-0.78` | `+0.68` | `0.96` | `q42:obligateNociceptiveEarPinBack` |
| `tail` | `-0.68` | `+0.82` | `0.98` | `q42:obligateInjuredAsymmetricLimpGait` |

### `InstanceState64` Ontogenetic Stages

Deterministic 64-byte per-instance phenotype parameterization (`seed`, `ontogenetic_age_norm`, `height_scale`, `site_vigor`, `environmental_stress`, `sex_dimorphism_flag`, `pouch_occupancy_flag`, `pelage_silver_shift`, `forelimb_hypertrophy_01`) spans:
1. `pouch_joey` (`0.00–0.22`)
2. `young_at_foot` (`0.22–0.42`)
3. `subadult_flyer` (`0.42–0.65`)
4. `adult_doe` (`0.65–1.00`, `24–38 kg`, `1.30–1.60 m` erect, forward-opening marsupium)
5. `alpha_boomer_buck` (`0.65–1.00`, `66–85 kg`, up to `2.10 m` erect, hypertrophied pectoral & forelimb musculature)

---

## 4. Ecology & South-Eastern Australian Biocultural Provenance

- **Diet & Habitat (`ro:0002470`, `ro:0002303`):** Native grass-layer grazer feeding on *Poa labillardierei*, *Themeda triandra*, and *Microlaena stipoides* across *Eucalyptus melliodora* grassy box-gum woodlands, *E. camaldulensis* floodplain woodlands, and open sclerophyll forests across South-Eastern Australia (`0–1800 m`).
- **Biocultural Custodianship (Social Permissive Commons `SPC`):**
  Attributed across **Bundjalung, Gumbaynggirr, Gadigal, Dharug, Yuin, Ngarigo, Walgalu, Wiradjuri, GunaiKurnai, Wurundjeri, Boonwurrung, and Wadawurrung Country** under Local Contexts TK/BC and CARE Principles.

---

## 5. Repository Artifacts & Verification

| Artifact | Purpose | Status |
|---|---|---|
| [`synth.project.json`](synth.project.json) | Synth project descriptor (`synth.project/v1`) | Authored |
| [`.synth/bookmarks.json`](.synth/bookmarks.json) | Authoritative AFD, ALA, GBIF, NCBI, NSW BioNet/DPE, VBA, Australian Museum, iNaturalist AU, TERN & TK/BC URLs | Authored |
| [`.synth/jobs.json`](.synth/jobs.json) | Reproducible Turtle -> `.q42` compile job definitions | Authored |
| [`ontology/taxon.ttl`](ontology/taxon.ttl) | Taxon concept, `UBERON` subsystems, ROM bounds, allometry, `InstanceState64`, trophic & Country graph | Compiled (`553` quins) |
| [`ontology/index.ttl`](ontology/index.ttl) | DCAT dataset & distribution manifest | Compiled (`76` quins) |
| [`dist/taxon.q42`](dist/taxon.q42) | Sealed NQuin taxon & biophysical ontology | Compiled & queried via `query_sparql` (`553` bindings) |
| [`dist/index.q42`](dist/index.q42) | Sealed NQuin package index | Compiled & queried via `query_sparql` (`76` bindings) |
| [`dossier/claims.json`](dossier/claims.json) | Pinned 193-row claims ledger (`2026-10-24.2`) + `VERT-01..14` | Updated for `ECO-WP-11B` (`reported_status: "incomplete"`) |
| [`source/macropus-giganteus.vibe`](source/macropus-giganteus.vibe) | 103-part multi-station cubic loft 3-layer CAD (`UBERON:*` / `ENVO:*`), 24-joint PGA rig, `chiang_hair` BSDF, `.emf` & `.qac` (`377,510` B) | Authored (`sha256: d9daf981cc5fd64da988c9f45bfe5391130f8b92e60e78d9c73cd3f66ee3ece9`) |
| [`source/actuation.vibe`](source/actuation.vibe) | `InstanceState64`, Achilles recoil (`k=62000 N/m`), gait state machine, ear-swivel & aura/pulse module (`7,948` B) | Verified via `vibe_check` (`valid: true`, `0` errors) |
| [`dist/macropus-giganteus.hmc`](dist/macropus-giganteus.hmc) | Replay-verified Hypermedia Container (`production16`, `4,111,631` B, `12` outputs) | `strict_replay_verified: true` (`sha256: 50a10f13d51d8688d55d31cafe52e42c69db078298f6193a6138cdf547365386`) |
| [`dist/macropus-giganteus.10d`](dist/macropus-giganteus.10d) | Multi-part 3-layer 10D manifold (`23,600` vertices, `46,152` triangles, `y ∈ [0.000, 1.740]` m, `657,856` B) | Produced (`sha256: d90d0da775548e19106c7d04aa16f93ba268779f4439bd47d31c8dde9b72d634`) |
| [`dist/macropus-giganteus-pbr.10d`](dist/macropus-giganteus-pbr.10d) | Woolly silver-grey PBR + topology + BVH 10D manifold (`369,328` B) | Produced (`sha256: 3ea7fa4efc15d41fa297fb98ad8172361b4033097366848a7c05f9cb91e5c990`) |
| [`dist/macropus-giganteus-field.emf`](dist/macropus-giganteus-field.emf) | Endothermic (`36.2 °C`) & saltatorial bioelectric `Q42EMF64` volume (`1,578,752` B) | Produced (`sha256: 2d1b6d75e56beea4049514200877f766311cbaccb16009598ee171ed63c3d4b9`) |
| [`dist/macropus-giganteus-call.qac`](dist/macropus-giganteus-call.qac) | Guttural cough (`165 Hz`) & double hind-foot thump (`65 Hz`) `.qac` v1 (`868,736` B) | Produced (`sha256: d8e5b3e1fb3e70e1aeb27ebab9f75e55cdfcda94d681a04b435c9bbfefe9899d`) |
| [`dist/rig-packet.json`](dist/rig-packet.json) | 24-joint `macropod_saltatorial` small-LLM behavior hook packet (`314` B) | Produced (`sha256: 37795e6a2de5f47492629aa184d1562c25fd4d0fa0b756faa13216a1d72dcf29`) |
| [`dist/receipt.json`](dist/receipt.json) | Synth `production16` build receipt (`strict_replay_verified: true`) | Authored (`sha256: 803503514fc136f323af90cda0e56b845ca155b3e40602babf3045fb362b71eb`) |
| [`previews/`](previews/) | `2048×2048` orthographic PNGs (`front`, `side`, `three-quarter`), `turnaround.png`, `blueprint.svg`, `spectral-slice.png`, `fur-*.png`, `hair-bsdf.png`, `review-receipt.json` | Rendered & visually inspected (`ECO-WP-GATE-W3` pending) |
