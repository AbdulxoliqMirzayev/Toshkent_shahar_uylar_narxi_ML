# Toshkent_shahar_uylar_narxi_ML
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
