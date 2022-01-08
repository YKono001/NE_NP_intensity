# NE_NP_intensity
【Used with CellProfiler 3.1.9】

Recognizing nuclear region from nuclear localization signal-fused fluorescence protein (NLS-FP) images.
3 pixels from the rim of the nuclear region are regarded as the nuclear envelope.
More than 10 pixels inside from the rim of nuclear region are regarded as the nucleoplasm.

When nuclear region cannot be detected properly using NLS-FP images, use the DetectWithNLSMaskWithLamin or DetectWithLamin pipeline to analyze images.
