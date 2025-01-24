# Neural Style Transfer with TensorFlow

## **Overview**
This project demonstrates **Neural Style Transfer**, a deep learning technique that combines the **content** of one image with the **style** of another image to create a new, visually stunning image. Using a pre-trained model from **TensorFlow Hub**, the implementation allows for easy experimentation with different content and style images.

---

## **How It Works**
1. **Content Image**:
   - The image whose structure and layout will be retained in the final output.
2. **Style Image**:
   - The image whose artistic style (e.g., colors, brushstrokes) will be applied to the content image.
3. **Model**:
   - Uses a pre-trained neural style transfer model available on TensorFlow Hub: [arbitrary-image-stylization-v1-256](https://tfhub.dev/google/magenta/arbitrary-image-stylization-v1-256/2).
4. **Output**:
   - A stylized image that blends the content of the first image with the style of the second.

