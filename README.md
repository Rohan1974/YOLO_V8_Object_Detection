## Object Detection with YOLOv8

This project explores object detection using the powerful YOLOv8 framework. It offers two approaches:

**From Scratch Training:** This section dives into building a custom object detection model. It covers splitting your dataset for training, testing, and validation. Additionally, it details extracting numeric labels from text strings (e.g., "MH12" becomes "12").
**Pre-trained Model Fine-tuning:** Here, It leverage the pre-trained YOLOv8n.pt model, initially trained on the COCO dataset. This model is then fine-tuned on your specific data to achieve better accuracy for your objects of interest.
  

**Key Points:**
**Nano Model for Efficiency:** We utilize the efficient YOLOv8 nano model for training, allowing for faster processing on resource-constrained environments.
**Confidence Score & GPU Acceleration:** During training, confidence scores are incorporated to improve the model's certainty in its detections. Additionally, GPU acceleration via CUDA drastically reduces training time.
**Accuracy Visualization:** Finally, the project visualizes the model's accuracy as it progresses through training epochs, providing valuable insights into the learning process.

  
**Conclusion**
This project demonstrates the power and flexibility of YOLOv8 for object detection tasks. It showcases both building a custom model and fine-tuning a pre-trained one, along with techniques for efficient training and performance evaluation.
