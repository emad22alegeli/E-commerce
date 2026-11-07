# أناقة (Anaqa) - Flutter

## التشغيل
```bash
flutter create . --platforms=android,ios --project-name anaqa   # يولّد مجلدات android/ios (مرة واحدة)
flutter pub get
flutter run
```
(الأمر الأول لن يستبدل ملفات lib أو pubspec الموجودة.)

## الهيكل
- lib/theme.dart: ألوان وخطوط من DESIGN.md (زوايا حادة 0px)
- lib/data.dart: المنتجات والمحافظات (بيانات تجريبية)
- lib/state.dart: السلة، المفضلة، الكوبون، الطلب، الدردشة (Provider)
- lib/screens/: الرئيسية، التصنيفات، المفضلة، السلة، تفاصيل المنتج، المحافظة، الدفع، نجاح الطلب، الدردشة، حسابي
- design_reference/: صور شاشات Stitch للمقارنة

## مفقود (المرحلة التالية)
خريطة GPS، باك إند حقيقي (منتجات/طلبات/دخول)، بوابات دفع، إشعارات.
