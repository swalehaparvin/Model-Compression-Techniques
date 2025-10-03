# ⚡ Model Compression Techniques (PyTorch Overview)
Model compression is a set of techniques used to reduce the size and computational complexity of a model while preserving or even improving its performance.
This repository provides simple Google Colab–ready examples that demonstrate **three core model compression techniques** used to optimize deep learning models for deployment on resource-constrained environments such as mobile devices, IoT hardware, and edge systems.  

---

## 🚀 Techniques Covered

### 1. Pruning  
Pruning removes unnecessary weights or entire neurons/filters from a neural network. By introducing sparsity, it reduces computation and memory usage while maintaining performance.  
- **Unstructured pruning**: Removes individual weights.  
- **Structured pruning**: Removes entire neurons, channels, or filters.  

---

### 2. Quantization  
Quantization reduces the precision of numerical representations (e.g., from 32-bit floating point to 8-bit integers). This significantly decreases model size and speeds up inference with minimal impact on accuracy.  
- **Post-training quantization**: Apply after model training.  
- **Quantization-aware training**: Train the model with quantization effects included.  

---

### 3. Knowledge Distillation  
Knowledge Distillation compresses a large **teacher model** into a smaller **student model**. The student learns both from the original training data and from the teacher’s predictions, allowing it to achieve strong performance with fewer parameters.  

---

## ✅ Summary  
- **Pruning** → Removes redundant parameters to create sparse models.  
- **Quantization** → Reduces precision to optimize memory and speed.  
- **Knowledge Distillation** → Transfers knowledge from large teacher models to compact student models.  

These three techniques are widely used in industry to deploy efficient, scalable AI models without sacrificing too much accuracy.  

Read https://www.dailydoseofds.com/model-compression-a-critical-step-towards-efficient-machine-learning/#1-knowledge-distillation
