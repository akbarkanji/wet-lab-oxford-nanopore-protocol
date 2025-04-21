# ONT Rapid Barcoding Kit Protocol (SQK-RBK114.24 / SQK-RBK114.96)

This protocol outlines the steps for barcoding DNA samples using the Oxford Nanopore Rapid Barcoding Kit.

## Materials Required

- Rapid Barcoding Kit (SQK-RBK114.24 or SQK-RBK114.96)
- Nuclease-free water
- DNA samples (ideally 400 ng per sample in ≤7.5 µL)
- Thermocycler or heat block
- Magnetic beads (AMPure XP or equivalent)
- Magnetic rack
- Nuclease-free tubes
- Pipettes and filtered tips

---

## Step-by-Step Protocol

### 1. Prepare DNA

- Dilute each DNA sample to 400 ng in a total volume of **7.5 µL** or less with nuclease-free water.

---

### 2. Barcoding Reaction

- To a nuclease-free tube, add:

  | Reagent       | Volume |
  |---------------|--------|
  | DNA sample    | 7.5 µL |
  | RB (Rapid Barcode) | 2.5 µL |

- Mix gently by pipetting.

---

### 3. Incubation

- **Incubate at 30°C for 2 minutes.**
- **Heat at 80°C for 2 minutes** to inactivate the transposase.

---

### 4. Pooling Barcoded Samples

- Combine **2 µL** from each barcoded sample into a single tube.

---

### 5. Clean-Up with Magnetic Beads

- Add an equal volume of magnetic beads to the pooled library.
- Mix thoroughly by pipetting.
- Incubate at room temperature for 5 minutes.
- Place on magnetic rack and let stand until clear (~5 minutes).
- Remove and discard the supernatant.
- Wash twice with 200 µL of 70% ethanol.
- Air dry the beads (~2 minutes).
- Elute in 10 µL of nuclease-free water.

---

### 6. Proceed to Adapter Ligation or Sequencing

Follow the remaining steps in the ONT protocol to ligate adapters and load onto the flow cell.

---

## Notes

- Work on ice when possible.
- Avoid over-drying the beads.
- Store any unused barcodes at -20°C.

---

## References

- Oxford Nanopore Technologies SQK-RBK114.24 protocol [https://nanoporetech.com/]








