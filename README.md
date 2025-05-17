
# Employee Evaluation App (Flask)

تطبيق تقييم الموظفين باستخدام Flask، يتيح للمقيمين تسجيل الدخول وتقييم الموظفين بناءً على 3 معايير.

## المزايا
- تسجيل دخول آمن للمقيمين باستخدام `user_code` و `user_ID`.
- عرض قائمة الموظفين المرتبطين بكل مقيم.
- 3 معايير تقييم: الالتزام الوظيفي والمظهر، الحضور والانصراف، جودة العمل.
- حفظ التقييمات في ملف Excel.

## التشغيل المحلي
```bash
pip install -r requirements.txt
python app.py
```

ثم افتح المتصفح على:
```
http://localhost:5000
```

## النشر على Render
- اربط المستودع بـ GitHub
- إعدادات Render:
  - Build Command: `pip install -r requirements.txt`
  - Start Command: `python app.py`
