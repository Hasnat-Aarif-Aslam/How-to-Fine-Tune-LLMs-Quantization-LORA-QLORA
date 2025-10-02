# **Quantization:**
<img width="1661" height="461" alt="image" src="https://github.com/user-attachments/assets/94d08d66-0ece-4353-8fb4-34a222ca3bac" />
<img width="1332" height="233" alt="image" src="https://github.com/user-attachments/assets/e1869b2a-ac95-41b1-afb9-bab521b4d1c2" />
<img width="1655" height="781" alt="image" src="https://github.com/user-attachments/assets/955649b7-867b-4f7b-8eb8-960c8c3bf342" />

| Format   | Bits | Range                                                                              | Precision   | Common Use                        |
| -------- | ---- | -----------------------------------------------------------------------------------| ----------- | --------------------------------- |
| **FP32** | 32   | Very large                                                                         | ~7 digits   | Full training, reference          |
| **FP16** | 16   | Medium                                                                             | ~3 digits   | Training speedup, inference       |
| **BF16** | 16   | Very large (same as FP32) because it keeps Exponent part same as FP32| ~2–3 digits | Training LLMs (favored)                         |
| **INT8** | 8    | −128 to +127 (scaled)                                                              | ~1–2 digits | Inference quantization            |
| **INT4** | 4    | −8 to +7 (scaled)                                                                  | Low         | Ultra-efficient inference (QLoRA) |


# **Types of Quantization:**

# **Symmetric Quantization:**
<img width="1658" height="334" alt="image" src="https://github.com/user-attachments/assets/6a389e6b-24ba-4def-b97e-e2d053ceb852" />
<img width="981" height="361" alt="image" src="https://github.com/user-attachments/assets/9c467d2f-a744-4193-8a22-fe2018493d51" />
<img width="1095" height="852" alt="image" src="https://github.com/user-attachments/assets/5db3bd63-d313-4a22-8f5e-a5ded733930b" />


# **Asymmetric Quantization:**
<img width="1590" height="631" alt="image" src="https://github.com/user-attachments/assets/6b8259b8-1e63-4e80-b802-7462e9569a09" />


# **Calibration:**
The process of finding the correct scaling factors and zero-points so that the FP32 values can be represented accurately in the lower-precision format.


# **Modes of Quantization:**

* **Post Training Quantization:**
<img width="1642" height="441" alt="image" src="https://github.com/user-attachments/assets/6600564a-80d9-40c1-9874-6448400adb51" />
<img width="632" height="420" alt="image" src="https://github.com/user-attachments/assets/8bd7097f-41e0-46a2-9026-6b643342ab12" />


* **Quantization Aware Training:**
<img width="1287" height="701" alt="image" src="https://github.com/user-attachments/assets/e95593ba-3b06-4019-9426-d2b77bcd5fd2" />
<img width="703" height="380" alt="image" src="https://github.com/user-attachments/assets/95e555b4-cca9-45e8-b8e3-4bff5d098d2c" />


