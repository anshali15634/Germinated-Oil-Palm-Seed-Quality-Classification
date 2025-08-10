# Germinated-Oil-Palm-Seed-Quality-Classification

Developed a binary image classification system to automate quality assessment of germinated oil palm seeds using transfer learning with GoogLeNet. The project aimed to address inefficiencies in manual visual inspection by using deep learning for robust classification under varying imaging conditions.

Main contributions are as follows:

➢ Fine-tuning GoogLeNet on a proprietary agricultural dataset with minimal class imbalance.

➢ Analysing model sensitivity to transformations (e.g., rotation, noise, brightness) through feature similarity and classification consistency.

➢ Designing a targeted offline data augmentation pipeline (rotation, Gaussian noise, scaling, translation) based on model weaknesses to enhance generalisation.

➢ Achieved a 12% improvement in accuracy on unseen test batches with domain shifts (e.g., lighting differences).

➢ Demonstrated enhanced invariance in the model’s features and classifier through t-SNE visualisations and cosine similarity metrics.

This work contributed toward improving model robustness in practical agricultural environments and provided a reproducible methodology for domain-specific deep learning adaptation.
