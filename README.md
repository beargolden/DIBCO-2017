# DIBCO-2017

We have submitted two algorithms to **ICDAR 2017 Document Image Binarization Competition (DIBCO 2017)**. Our energy-based method (DIBCO2017-HBUT-a) performs the 2<sup>nd</sup> and 10<sup>th</sup> prize for handwritten and machine-printed document image binarization, respectively, among 26 distinct algorithms submitted from 18 research groups[1]. Our locally adaptive thresholding method (DIBCO2017-HBUT-b) performs the 9<sup>th</sup> prize for both handwritten and machine-printed document image binarization among 26 submitted algorithms, respectively[1].

**1. DIBCO2017-HBUT-a:** *Wei XIONG, Jingjing XU, Shiyun ZHAO, Min LI*

> This method comprises three main steps. First, morphological bottom-hat transform is carried out to enhance the document image contrast, and a disk-shaped mask is used to apply morphological operation, whose size is determined by stroke width transform (SWT)[2]. Second, Howe’s binarization method[3] based on graph cut the Laplacian energy minimization with Canny edge detection is then performed on the enhanced document images. Finally, image post-processing is adopted to produce better results.

**2. DIBCO2017-HBUT-b:** *Wei XIONG, Congxiang DONG, Ziyu XIAO, Min LI*

> This method consists of four main steps. First, a bilateral filter is a non-linear, edge-preserving and noise-reducing smoothing filter applied to the input image. Second, the local image contrast and local image gradient are combined[4] to indicate text stroke edge pixels. Third, the document image is binarized by a locally adaptive thresholding method, and the neighborhood window size is determined by stroke width transform (SWT)[2]. Finally, image post-processing is adopted to produce better results.

References

[1] Pratikakis, I., Zagoris, K., Barlas, G., Gatos, B.: ICDAR 2017 competition on document image binarization (DIBCO 2017). In: 14th International Conference on Document Analysis and Recognition (ICDAR 2017), pp. 1395–1403. Kyoto, JAPAN (2017). DOI: 10.1109/icdar.2017.228

[2] Epshtein, B., Ofek, E., Wexler, Y.: Detecting text in natural scenes with stroke width transform. In: 2010 IEEE Conference on Computer Vision and Pattern Recognition (CVPR 2010), pp. 2963–2970. San Francisco, CA (2010). DOI: 10.1109/cvpr.2010.5540041

[3] Howe, N.R.: Document binarization with automatic parameter tuning. International Journal on Document Analysis and Recognition 16(3), 247–258 (2013). DOI: 10.1007/s10032-012-0192-x

[4] Su, B., Lu, S., Tan, C.L.: Robust document image binarization technique for degraded document images. IEEE Transactions on Image Processing 22(4), 1408–1417 (2013). DOI: 10.1109/tip.2012.2231089
