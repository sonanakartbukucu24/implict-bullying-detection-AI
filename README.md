# implict-bullying-detection-AI
BERTurk-based implicit bullying detection AI

Bu proje, Türkçe metin sınıflandırması için BERT tabanlı bir modelin LoRA ve 8-bit quantization ile parametre verimliliği sağlanarak eğitilmesini içermektedir.

Özellikler

   Türkçe BERT modeli kullanımı

   LoRA (Low-Rank Adaptation) ile verimli ince ayar

   8-bit quantization ile düşük kaynak kullanımı

   Label smoothing ile daha sağlam eğitim

   Early stopping ve checkpoint mekanizması

Kullanım

Projeyi kullanmak için gerekli kodlar ve açıklamalar ilgili hücrelerde bulunmaktadır.
Google Colab ortamında kolayca çalıştırılabilir.
Tercihen Colab ortamında Tesla T4 bu işlem için gayet verimlidir.

Model

Eğitilen model, eğitim veri setine ve kullanılan hiperparametrelere bağlı olarak yaklaşık %89-90 doğruluk değerine ulaşmıştır.
Model dosyaları /model_final dizininde saklanmaktadır.

Lisans

Bu proje Creative Commons Attribution-NonCommercial 4.0 International (CC BY-NC 4.0) lisansı ile lisanslanmıştır.
Ticari amaçlarla kullanılamaz, paylaşıldığında veya değiştirilip kullanıldığında atıf yapılması zorunludur.
