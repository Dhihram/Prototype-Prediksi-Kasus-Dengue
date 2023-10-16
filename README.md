![GitHub Releases](https://img.shields.io/badge/available-syntax-blue)

# Prediksi Kasus Dengue

Program ini dipublikasikan menggunakan library [Shiny.io](https://pages.github.com/](https://shiny.posit.co/)https://shiny.posit.co/).
Program ini dikembangkan menggunakan aplikasi [R](https://cran.r-project.org/) dan merupakan hasil peneilitian yang dipresentasikan pada [the 6th Asean Dengue Summit](https://www.asiadenguesummit.org/wp-content/uploads/6th-Asia-Dengue-Summit-Programme-Book.pdf) di Thailand pada Juni 2023. Hasil ini merupakan kolaborasi antara [Kementerian Kesehatan Republik Indonesia](https://www.kemkes.go.id/), [Malaria Consortium](https://www.malariaconsortium.org/where-we-work/thailand.htm), dan [Public Health Litearture Club](https://www.instagram.com/publichealth.literatureclub/).

## Sumber Data:
- [Data keseluruhan cuaca BMKG](https://dataonline.bmkg.go.id/) dan dipilih per stasiun, lalu data diekstrak ke excel per bulan dari Januari 2018 sampai Desember 2022.
- Data Kasus Dengue
- Data Ovitrap Index

## Trained Model
Seluruh model dianalisis menggunakan package ```caret```
- Regression Tree
- Support Vector Regression
- Random Forest
- Lasso Regression
- Ridge Regression
- Linear Regression

## Used Model
Model dipilih berdasarkan RMSE dan MAE. Sehingga model yang diaplikasin pada program ini adalah Support Vector Regression.

Untuk mengakses lama website prediksi, silahkan klik [di sini](https://himhariss.shinyapps.io/PrediksiDengue/)

Untuk dokumentasi permodelan dapat dilihat [di sini](https://dhihram.github.io/Prototype-Prediksi-Kasus-Dengue/#perbandingan-model)
