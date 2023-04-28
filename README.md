# Retinex_based_Image_filter_processing
#English version

This is a project to filter the noises underwater and to process images taken by the camera using retinex way. We use gamma transform to enhance the light and the contrast of the image, and after that there are various  adaptive filters to choose.

Adaptive filtering is a filtering method that automatically adjusts filter parameters based on local pixel variations, and can be used for underwater image restoration. One underwater image restoration method using adaptive filtering is based on the Retinex theory and gamma correction, with the following specific steps:

  1. Gamma correction is performed on the underwater image to reduce brightness distortion.
  2. The Retinex theory is used to enhance the gamma-corrected image and improve contrast.
  3. Adaptive filtering is applied to the enhanced image to remove noise and blur while preserving detail information.
  4. Finally, inverse gamma correction is performed to restore the output image to its original brightness level.

##################Chinese version###############

自适应滤波是一种根据局部像素变化自动调整滤波器参数的滤波方法，可以用于水下图像的复原。一种自适应滤波的水下图像复原方法是基于Retinex理论和伽马校正，具体步骤如下： 
  1. 对水下图像进行伽马校正，以减小图片的亮度失真； 
  2. 利用Retinex理论对伽马校正后的图像进行增强，提高对比度； 
  3. 对增强后的图像进行自适应滤波处理，可以去除噪声和模糊，同时保留细节信息； 
  4. 最后进行反伽马校正，将输出图像还原到原始亮度级别。 
  以上方法可以适用于一般的水下图像复原，但实际应用时需要根据具体情况进行调整和优化。
