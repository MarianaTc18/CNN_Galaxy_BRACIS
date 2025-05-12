*Convolutional Neural Networks Applied to the Identification and Classification of Galaxies*

Abstract. Surveys are automated telescopes strategically positioned on
the Earth’s surface or in space, designed to scan the sky to build a de-
tailed catalog of the celestial bodies observed in their field of view. To-
gether, these instruments generate terabytes of astronomical data, mak-
ing it essential to employ automated techniques to accurately record
and identify the celestial bodies within such a vast information volume.
For this reason, qualified professionals and advanced deep learning com-
putational techniques, such as Convolutional Neural Networks (CNNs),
are needed to manage and process this enormous amount of data. This
work investigates the applicability of several CNNs in classifying galaxies
using images from the Galaxy10 SDSS Dataset, composed of 21,785 im-
ages, each with dimensions of 69x69 pixels. The tested frameworks, based
on previous studies, were EfficientNetV2-M, DenseNet121, ResNet50,
VGG16 and VGG19. Preprocessing techniques such as data augmenta-
tion, resizing and contrast adjustment were applied in an active selected
manner in different experiments, seeking to identify the most efficient
combination in order to improve the results. The models were evalu-
ated using analyses such as Accuracy, Loss, ROC-AUC and PR-AUC.
The VGG19 architecture with application of the CutMix technique pre-
sented the best performance, achieving an accuracy of 0.90 and PR-AUC
of 0.94. The results obtained not only confirmed the robustness of CNNs
in the classification of astronomical data, but also highlighted the im-
portance of choosing the model criteria and complementary techniques
to optimize the classification process.

Keywords: Astronomy · Convolutional Neural Networks · Galaxies.
