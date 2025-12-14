# 🩻📊 Multi-class Medical CXR Image Classification using Traditional ML, Ensemble Learning and Deep Learning (CNN)

This project uses machine learning techniques to create three models that will aid in diagnosing COVID-19. The models will analyze X-ray images of the lungs determine whether the person has COVID-19, Non-COVID related infection or a Normal result.

Three types of models are explored in this project: traditional machine learning model (Decision Tree), ensemble learning model (Random Forest) and a deep learning model (CNN).

## ⚙️ Technologies

- `Python`
- `PyTorch`
- `Google Colab`

## ✨ Project Findings:

-  We implemented three different models: Decision Tree, Random Forest and CNN.
-   Decision tree and random forest models required manual feature extraction from the images which is not practical for large images and creates high dimensionality.
-   The benefit of CNN is that it automatically learns the features from the raw images and hence is more practical.
-   Decision tree performed poorly compared to the other two models.
-   Random forest model had a relatively good performance.
-   CNN performed well within the resource constraints and could have a much better performance if the original image sizes were used.

## 🗃️ Dataset

**COVID-QU-Ex Dataset** </br>
The researchers of Qatar University have compiled the COVID-QU-Ex dataset, which consists of 33,920 chest X-ray (CXR) images including:

*   11,956 COVID-19
*   11,263 Non-COVID infections (Viral or Bacterial Pneumonia)
*   10,701 Normal

Access the dataset through this link [COVID-QU-Ex Dataset](https://www.kaggle.com/datasets/anasmohammedtahir/covidqu/)</br>

## 📚 Citation

1.    A. M. Tahir, M. E. H. Chowdhury, A. Khandakar, Y. Qiblawey, U. Khurshid, S. Kiranyaz, N. Ibtehaz, M. S. Rahman, S. Al-Madeed, S. Mahmud, M. Ezeddin, K. Hameed, and T. Hamid, “COVID-19 Infection Localization and Severity Grading from Chest X-ray Images”, Computers in Biology and Medicine, vol. 139, p. 105002, 2021, https://doi.org/10.1016/j.compbiomed.2021.105002.
2.    Anas M. Tahir, Muhammad E. H. Chowdhury, Yazan Qiblawey, Amith Khandakar, Tawsifur Rahman, Serkan Kiranyaz, Uzair Khurshid, Nabil Ibtehaz, Sakib Mahmud, and Maymouna Ezeddin, “COVID-QU-Ex .” Kaggle, 2021, https://doi.org/10.34740/kaggle/dsv/3122958.
3.    T. Rahman, A. Khandakar, Y. Qiblawey A. Tahir S. Kiranyaz, S. Abul Kashem, M. Islam, S. Al Maadeed, S. Zughaier, M. Khan, M. Chowdhury, "Exploring the Effect of Image Enhancement Techniques on COVID-19 Detection using Chest X-rays Images," Computers in Biology and Medicine, p. 104319, 2021, https://doi.org/10.1016/j.compbiomed.2021.104319.
4.    A. Degerli, M. Ahishali, M. Yamac, S. Kiranyaz, M. E. H. Chowdhury, K. Hameed, T. Hamid, R. Mazhar, and M. Gabbouj, "Covid-19 infection map generation and detection from chest X-ray images," Health Inf Sci Syst 9, 15 (2021), https://doi.org/10.1007/s13755-021-00146-8.
5.    M. E. H. Chowdhury, T. Rahman, A. Khandakar, R. Mazhar, M. A. Kadir, Z. B. Mahbub, K. R. Islam, M. S. Khan, A. Iqbal, N. A. Emadi, M. B. I. Reaz, M. T. Islam, "Can AI Help in Screening Viral and COVID-19 Pneumonia?," IEEE Access, vol. 8, pp. 132665-132676, 2020, https://doi.org/10.1109/ACCESS.2020.3010287.
