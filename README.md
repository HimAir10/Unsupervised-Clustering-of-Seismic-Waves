# Unsupervised-Clustering-of-Seismic-Waves

Project Summary:
This project focuses on the unsupervised clustering of seismic signals using deep convolutional autoencoders. It explores novel methods for processing and analyzing seismic data with minimal reliance on labeled datasets, making it particularly useful in scenarios where labeled data is scarce. Key contributions include:

Feature Learning and Dimensionality Reduction:
Utilized under-complete convolutional autoencoders to extract salient features from seismic waveforms, facilitating effective clustering in a reduced feature space.

Clustering and Optimization:
Implemented a two-step clustering approach, starting with k-means for centroid initialization, followed by fine-tuning the network through joint optimization of feature learning and clustering assignment.

Applications:
Discrimination of seismic waveforms: Classified local and teleseismic events with an accuracy of 98.41%, outperforming traditional methods.
First-motion polarity determination: Distinguished between upward and downward seismic signals with high precision, leveraging unsupervised techniques.

Significance:
Enhances the reliability of earthquake early warning systems by reducing false alerts and improving seismic signal classification.
Demonstrates the scalability and efficiency of unsupervised methods, achieving superior results with reduced data and computational costs.
