# LLM Explorer: GPT-2 ve BERT Karşılaştırması

Bu proje, Hugging Face Transformers kütüphanesi kullanılarak geliştirilmiş, GPT-2 ve BERT modellerinin yeteneklerini, performansını ve iç mekaniklerini karşılaştıran kapsamlı bir analiz ve görselleştirme aracıdır.

## Özellikler

* **GPT-2 ile Metin Üretimi:** Verilen bir başlangıç metnini tamamlar.
* **BERT ile Metin Analizi:** Metinleri anlamsal olarak analiz eder ve token'lara ayırır.
* **Performans Karşılaştırması:** Modellerin işlem hızı, kelime/token sayısı ve yaratıcılık gibi metriklerini karşılaştırır.
* **Attention Görselleştirmesi:** Modellerin metin içindeki hangi kelimelere odaklandığını gösteren ısı haritaları (heatmap) oluşturur.
* **Etkileşimli Web Arayüzü:** Gradio ile geliştirilmiş, kullanıcı dostu arayüzler üzerinden modelleri test etme imkânı sunar.

## Kullanılan Teknolojiler

* Python
* PyTorch
* Hugging Face (Transformers, Tokenizers)
* Gradio
* Pandas & NumPy
* Matplotlib & Seaborn

## Kurulum ve Çalıştırma

1.  **Repo'yu klonlayın:**
    ```bash
    git clone [https://github.com/kullanici-adiniz/LLM-Kasifi.git](https://github.com/kullanici-adiniz/LLM-Kasifi.git)
    cd LLM-Kasifi
    ```

2.  **Gerekli kütüphaneleri kurun:**
    ```bash
    pip install transformers torch gradio matplotlib seaborn pandas numpy tqdm plotly ipywidgets tokenizers
    ```

3.  **Jupyter Notebook'u çalıştırın:**
    `llm_explorer_clean.ipynb` dosyasını açın ve hücreleri sırasıyla çalıştırın. Son hücre, Gradio arayüzünü başlatacaktır.
