# LLM-RAG: Retrieval-Augmented Generation with Qwen-3B

This repository contains the implementation of a Retrieval-Augmented Generation (RAG) pipeline utilizing a fine-tuned Qwen-3B model and the BLDS-2015 dataset.

## 1. Giới thiệu (Introduction)

Dự án `llm-rag` được thiết kế để xây dựng một hệ thống hỏi đáp dựa trên tài liệu (RAG) hiệu quả. Hệ thống sử dụng mô hình ngôn ngữ lớn đã được tinh chỉnh (fine-tuned) kết hợp với cơ sở dữ liệu vector để trích xuất ngữ cảnh và tạo ra câu trả lời chính xác.

**Các thành phần chính:**
- **Repository:** [vinhhbui/llm-rag](https://github.com/vinhhbui/llm-rag)
- **Model Checkpoint:** [GodGooose/qwen3b-blds](https://huggingface.co/GodGooose/qwen3b-blds)
- **Dataset:** [GodGooose/blds-2015](https://huggingface.co/datasets/GodGooose/blds-2015)

## 2. Yêu cầu hệ thống (System Requirements)

Dự án có thể chạy trên các cấu hình phần cứng khác nhau. Dưới đây là các thiết lập được đề xuất dựa trên cấu hình phổ biến:

- **Môi trường:** Python 3.10+, CUDA Toolkit 11.8 hoặc 12.x.

## 3. Cài đặt (Installation)

Thực hiện các lệnh sau trong terminal để tải mã nguồn và cài đặt các thư viện cần thiết.

```bash
# Clone the repository
git clone https://github.com/vinhhbui/llm-rag.git
cd llm-rag

# Create a virtual environment (recommended)
python3 -m venv venv
source venv/bin/activate

# Install dependencies
pip install -r requirements.txt
```

## 4. Video demo
https://drive.google.com/drive/folders/1qg9poZPIdsmZ9SecT-UsognWYCkOlTUD?usp=sharing
