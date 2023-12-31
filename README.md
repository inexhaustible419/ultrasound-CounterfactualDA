# ultrasound-CounterfactualDA
Self-supervised Learning for Ultrasound Tongue Contour Extraction with Counterfactual Data Augmentation


**Overview of our framework.** **Grid Dropout (GD):** Dropout is applied to specific pixels in a grid-like fashion. **Center Dropout (CD):**
A large contiguous area is specified for pixel dropout. **Center Filter (CF):** After selecting the central region, basic mean filtering is applied.
**Random Shuffle (RS):** Regions are randomly selected for shuffling pixel combinations in blocks.

![image](https://github.com/inexhaustible419/ultrasound-CounterfactualDA/assets/145007561/fa7ec248-2727-443f-8695-27de8e73c10d)

**Typical sample performance in our method ablation study.** **Original** is the direct output of the backbone network; **+SSL** adds self
supervised pre training; **+RS&GD** adds specific data augmentation based on **+SSL**.
![image](https://github.com/inexhaustible419/ultrasound-CounterfactualDA/assets/145007561/50a5e185-bbda-4194-a91f-c79109a5eb93)

