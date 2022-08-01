# SpeedAnalysis
Working with my life partner to explore distribution of interference in program performance benchmark tools

Jamie and I were talking one day about the performance testing she is doing for her project Rosie Pattern Language using Hyperfine. She mentioned that Hyperfine sometimes reports that there may have been outliers in the testing. I suggested that maybe she should try clustering to understand if there was any pattern to the data. And so this project came to be.

Normally for clustering you would use K-Means however because this data is one dimensional a simpler technique called Kernel Density Estimation is appropriate. KDE attempts to create a probability distribution for your data. It's basically a sophisticated histogram.