# Image-Compression-and-Video-Coding

**Recent works on image compression and video coding (especially deep-based)**

**This list is maintained by:**

**Sifeng Xia, Yueyue Hu, Wenhan Yang, Dezhao Wang, Yuzhang Hu**

**[[STRUCT]](http://www.icst.pku.edu.cn/struct/struct.html) PKU (PI: Prof. Jiaying Liu)**

## Image Compression
### Prediction
 * CNN-based Prediction
   * CNN-based Prediction for Lossless Coding of Photographic Images (PCS 2018), Ionut Schiopu, Yu Liu, Adrian Munteanu.
   
### Auto-Encoder
 * Deep Convolutional AutoEncoder [[Web]](https://arxiv.org/abs/1804.09535) [[PDF]](https://arxiv.org/pdf/1804.09535.pdf)
   * Deep Convolutional AutoEncoder-based Lossy Image Compression (PCS 2018), Zhengxue Cheng, Heming Sun, Masaru Takeuchi, Jiro Katto.
 * Quantization Independent [[Web]](https://www.irisa.fr/temics/demos/visualization_ae/visualizationAE.htm) [[PDF]](https://www.irisa.fr/temics/demos/visualization_ae/paper_autoencoder_based.pdf)
   * Autoencoder Based Image Compression: Can The Learning Be Quantization Independent? (ICASSP 2018), Thierry Dumas, Aline Roumy, Christine Guillemot.
 * Compressive Autoencoders [[Web]](https://arxiv.org/abs/1703.00395) [[PDF]](https://arxiv.org/pdf/1703.00395.pdf)
   * Lossy Image Compression with Compressive Autoencoders (ICLR 2017), Lucas Theis, Wenzhe Shi, Andrew Cunningham, Ferenc Huszár.
 * End-to-end Compression [[Web]](http://www.cns.nyu.edu/~lcv/iclr2017/) [[PDF]](https://arxiv.org/pdf/1611.01704.pdf)
   * End-to-end Optimized Image Compression (ICLR 2017), Ballé, Laparra & Simoncelli.
 * CAS-CNN [[Web]](https://arxiv.org/abs/1611.07233) [[PDF]](https://arxiv.org/pdf/1611.07233.pdf)
   * CAS-CNN: A Deep Convolutional Neural Network for Image Compression Artifact Suppression (Arxiv 2016), Lukas Cavigelli, Pascal Hager, Luca Benini.   
 * Auto-encoders compression [[Web]](https://arxiv.org/abs/1403.7752) [[PDF]](https://arxiv.org/pdf/1403.7752.pdf)
   * Auto-encoders: reconstruction versus compression (Arxiv 2014), Yann Ollivier.
 * Lightweight Lossy Compression [[Web]](http://ieeexplore.ieee.org/document/7239543/) [[PDF]](http://ieeexplore.ieee.org/document/7239543/)
   * Lightweight Lossy Compression of Biometric Patterns via Denoising Autoencoders (IEEE SPL 2015), Davide Del Testa, Michele Rossi.   
 * Entropy Control and Auto-encoders [[Web]](https://www.irisa.fr/temics/demos/visualization_ae/visualizationAE.htm) [[PDF]](https://arxiv.org/pdf/1802.09371)
   * Autoencoder based image compression: can the learning be quantization independent? (ICASSP 2018), Thierry Dumas, Aline, Roumy, Christine Guillemot.

### Adaptive Bit Rates
 * Recurrent Neural Networks [[Web]](https://github.com/tensorflow/models/tree/master/compression) [[PDF]](https://arxiv.org/pdf/1608.05148.pdf)
   * Full Resolution Image Compression with Recurrent Neural Networks (Arxiv 2016), George Toderici, Damien Vincent, Nick Johnston, Sung Jin Hwang, David Minnen, Joel Shor, Michele Covell.
 * Variable Rate Image Compression [[Web]](https://arxiv.org/abs/1511.06085) [[PDF]](https://arxiv.org/pdf/1511.06085.pdf)
   * Variable Rate Image Compression with Recurrent Neural Networks (Arxiv 2015), George Toderici, Sean M. O'Malley, Sung Jin Hwang, Damien Vincent, David Minnen, Shumeet Baluja, Michele Covell, Rahul Sukthankar.
 * Priming and Spatially Adaptive Bit Rates Compression[[Web]](https://arxiv.org/abs/1703.10114) [[PDF]](https://arxiv.org/pdf/1703.10114.pdf)
   * Improved Lossy Image Compression with Priming and Spatially Adaptive Bit Rates for Recurrent Networks (Arxiv 2017), Nick Johnston, Damien Vincent, David Minnen, Michele Covell, Saurabh Singh, Troy Chinen, Sung Jin Hwang, Joel Shor, George Toderici.   
 * Content-weighted Image Compression[[Web]](https://arxiv.org/abs/1703.10553) [[PDF]](https://arxiv.org/abs/1703.10553.pdf)
   * Learning Convolutional Networks for Content-weighted Image Compression (Arxiv 2017), Mu Li, Wangmeng Zuo, Shuhang Gu, Debin Zhao, David Zhang. 


### Generative Model
 * Generative Compression [[Web]](https://arxiv.org/abs/1703.01467) [[PDF]](https://arxiv.org/pdf/1703.01467.pdf)
   * Generative Compression (PCS 2018), Shibani Santurkar, David Budden, Nir Shavit.
 * Semantic Perceptual Image Compression [[Web]](https://github.com/iamaaditya/image-compression-cnn) [[PDF]](https://arxiv.org/pdf/1612.08712.pdf)
   * Semantic Perceptual Image Compression (Arxiv 2016), A Prakash, N Moran, S Garber, A DiLillo, J Storer.
 * Generative Compression [[Web]](https://arxiv.org/abs/1703.01467) [[PDF]](https://arxiv.org/pdf/1703.01467.pdf)
   * Generative Compression (Arxiv 2017), Shibani Santurkar, David Budden, Nir Shavit.
 * Semantic Perceptual Image Compression [[Web]](https://github.com/iamaaditya/image-compression-cnn) [[PDF]](https://arxiv.org/pdf/1612.08712.pdf)
   * Semantic Perceptual Image Compression (Arxiv 2016), A Prakash, N Moran, S Garber, A DiLillo, J Storer.
 * Conceptual Compression [[Web]](https://arxiv.org/abs/1604.08772) [[PDF]](https://arxiv.org/pdf/1604.08772.pdf)
   * Towards Conceptual Compression (NIPS 2016), Karol Gregor, Frederic Besse, Danilo Jimenez Rezende, Ivo Danihelka, Daan Wierstra.

### Transform
 * Nonlinear Transform Codes [[Web]](https://arxiv.org/abs/1607.05006) [[PDF]](https://arxiv.org/pdf/1607.05006.pdf)
   * End-to-end optimization of nonlinear transform codes for perceptual quality (PCS 2016), Johannes Ballé, Valero Laparra, Eero P. Simoncelli.
 * Soft-to-Hard Vector Quantization [[Web]](https://arxiv.org/abs/1704.00648) [[PDF]](https://arxiv.org/pdf/1704.00648.pdf)
   * Soft-to-Hard Vector Quantization for End-to-End Learned Compression of mages and Neural Networks (Arxiv 2017), Eirikur Agustsson, Fabian Mentzer, Michael Tschannen, Lukas Cavigelli, Radu Timofte, Luca Benini, Luc Van Gool. 
   
 * DC Coefficient Estimation [[PDF]](http://ieeexplore.ieee.org/document/7903672/)
   * DC Coefficient Estimation of Intra-Predicted Residuals in HEVC (TCSVT 2017), Chen Chen, Zexiang Miao, Xiandong Meng, Shuyuan Zhu, Bing Zeng.  

### Post-Processing
 * Codes + CNN [[PDF]](http://ieeexplore.ieee.org/document/7999241/)
   * An End-to-End Compression Framework Based on Convolutional Neural Networks (TCSVT 2017), Feng Jiang, Wen Tao, Shaohui Liu, Jie Ren, Xun Guo, Debin Zhao. 
 * Image Decoding via Edge-Preserving GAN
   * Enhanced Image Decoding via Edge-Preserving Generative Adversarial Network (ICME 2018), Qi Mao, Shiqi Wang, Shanshe Wang, Xinfeng Zhang, Siwei Ma. 
   
## Video Coding

### Loop Filter and Post-Processing
 * Deep HEVC CU Split Decision
   * Fully Connected Network for HEVC CU Split Decision equipped with Laplacian Transparent Composite Model (PCS 2018), Hossam Amer, Abdullah Rashwan, En-hui Yang.    
 * Deep In-Loop Filtering
   * Deep Learning Based HEVC In-Loop Filtering For Decoder Quality Enhancement (PCS 2018), Shiba Kuanar, Christopher Conly, Kamisetty Rao.

### Intra-Prediction Related
 * Progressive Spatial Recurrent Neural Network for Intra Prediction[[Web]](https://arxiv.org/abs/1807.02232) [[PDF]](https://arxiv.org/pdf/1807.02232.pdf)
   * Progressive Spatial Recurrent Neural Network for Intra Prediction (Arxiv 2018), Yueyu Hu, Wenhan Yang, Mading Li, Jiaying Liu. 
 * Fully Connected Network [[PDF]](https://ieeexplore.ieee.org/document/8296231/)
   * Intra prediction using fully connected network for video coding (ICIP 2017), Jiahao Li, Bin Li, Jizheng Xu, Ruiqin Xiong.
 * Convolutional Neural Networks [[PDF]](https://arxiv.org/ftp/arxiv/papers/1808/1808.05734.pdf)
   * Convolutional Neural Networks based Intra Prediction for HEVC (Arxiv 2018), Wenxue Cui, Tao Zhang, Shengping Zhang, Feng Jiang, Wangmeng Zuo, Debin Zhao.


### Inter-Prediction Related
 * Neural Network Based Inter Prediction for HEVC
   * Neural Network Based Inter Prediction for HEVC (ICME 2018), Yang Wang, Xiaopeng Fan, Chuanmin Jia, Debin Zhao, Wen Gao. 
 * CNN Motion Compensation Refinement[[Web]](https://ieeexplore.ieee.org/document/8351609/) [[PDF]](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=8351609)
   * Convolutional Neural Network-Based Motion Compensation Refinement for Video Coding (ISCAS 2018), Zhenghui Zhao, Shiqi Wang, Shanshe Wang, Xinfeng Zhang, Siwei Ma and Jiansheng Yang. 
 * CNN-Based Bi-Directional Motion Compensation[[Web]](https://ieeexplore.ieee.org/document/8351189/) [[PDF]](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=8351189)
   * CNN-Based Bi-Directional Motion Compensation for High Efficiency Video Coding (ISCAS 2018), Zhenghui Zhao, Shiqi Wang, Shanshe Wang, Xinfeng Zhang, Siwei Ma and Jiansheng Yang. 
 * Group Variational Transformer for Fractional Interpolation[[Web]](https://arxiv.org/abs/1806.07008) [[PDF]](https://arxiv.org/pdf/1806.07008.pdf)
   * A Group Variational Transformation Neural Network for Fractional Interpolation of Video Coding (DCC 2018), Sifeng Xia, Wenhan Yang, Yueyu Hu, Siwei Ma, Jiaying Liu. 
 * CNN for Half-Pel Interpolation[[Web]](https://arxiv.org/abs/1703.03502) [[PDF]](https://arxiv.org/pdf/1703.03502.pdf)
   * A Convolutional Neural Network Approach for Half-Pel Interpolation in Video Coding (ISCAS 2017), Ning Yan, Dong Liu, Houqiang Li, and Feng Wu.   
   
### Rate Control
 * RL for Rate Control[[Web]](https://ieeexplore.ieee.org/abstract/document/8351575/) [[PDF]](https://ieeexplore.ieee.org/iel7/8334884/8350884/08351575.pdf)
   * Reinforcement Learning for HEVC/H.265 Intra-Frame Rate Control (ISCAS 2018), Jun-Hao Hu, Wen-Hsiao Peng, and Chia-Hua Chung. 
   
### Transform
 * Variable Block-Sized Signal Dependent Transform [[PDF]](http://ieeexplore.ieee.org/document/7888910/)
   * Variable Block-Sized Signal Dependent Transform for Video Coding (TCSVT 2017), Cuiling Lan, Jizheng Xu, Wenjun Zeng, Guangming Shi, Feng Wu.   
   
### Coding + Image Processing
 * CNN-Based Block Up-sampling[[Web]](https://arxiv.org/abs/1702.06728) [[PDF]](https://arxiv.org/pdf/1702.06728.pdf)
   * Convolutional Neural Network-Based Block Up-sampling for Intra Frame Coding (TCSVT 2017), Yue Li, Dong Liu, Houqiang Li, Li Li, and Feng Wu. 
