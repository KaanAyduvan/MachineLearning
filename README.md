# Google Play Store Apps - Churn Analysis and Noise & Anomaly Detection

Bu proje, Google Play Store Apps verisini kullanarak bu problem üzerine odaklanmıştır: **Churn Analysis (Kullanıcı Kaybı Analizi)**. Verinin öne çıkan özellikleri ve yapılan analizler aşağıda detaylandırılmıştır.

## Kaggle Notebook Link

https://www.kaggle.com/code/kaanayduvann/churn-analysis-and-anomaly-dedection-of-googleapps

## Veri Seti Açıklaması

Google Play Store Apps veri seti şu sütunları içermektedir:

- **App Name**: Uygulamaların isimleri.
- **App Id**: Uygulamaların eşsiz değerleri.
- **Category**: Uygulamaların kategorileri.
- **Rating**: Uygulamaların 1 ile 5 arasında aldığı puanlar.
- **Rating Count**: Uygulamaların kaç kez oylandığını gösterir.
- **Installs**: Uygulamaların indirilme sayısı.
- **Minimum Installs**: Minimum indirilme sayısı.
- **Maximum Installs**: Maksimum indirilme sayısı.
- **Free**: Uygulamanın ücretsiz olup olmadığını gösterir (True/False).
- **Price**: Uygulamaların ücreti.
- **Currency**: Ücretli uygulamaların para birimi.
- **Size**: Uygulamanın boyutu.
- **Minimum Android**: Desteklenen minimum Android sürümü.
- **Developer Id**: Geliştirici kimliği.
- **Developer Website**: Geliştirici websitesi.
- **Developer Email**: Geliştirici e-posta adresi.
- **Released**: Uygulamanın yayınlanma tarihi.
- **Privacy Policy**: Gizlilik politikası.
- **Last Updated**: Uygulamanın son güncellenme tarihi.
- **Content Rating**: İçeriğin hangi kitleye yönelik olduğunu gösterir.
- **Ad Supported**: Reklam desteklenip desteklenmediğini belirtir (True/False).
- **In-app Purchases**: Uygulama içi satın alım olup olmadığını gösterir (True/False).
- **Editors Choice**: Editörlerin önerip önermediğini belirtir (True/False).

## Kullanılan Sütunlar
Projelerde aşağıdaki sütunlar kullanılmıştır:

- **App Name**
- **Rating**
- **Rating Count**
- **Installs**
- **Price**
- **Category**
- **Last Updated**
- **Free**

## Churn Analysis Projesi Sonuçları
Churn Analysis projemizde, model performansını şu metriklerle değerlendirdik:

- **Mean Squared Error (MSE)**: 0.005553778039120735
- **Mean Absolute Error (MAE)**: 0.005553778039120735
- **Confusion Matrix**:
  [[246653    663]
  [  1906 213346]]
 - **Accuracy**: 0.9944462219608793
- **Precision**: 0.9969019994486213
- **Recall**: 0.9911452622972144
- **F1**: 0.9940152960553137


