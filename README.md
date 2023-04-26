# proteoglycan-quant
a FIJI macro to quantify proteoglycans from RGB trichrome stained tissue

Rachel Wyetzner and Sakin Kirti, 10/13/2021
Proteoglycan Quantification for the Atit Lab

This macro should be used when you have pre-cropped images that exclude hair follicles of RGB Trichrome
stained skin and want to put them through ImajeJ for quantification of proteoglycan area and ECM area.

This macro can be used with 10x images only. If trying to run other magnification images through, 
you must change the scale value located in the for loop

This macro performs 2 functions
1. thresholds area of the ECM
2. exports results as a csv. file

Developed for and used in:
Jussila AR, Zhang B, Caves E, Kirti S, Steele M, Hamburg-Shields E, Lydon J, Ying Y, Lafyatis R, Rajagopalan S, Horsley V, Atit RP. Skin Fibrosis and Recovery Is Dependent on Wnt Activation via DPP4. J Invest Dermatol. 2022 Jun;142(6):1597-1606.e9. doi: 10.1016/j.jid.2021.10.025. Epub 2021 Nov 20. PMID: 34808238; PMCID: PMC9120259.
