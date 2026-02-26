# CoRe-GS: Coarse-to-Refined Gaussian Splatting with Semantic Object Focus
## Authors
Hannah Schieber, Dominik Frischmann, Simon Boche, Victor Schaack, Angela Schoellig, Stefan Leutenegger, and Daniel Roth

## Abstract
Fast and efficient reconstruction supports time-critical tasks such as tele-guidance and disaster response, where operators must quickly gain an accurate understanding of the environment. Full high-fidelity scene reconstruction is computationally expensive and often unnecessary when only specific points of interest (POIs) matter for timely decision making. We address this challenge with CoRe-GS, a semantic POI-focused Gaussian Splatting (GS) approach. Instead of optimizing every scene element uniformly, CoRe-GS first produces a fast segmentation-ready GS representation and then selectively refines splats belonging to semantically relevant POIs detected during data acquisition. 

This targeted refinement drastically reduces training time compared to state-of-the-art full semantic GS while improving novel view synthesis quality in the areas that matter most. We evaluate segmentation quality on the LERF-Mask dataset showing in-line segmentation performance with the state-of-the-art approaches. To demonstrate the key features, we validate CoRe-GS on synthetic (NeRDS 360) and real-world datasets (SCRREAM, Tanks and Temples (train and truck)) demonstrating that prioritizing POIs enables faster and higher-quality mobile reconstruction tailored to operational needs.

## Code
Feel free to reach out if you want to compare with our method on other datasets


