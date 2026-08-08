# Beyond-Sight
BeyondSight: Quality-Conditioned Balanced Gated Fusion for Pre- venting Modality Collapse in Image–Audio Classification
Image–audio fusion can improve recognition by combining complementary
visual and acoustic evidence, but learned gates may collapse toward a glob-
ally stronger modality, and quality inputs alone may not prevent this fail-
ure. This study develops BeyondSight, an image–audio classification pipeline
that compares unimodal models, embedding concatenation, stacked meta-
classifiers, standard gating, quality-conditioned gating, and balanced gat-
ing with common-space projection, normalization, dropout, and mini-batch
gate regularization. The primary experiment used 3,060 label-aligned image–
audio pairs from 64 bird species, with additional evaluations on animal-plus-
car and machinery–vehicle datasets. Image-only ConvNeXt achieved 94.55%
accuracy, while the Audio Spectrogram Transformer classifier achieved 71.90%.
All image–audio fusion methods exceeded both unimodal baselines. Stacked
Meta Logistic Regression produced the highest observed test accuracy of
97.82%, although it was identified through post-hoc test-set comparison. The
proposed Quality-Aware Balanced Gated Fusion model achieved 97.39% ac-
curacy and reduced complete image-gate saturation from 1.0000 to a mean of
0.5252. On the Low Image/Good Audio subset, it achieved 96.43% accuracy
compared with 89.29% for image-only classification. However, quality–gate
correlations were weak, with absolute values below 0.18. The results dis-
tinguish predictive accuracy, anti-collapse regularization, explicit modality
weighting, quality responsiveness, and architectural reuse as separate objec-
tives in multimodal fusion.
Keywords: multimodal information fusion, image–audio classification,
modality collapse, quality-conditioned fusion, balanced gated fusion,
explicit modality weighting, architectural reuse
