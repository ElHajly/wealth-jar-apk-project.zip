# جرة الثروة - بناء APK

1. دخل لـ github.com وصاوب repository جديد (خاصو يكون Public ولا Private، عادي).
2. فالصفحة ديال الـ repository ضغط "uploading an existing file" وجر كاع محتوى هاد المجلد (بما فيهم المجلد المخفي .github).
   إيلا ما قدرتيش ترفع المجلد المخفي، صاوب يدويا الملف .github/workflows/build-apk.yml وانسخ فيه المحتوى.
3. دخل لتاب Actions، اختار "Build APK" وضغط "Run workflow".
4. من بعد 8 حتى 12 دقيقة، ضغط على آخر run ونزل "wealth-jar-apk" من تحت (Artifacts). فيه ملف app-debug.apk داخل zip.
5. نقل الملف للتيليفون، ونصبو (سمح بالتنصيب من مصادر خارجية إيلا طلبها).
