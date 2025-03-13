# -Preprocessing-Method-for-Dct-based-Image-compression
# Project Overview
This project implements a **Boundary tracing algorithms** and **correlation-based preprocessing method**  to reduce the ringing effect caused by the DCT.We propose a novel filtering method designed for block-DCT-based compression, with a specific focus on reducing ringing noise without causing significant detail degradation.This method involves assessing local characteristics through power spectrum distribution analysis and applying filtering accordingly. Importantly, this process, independentof the coding process, is compatible with existing encoders.
# Background
**DCT-based** compression methods, such as those employed in JPEG and MPEG, are extensively utilized for image storage and transmission. However, they often introduce artifacts, especially at low bit-rates. Although post-processing at the decoder side can alleviate this issue, it leaves existing decoders unaffected. To improve image quality at the encoder side, implementing noise reduction before compression proves beneficial.
# Key Features
* Applied a **correlation-based  preprocessing method** to reduce the ringing effect caused by the DCT.
* Developed a **Boundary tracing algorithms** algorithm to extract the shape or outline of objects.
* Successfully reduced the ringing effect , achieving a **higher Peak signal-to-noise ratio (PSNR)** compared to the traditional Low Pass Filter (LPF).
# Tools & Technologies
* Python (Simulation & Performance Analysis)
* correlation-based  preprocessing method
* Boundary tracing algorithms
