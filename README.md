# Toshkent_shahar_uylar_narxi_ML

# Housing Price Prediction

This project uses machine learning methods to predict housing prices in Tashkent city. The project includes data cleaning, preparation, and training various models.

## Data

The data is sourced from the `housing_data_08-02-2021.csv` file. This file contains information about house prices, sizes, and locations.

## Libraries

The following libraries are used in this project:
- **Pandas**: For loading and cleaning data.
- **NumPy**: For working with numerical data.
- **scikit-learn**: For creating and evaluating machine learning models.

## Main Steps

1. **Load Data**: Data is loaded from a CSV file.
2. **Clean Price Column**: Values in the price column are converted to numeric format.
3. **Clean Size Column**: Text values in the size column are converted to numeric format.
4. **Fill Null Values**: Null values in each numerical column are filled with the median.
5. **One-Hot Encoding for Categorical Columns**: Categorical data is converted to numeric format.
6. **Split Data**: Training and test data are separated.
7. **Standardization**: Numerical data is standardized.
8. **Create Models**: Random Forest and Linear Regression models are created and trained.
9. **Make Predictions**: Predictions are made on the test data.
10. **Calculate Errors**: Errors are evaluated using RMSE (root mean square error).
11. **Cross-Validation**: Models are assessed through cross-validation.

## Results

The evaluation results of the models are presented in the form of RMSE. Cross-validation results are also shown, helping to determine the reliability of the models.

## How to Use

1. Download the code.
2. Install the required libraries.
3. Run the code and see the results.

## Conclusion

This project tests various methods for predicting housing prices in Tashkent city. Through this code, you can understand the essential steps of the machine learning process.



#############################################################################################################################################
# Housing Price Prediction

Ushbu loyiha Toshkent shahridagi uylar narxini bashorat qilish uchun mashinani o'rganish usullaridan foydalanadi. Loyiha ma'lumotlarni tozalash, tayyorlash va turli modelni o'qitishni o'z ichiga oladi. 

## Ma'lumotlar

Ma'lumotlar `housing_data_08-02-2021.csv` faylidan olinadi. Ushbu fayl uylarning narxi, o'lchovlari va joylashuvi haqidagi ma'lumotlarni o'z ichiga oladi.

## Kutubxonalar

Ushbu loyihada quyidagi kutubxonalar ishlatiladi:
- **Pandas**: Ma'lumotlarni yuklash va tozalash uchun.
- **NumPy**: Raqamli ma'lumotlar bilan ishlash uchun.
- **scikit-learn**: Mashinani o'rganish modellarini yaratish va baholash uchun.

## Asosiy Qadamlar

1. **Ma'lumotlarni yuklash**: CSV faylidan ma'lumotlar yuklanadi.
2. **Narx ustunini tozalash**: Narx ustunidagi qiymatlar raqamli formatga o'zgartiriladi.
3. **Size ustunini tozalash**: Size ustunidagi matnli qiymatlar raqamli formatga o'zgartiriladi.
4. **Null qiymatlarni to'ldirish**: Har bir raqamli ustun uchun null qiymatlar median bilan to'ldiriladi.
5. **Kategoriyali ustunlarni OneHotEncoding qilish**: Kategorik ma'lumotlar raqamli formatga o'zgartiriladi.
6. **Ma'lumotlarni ajratish**: O'qitish va test ma'lumotlari ajratiladi.
7. **Standartizatsiya**: Raqamli ma'lumotlar standartizatsiya qilinadi.
8. **Modelni yaratish**: Random Forest va Linear Regression modellarini yaratish va o'qitish.
9. **Bashorat qilish**: Test ma'lumotlari ustida bashorat qilish amalga oshiriladi.
10. **Xatolikni hisoblash**: RMSE (root mean square error) yordamida xatoliklar baholanadi.
11. **Kross-valyatsiya**: Modellarni kross-valyatsiya orqali baholash.

## Natijalar

Modelning baholash natijalari RMSE ko'rinishida chiqariladi. Kross-valyatsiya natijalari ham ko'rsatiladi, bu esa modelning ishonchliligini aniqlashga yordam beradi.

## Qanday foydalanish

1. Kodni yuklab oling.
2. Talab qilinadigan kutubxonalarni o'rnating.
3. Kodni ishga tushiring va natijalarni ko'ring.

## Xulosa

Ushbu loyiha Toshkent shahridagi uylar narxini bashorat qilishda turli usullarni sinovdan o'tkazadi. Ushbu kod orqali mashinani o'rganish jarayonining asosiy qadamlarini tushunishingiz mumkin.
