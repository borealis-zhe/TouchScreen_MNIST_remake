#  Handwritten digits recognition on stm32h7  
## 基于STM32H747I-DISCOVERY kit开发板的手写数字识别  
 TouchScreen_MNIST_remake 嵌入式系统课程大作业  
 项目使用CubeMX生成，使用keil mdk编程，使用了ST Cube-X-AI包  
 This is a public repo for homework  
 This project was generated by CubeMX ST Cube-X-AI packages. The model is from [ST MODELZOO](https://github.com/STMicroelectronics/stm32ai-modelzoo)  
 **Caution: There is a potiential fatal bug to be fixed !**  
 The activation buffer is probably allocated incorrectly due to some reasons and my solution is to declare an extra space for activation buffer. Anyway, it works. See ../CM7/Core/Src/main.c(326): ai_u8 activations[AI_NETWORK_DATA_ACTIVATIONS_SIZE+8192]; You can also refer to [here](https://community.st.com/t5/edge-ai/memory-error-related-with-cube-ai/m-p/685360#M2697)  
 If Anyone has a solution please create an issue or pull request.
 ![image](doc\Wechat_pic_1.jpg)