# Breast Cancer Classification


This project is developed to classify mammogram images using [CBIS-DDSM (Curated Breast Imaging Subset of Digital Database for Screening Mammography)](https://www.kaggle.com/datasets/awsaf49/cbis-ddsm-breast-cancer-image-dataset/data) dataset. The project aims to create an integrated model by combining two different transfer learning models like VGG16 and ResNet50V2. This combination of two powerful deep learning architectures aims to extract features from mammogram images more effectively.

The dataset contains full mammogram images that include different types of breast cancer cases. The project processes these images and uses the pretrained weights of both models to extract features by removing the last layers. The features obtained from the VGG16 model and ResNet50V2 model are converted into feature vectors using global average pooling, and these features are then combined to process them on fully connected layers. As a result, the integrated model is trained on training data to solve the binary classification problem and is evaluated with both accuracy and loss values.


***

Bu proje, [CBIS-DDSM (Curated Breast Imaging Subset of Digital Database for Screening Mammography)](https://www.kaggle.com/datasets/awsaf49/cbis-ddsm-breast-cancer-image-dataset/data) veri setini kullanarak memogram görüntülerinin sınıflandırılması amacıyla geliştirilmiştir. Proje, VGG16 ve ResNet50V2 gibi iki farklı transfer learning modelini birleştirerek entegre bir model oluşturmayı hedeflemektedir. Bu iki güçlü derin öğrenme mimarisinin birleşimi, memogram görüntülerinden elde edilen özelliklerin daha etkin bir şekilde çıkarılmasını hedeflenmektedir.

Veri seti, farklı türde meme kanseri vakalarını içeren tam memogram görüntüleri içerir. Proje, bu görüntüleri işleyerek, her iki modelin önceden eğitilmiş ağırlıklarını kullanarak son katmanların çıkarılması ile öznitelik çıkarımı yapar. VGG16 modelinden ve ResNet50V2 modelinden elde edilen özellikler, global average pooling ile öznitelik vektörlerine dönüştürülür ve bu öznitelikler daha sonra birleştirilerek tam bağlantılı katmanlar üzerinde işlenir. Sonuç olarak, entegre model, ikili sınıflandırma problemini çözmek için eğitim verileri üzerinde eğitilir ve hem doğruluk hem de kayıp değerleri ile değerlendirilir.


***[(model drive link)](https://drive.google.com/drive/folders/1PKGFF6RSPcC4kjQHR92YjeIvWn5wR4Vn?usp=drive_link)***

![Test sonuçları](img/img.png)
