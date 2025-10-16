# MSTLD-dataset
The MSTLD is dataset covers a very wide range of scenarios, especially focusing on the operational complexity of power transmission lines and safety-critical scenarios, filling the gap in existing datasets. 
# MSTLD: A Multi-Scenario Transmission Line Segmentation Dataset for Power Grid Monitoring under Complex Conditions

Galloping of transmission lines caused by extreme
weather conditions poses a severe threat to the stable delivery
of electric power. Current mainstream monitoring approaches
typically employ deep learning–based segmentation algorithms
to extract transmission lines from images, followed by classification of galloping severity. The accuracy of the segmentation
algorithms largely depends on the quality of the transmission
line segmentation dataset and directly impacts the reliability of
galloping level prediction. However, publicly available transmission line segmentation datasets remain scarce and often suffer
from limited scene diversity and suboptimal annotation quality.
To address these issues, we present MSTLD, a high-quality
semantic segmentation dataset for transmission lines, featuring
cross-season, day-night, multi-background, and multi-scale diversity, with 4,000 finely annotated images. First, we introduce a
spatiotemporal random sampling strategy and a two-stage data
filtering process, which not only enhance the dataset’s ability
to represent real-world operating conditions but also increase
the variety and proportion of critical scenarios such as extreme
weather, low illumination, and cluttered backgrounds. Then, we
design a hybrid annotation strategy that balances annotation
efficiency and accuracy. Finally, extensive experimental results
of 18 state-of-the-art models on MSTLD demonstrate the strong
adaptability and discriminative power of the proposed dataset.
Furthermore, additional experiments were conducted to validate
the effectiveness of the proposed hybrid annotation strategy and
its inherent challenges.


The dataset covers multiple scenarios, and several groups of representative scenarios along with their corresponding annotation information are shown in the figure.
![标注数据集](https://github.com/user-attachments/assets/2e66e21c-12a4-47c1-b873-ae9960ac4051)

# Data Access 
Currently, the MSTLD dataset has been partially released. Researchers who require access to the data can contact us and specify the intended use.
