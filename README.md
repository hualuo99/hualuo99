一、核心编程语言
- Python （全栈开发语言，贯穿数据处理、AI 模型训练、后端服务及 GUI 开发）
二、人工智能与机器学习
1. 深度学习框架
- PyTorch（核心训练与推理框架）
- TorchVision（计算机视觉任务工具包）
- Transformers（NLP 预训练模型库）
2. 模型优化技术
- 参数高效微调：LoRA、QLoRA
- 量化与加速：BitsAndBytes（INT8/4 量化）、NVIDIA CUDA（GPU 加速）
- 混合精度训练与推理：FP16/BF16 优化显存使用
3. 领域特定模型
- 计算机视觉：YOLOv8（目标检测）、OCR 技术（文本识别）、OpenCV/Pillow（图像处理）
- 自然语言处理：基于 RAG 的 Vanna 框架（NL2SQL）、Faster-Whisper（语音识别）
- 多模态生成：Stable Diffusion（ComfyUI 可视化界面）
三、数据存储与检索
- 关系型数据库：MySQL（结构化数据存储）
- 向量数据库：ChromaDB（语义相似度检索）
- 数据处理工具：Pandas/NumPy（数据清洗与分析）、SQLAlchemy（ORM）
四、后端开发与 API 集成
- Web 框架：Flask（RESTful API 服务）
- API 集成：OpenAI API、第三方服务接口（如翻译、支付等）
- 异步处理：Celery（任务队列）、Redis（缓存）
五、应用开发与用户界面
- GUI 开发：PySide6（跨平台桌面应用，基于 Qt6）
- 视频处理：FFmpeg（底层编解码）、MoviePy（高级剪辑）
- 自动化工具：影刀 RPA（业务流程自动化）
六、安全与加密
- 数据编码：zlib（压缩）、marshal（序列化）、base64（传输编码）
- 加密算法：XOR（轻量级加密）、AES-256（敏感数据保护）
七、性能优化与部署
- 硬件加速：NVIDIA GPU（CUDA/CuDNN）、TensorRT（推理优化）
- 内存管理：低显存模式（--lowvram）、批量处理优化
- 部署工具：Docker（容器化）、Gunicorn/Nginx（Web 服务部署）
技术栈优势总结
1. 全栈 AI 能力：覆盖数据处理、模型训练、推理部署到前端交互的完整链路
2. 多模态支持：无缝整合文本、图像、语音、视频处理能力
3. 工程化落地：兼顾学术前沿（如 LoRA 微调）与企业级需求（安全加密、RPA 自动化）
4. 资源效率优化：通过量化、GPU 加速和内存优化，支持在消费级硬件上运行大型模型
5. 模块化设计：各组件可独立扩展，支持快速迭代与技术选型替换

技术栈应用场景
- 智能数据分析平台：结合 NL2SQL 与向量检索，实现自然语言驱动的数据查询
- 多媒体内容生成：基于 Stable Diffusion 和 FFmpeg 的自动化视频 / 图像创作工具
- 企业级 RPA 系统：融合 AI 模型与流程自动化，构建智能业务机器人
- 边缘 AI 设备：通过模型量化与 CUDA 加速，在嵌入式 GPU 上部署轻量级推理服务

开发项目(闭源)
暂时无法在飞书文档外展示此内容
