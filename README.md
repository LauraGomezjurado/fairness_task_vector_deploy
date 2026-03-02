# On Fairness of Task Arithmetic: The Role of Task Vectors

**Published as a conference paper at ICLR 2026.**

## Authors

**Laura Gomezjurado Gonzalez**<sup>1♯*</sup>, **Hiroki Naganuma**<sup>2,3♯†</sup>, **Kotaro Yoshida**<sup>4♯‡</sup>, **Yuji Naraki**<sup>5</sup>, **Takafumi Horie**<sup>6</sup>, **Ryotaro Shimizu**<sup>7</sup>

<sup>1</sup>Stanford University · <sup>2</sup>Mila · <sup>3</sup>Université de Montréal · <sup>4</sup>Institute of Science Tokyo · <sup>5</sup>Independent Researcher · <sup>6</sup>Kyoto University · <sup>7</sup>ZOZO Research

<sup>♯</sup>Equal contribution · <sup>*†‡</sup>Corresponding authors

## Abstract

Model editing techniques, particularly task arithmetic with task vectors, offer an efficient alternative to full fine-tuning by enabling direct parameter updates through simple arithmetic operations. While this approach promises substantial computational savings, its impact on fairness has remained largely unexplored—despite growing concern over biased outcomes in high-stakes applications such as hate speech detection. In this work, we present the first systematic study of group fairness in task arithmetic within this binary text and image classification regime, comparing it against full fine-tuning (FFT) and Low-Rank Adaptation (LoRA). We evaluate across multiple language models and datasets using standard group fairness metrics, including Demographic Parity and Equalized Odds. Our analysis shows that task vectors can be tuned to achieve competitive accuracy while reducing disparities, and that merging subgroup-specific task vectors provides a practical mechanism for steering fairness outcomes. We further provide a theoretical bound linking task vector scaling to fairness metrics, offering insight into the observed trade-offs. Together, these findings establish task arithmetic not only as a cost-efficient editing method but also as a fairness-aware alternative to existing adaptation techniques, within the standard group-fair classification setting, laying the groundwork for responsible deployment of large language models.