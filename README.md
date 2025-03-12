# Model Deployment


# Gereklilikler

1. Model nesnesi (pkl) ya da model nesnesini çıkaracak script (model.py)
2. "app.py" Flask Uygulaması
3. Kullanıcı etkileşimi için gerekli arayüz. (html template)


# Projeyi Çalıştırmak için

1. Çalışma dizininde aşağıdaki dosyaların olduğuna emin olunuz:

- data klasörü ve içinde advertising.csv dosyası.
- templates klasörü ve içerisinde web arayüzü
- app.py (flask uygulaması)
- model.py (modellemeyi yapacak script)
- regression_model.pkl (model nesnesi. eğer bu dosya yoksa model.py ile oluşturunuz)

2. Dosyaların olduğu dizinde console'dan python app.py kodunu çalıştırınız.

3. http://localhost:5000 dizininden uygulamaya erisiniz.

