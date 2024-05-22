# ỨNG DỤNG LLM TRONG BÀI TOÁN XÁC ĐỊNH TƯƠNG ĐỒNG VĂN BẢN TIẾNG VIỆT
## Về data:
### Train data
Data cho bài toán này trong tiếng Việt còn hạn chế. Nhóm sử dụng bộ data [STS-Benchmark](https://paperswithcode.com/dataset/sts-benchmark) sau đó dịch sang tiếng Việt sử dụng model VietAI-envit5-translation.

### Test data
Sử dụng 2 bộ ngữ liệu vnPara và VNPC (cụ thể trong Report). Các kết quả được thể hiện cụ thể trong Report.

## Report
Report trong đường link [Google Drive](https://drive.google.com/drive/folders/105o-wPw04XTOBfsOUqUXWJ_jFhMXbFNw?usp=sharing)

## Về các mô hình được sử dụng
- Mô hình Pre-trained: Các mô hình Bert, RoBERTa, PhoBert, SBert.
- Mô hình ngôn ngữ lớn: Mistral 7B và PhoGPT 7B5.

## Code finetune và thực hiện
- Các file notebook FINETUNE chứa các code về finetune các model.
- Các file notebook DEMO chứa các code về việc thực hiện thử các chức năng.
- Lưu ý: Nên chạy các file FINETUNE trên Colab hoặc Kaggle vì vượt khả năng của máy tính cá nhân. 
