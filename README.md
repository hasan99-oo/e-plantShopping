#  e-plantShopping

مشروع React بسيط استخدمته لتجربة مفاهيم DevOps.

## المفاهيم المطبقة
- Git لإدارة الإصدارات.
- Docker لتشغيل المشروع داخل Container.
- GitHub Actions لتجربة CI/CD.

## تشغيل المشروع باستخدام Docker
```bash
docker build -t e-plant-app .
docker run -p 5173:5173 e-plant-app
