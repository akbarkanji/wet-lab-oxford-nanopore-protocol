🧪 Oxford Nanopore Rapid Barcoding Protocol (SQK-RBK114.24 / SQK-RBK114.96)
📋 Overview
This protocol enables rapid barcoding of genomic DNA using the Rapid Barcoding Kit V14. The process involves:

Tagmentation: Simultaneous fragmentation and barcoding of DNA using a transposase.

Pooling and Cleanup: Combining barcoded samples and purifying the pooled library.

Adapter Ligation: Attaching sequencing adapters to the purified library.

Sequencing: Loading the prepared library onto a flow cell for sequencing.

🧰 Materials and Equipment
Reagents and Kits
Rapid Barcoding Kit V14: SQK-RBK114.24 or SQK-RBK114.96

AMPure XP Beads (Beckman Coulter)

80% Ethanol (freshly prepared)

Nuclease-Free Water

Qubit dsDNA HS Assay Kit (Invitrogen, Q32851)

Flow Cell Priming Kit V14 (EXP-FLP004)

Rapid Adapter Auxiliary V14 (EXP-RAA114)

Sequencing Auxiliary Vials V14 (EXP-AUX003)

Equipment
MinION, GridION, or PromethION device

R10.4.1 Flow Cells (FLO-MIN114)

Magnetic Rack

Thermocycler or Heat Block

Pipettes and Tips

Microcentrifuge Tubes

🧬 Input DNA Requirements
Quantity: 200 ng of high-quality genomic DNA per sample

Volume: Adjusted to 10 µL with Nuclease-Free Water

Quality: High molecular weight, A260/280 ratio ~1.8

🧪 Step-by-Step Protocol
1. Barcode Attachment (Tagmentation)
For each sample:

In a PCR tube, combine:

10 µL genomic DNA (200 ng)

2.5 µL Barcode (RBxx)

2.5 µL Fragmentation Mix (FRA)

Mix gently by pipetting.

Incubate at 30°C for 1 minute.

Immediately place on ice.

Note: The transposase simultaneously fragments the DNA and attaches barcoded tags.

2. Pooling and Cleanup
Pool 2 µL from each barcoded sample into a single tube.

Add 1.8x volume of AMPure XP beads to the pooled sample.

Incubate at room temperature for 5 minutes.

Place the tube on a magnetic rack until the solution clears.

Remove and discard the supernatant.

Wash the beads twice with 200 µL of freshly prepared 80% ethanol.

Air-dry the beads for 5 minutes.

Elute the DNA in 10 µL of Nuclease-Free Water.

3. Adapter Ligation
To the 10 µL of eluted DNA, add:

1 µL Rapid Adapter (RAP)

Mix gently by pipetting.

Incubate at room temperature for 5 minutes.

Note: Proceed to sequencing promptly after adapter ligation.

4. Flow Cell Priming and Library Loading
Prime the flow cell using the Flow Cell Priming Kit V14 (EXP-FLP004) as per manufacturer's instructions.

Prepare the sequencing mix:

37.5 µL Sequencing Buffer (SQB)

25.5 µL Loading Beads (LB)

12 µL Adapter-ligated library

Mix the sequencing mix gently by pipetting.

Load 75 µL of the sequencing mix onto the flow cell via the SpotON sample port.

🖥️ Sequencing Setup
Software: Use MinKNOW for sequencing control.

Kit Selection: Choose the appropriate kit (SQK-RBK114.24 or SQK-RBK114.96) in the software.

Basecalling: Enable live basecalling if desired.

Demultiplexing: Utilize MinKNOW, Guppy, or EPI2ME for barcode demultiplexing.

📝 Notes and Tips
DNA Quality: High-quality, high molecular weight DNA is crucial for optimal results.

Temperature Control: Maintain reagents and samples on ice when not in use.

Bead Cleanup: Ensure complete removal of ethanol during bead washing to prevent interference with downstream steps.

Sequencing Timing: Begin sequencing promptly after library preparation to ensure library integrity.

📚 References
Rapid Sequencing gDNA Barcoding Protocol – Oxford Nanopore Technologies
