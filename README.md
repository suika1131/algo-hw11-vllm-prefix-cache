# Algorithms HW11 — vLLM Prefix Caching
## 學生資訊
- 姓名：[施旭嶸]
- 學號：[B3231131]
- 課程：3468 演算法 1142
## 實驗環境
- 平台：Google Colab T4
- vLLM 版本：[填 vllm.__version__]
- 模型：Qwen2.5-0.5B-Instruct（或你實際用的）
- prompts 數：100
- max_tokens：64
## 結果摘要
========== 比較摘要 ==========
  吞吐 (req/s) 加速:  3.05 倍
  吞吐 (tok/s) 加速:  3.05 倍
  總耗時下降:          67.2%  (4.94s → 1.62s)
  (TTFT 缺失:vLLM V1 engine 在 offline 模式不回傳 per-request metrics)
## 結論
（200 字描述觀察到的現象與 §11.4 連結）
## 對應作業
- 作業：3468 演算法 HW11 (Ch11) Problem 8(a)
- 投影片：CLRS 4e Ch11 v4 PPT 第 82 頁
- 實驗指南：本 repo 內 README-11-p76.md