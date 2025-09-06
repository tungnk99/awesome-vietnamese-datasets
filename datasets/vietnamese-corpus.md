# 📚 Vietnamese Corpus Datasets


Tài liệu này tổng hợp các **corpus tiếng Việt** phục vụ cho mục đích nghiên cứu và phát triển trong lĩnh vực Natural Language Processing (NLP).  
Các corpus chủ yếu bao gồm tập văn bản thô, được sử dụng làm nguồn dữ liệu cho quá trình training và pre-training các language models (LM).

---

## 🔹 General Corpus
Văn bản chung (Wikipedia, báo chí, sách, web…)

| Dataset | #Samples | Size | Year | License | Link | Citation |
|---------|----------|------|------|---------|------|----------|
| wikipedia_vi | 1,281,412 | ~570MB | – | – | [Hugging Face](https://huggingface.co/datasets/vietgpt/wikipedia_vi) | – |
| Vietnamese-Book-Corpus | 16,407 | ~1.92GB | – | – | [Hugging Face](https://huggingface.co/datasets/tmnam20/Vietnamese-Book-Corpus) | – |
| Binhvq News Corpus | 14,896,998 | ~18.6 GB | 2018 | Apache License | [GitHub](https://github.com/binhvq/news-corpus) | – |
| vietnamese-poetry-corpus | 198,598 | ~164 MB | –  | – | [Hugging Face](https://huggingface.co/datasets/phamson02/vietnamese-poetry-corpus) | – |
| BKAINewsCorpus | 16,762,024 | ~28.7 GB | 2024 | – | [Hugging Face](https://huggingface.co/datasets/bkai-foundation-models/BKAINewsCorpus) | – |
| NewsCategory  | 596,524 | ~1.04 GB | 2024 | – | [Hugging Face](https://huggingface.co/datasets/bkai-foundation-models/NewsCategory) | – |
| NewsSapo   | 31,728,183 | - | 2024 | – | [Hugging Face](https://huggingface.co/datasets/bkai-foundation-models/NewsSapo) | – |


**📝 Notes:**  
- *wikipedia_vi*: 
- *Vietnamese-Book-Corpus*: 
- *Binhvq News Corpus*:
- *vietnamese-poetry-corpus*:
- *BKAINewsCorpus*:
- *NewsCategory*:
- *NewsSapo*:
---

## 🔹 News Corpus
| Dataset | #Samples | Size | Year | License | Link | Citation |
|---------|----------|------|------|---------|------|----------|
| Binhvq News Corpus | 14.896.998 bài báo | ~18.6 GB | 2018 | Apache License | [GitHub](https://github.com/binhvq/news-corpus) | – |
| VLSP News Corpus | ~1M sentences | ~500MB | 2016–2019 | Research-only | [VLSP](https://vlsp.org.vn/) | VLSP Proceedings |

**📝 Notes:**  
- *VnExpress Corpus*: ngôn ngữ báo chí, cú pháp chuẩn, ít lỗi chính tả.  
- *VLSP News*: chuẩn hóa, hay được dùng cho POS/NER nhưng hạn chế license (chỉ dùng nghiên cứu).  

---

## 🔹 Social Media / Forum
| Dataset | #Samples | Size | Year | License | Link | Citation |
|---------|----------|------|------|---------|------|----------|
| UIT-ViOCD | ~30k comments | ~3MB | 2020 | CC BY-NC-SA 4.0 | [UIT NLP Lab](https://uit-nlp.net) | [Paper](https://aclanthology.org/2020.lrec-1.812/) |
| Foody Review Corpus | ~20k reviews | ~2MB | 2019 | Research-only | [GitHub](#) | – |

**📝 Notes:**  
- *UIT-ViOCD*: nhiều từ lóng, viết tắt, noise → phù hợp nghiên cứu xử lý ngôn ngữ đời thường.  
- *Foody Review*: ngôn ngữ đánh giá, cảm xúc, hữu ích cho sentiment analysis.  

---

## 🔹 Literature / Others
| Dataset | #Samples | Size | Year | License | Link | Citation |
|---------|----------|------|------|---------|------|----------|
| Vietnamese Books Corpus | ? | ? | ? | Research-only | [GitHub](#) | – |
| VNESEcorpus | ~100M tokens | ~2GB | 2017 | Research-only | [GitHub](#) | – |

**📝 Notes:**  
- *Vietnamese Books Corpus*: phong cách văn học, khác biệt với dữ liệu báo chí/diễn đàn.  
- *VNESEcorpus*: nguồn dữ liệu tổng hợp, chưa chuẩn hóa, có thể dùng cho pretraining.  

---

👉 **Lưu ý chung:**  
- Các con số chỉ mang tính tham khảo, cần kiểm chứng từ nguồn chính thức.  
- Một số dataset bị giới hạn bản quyền → chỉ dùng cho mục đích nghiên cứu.  
- Bạn có thể đóng góp thêm corpus mới bằng cách tạo **Pull Request** 🙌.  
