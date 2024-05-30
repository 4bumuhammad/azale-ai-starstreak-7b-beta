# Azale-ai / starstreak-7b-beta

Original source : 
<pre>https://huggingface.co/azale-ai/Starstreak-7b-beta</pre>

---

&nbsp;

## Startstreak-7B-beta
Starstreak adalah serangkaian language models, yang disempurnakan dengan teknik QLoRA dari model dasar yang disebut Zephyr. Model-model ini telah dilatih untuk menghasilkan konten dalam bahasa Inggris, Indonesia, dan bahasa-bahasa tradisional Indonesia. Starstreak-7B-β adalah varian spesifik dari Starstreak language model open-source, yang dilambangkan dengan seri “β” (beta). Model ini dilatih menggunakan versi HuggingFaceH4/zephyr-7b-beta yang telah disesuaikan. Dua set data digunakan untuk melatih model: yang pertama adalah graelo/wikipedia, dan yang kedua adalah uonlp/CulturaX. Nama “Starstreak” adalah referensi untuk rudal Starstreak, rudal berkecepatan tinggi (HVM) dengan kecepatan melebihi Mach 3. Hal ini menjadikannya salah satu rudal tercepat di kelasnya, dengan jarak tembak efektif 7 kilometer dan jangkauan radar 250 kilometer.”

&nbsp;

**Model Details**

- **Finetuned from model**: <a href=https://huggingface.co/HuggingFaceH4/zephyr-7b-beta>HuggingFaceH4/zephyr-7b-beta</a>
- **Dataset**: <a href=https://huggingface.co/datasets/graelo/wikipedia>graelo/wikipedia</a> and <a href=https://huggingface.co/datasets/uonlp/CulturaX>uonlp/CultruaX</a>
- **Model Size**: 7B
- **License**: CC0 1.0 Universal (CC0 1.0) Public Domain Dedication
- **Language**: English, Indonesian, Achinese, Balinese, Banjar, Basa Banyumasan, Buginese, Gorontalo, Javanese, Maduranese, Minangkabau, Sundanese, Malay, Nias, and Tetum
- **Demo Google Colab**: <a href=https://colab.research.google.com/drive/1QGImbhbb0vdTIbsxvQJPrfh0qDcADKGe>Google Colab</a>
- **Demo HuggingFace Space**: HuggingFace Space

&nbsp;

**How to use**
Untuk menggunakan model Startstreak, pastikan bahwa PyTorch telah terinstal dan Anda memiliki GPU Nvidia (atau gunakan Google Colab). Setelah itu, Anda perlu menginstal dependensi yang diperlukan:
```bash
pip3 install -U git+https://github.com/huggingface/transformers.git
pip3 install -U git+https://github.com/huggingface/peft.git
pip3 install -U git+https://github.com/huggingface/accelerate.git
pip3 install -U bitsandbytes==0.39.0 einops==0.6.1 sentencepiece
```