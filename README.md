# 👋 مرحباً — أنا Mohammed Alhaj  
**AI Engineer · Computer Vision · Python Developer**  
_Intelligent Systems • YOLO • Edge AI • MLOps_

[![Website](https://img.shields.io/badge/Portfolio-Visit-blue?logo=google-chrome)](https://github.com/mohammed-m-alhaj)
[![GitHub followers](https://img.shields.io/github/followers/mohammed-m-alhaj?label=Follow&logo=github)](https://github.com/mohammed-m-alhaj)
[![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=mohammed-m-alhaj&layout=compact)](https://github.com/mohammed-m-alhaj)
![GitHub stats](https://github-readme-stats.vercel.app/api?username=mohammed-m-alhaj&show_icons=true&count_private=true)

---

## 🚀 نبذة سريعة
أنا أعمل على بناء أنظمة ذكاء اصطناعي قابلة للتطبيق ميدانياً — خاصةً في الرؤية الحاسوبية وأنظمة الحافة (edge-AI). أحبّ تحويل النماذج البحثية إلى حلول تعمل في الواقع: كشف لوحات، نظام مواقف ذكي، مساعدات ذكية، وواجهات تجريبية للموديلات.  

---

## 🔭 أعمال بارزة (Pinned Projects)
> ها هنا أبرز المشاريع المعلّقة من صفحتك — كل مشروع مع وصف مختصر وروابط التشغيل/الريبو.

### 1) **AI Multi Search Agent**  
محرّك بحث ذكي يجمع نتائج من مصادر متعددة (LangChain + LangGraph) ويعرض النتائج بواجهة Streamlit تفاعلية. مناسب لتلخيص المقارنات والبحث متعدد المصادر.  
- ميزات: بحث متعدد المصادر، تلخيص ذكي، واجهة Streamlit، إعدادات عبر `.env`.  
- تشغيل سريع: `streamlit run main.py`.  
🔗 Repo: https://github.com/mohammed-m-alhaj/ai-multi-search-agent . :contentReference[oaicite:2]{index=2}

### 2) **mindRouter-agent**  
وكيل/إطار عمل لتوجيه استدعاءات الذكاء الاصطناعي (Agent orchestrator) — مفيد لبناء سلاسل مهام ذكية وعمليات معالجة معقّدة.  
🔗 Repo: https://github.com/mohammed-m-alhaj/mindRouter-agent . :contentReference[oaicite:3]{index=3}

### 3) **smart-assistant-pyqt**  
مساعد ذكي بواجهة PyQt للسطح المكتب — يركّز على التجربة المحلية للمساعد مع تحكم رسومي ومهام ذكية.  
🔗 Repo: https://github.com/mohammed-m-alhaj/smart-assistant-pyqt . :contentReference[oaicite:4]{index=4}

### 4) **ToolScoutAgent**  
مشروع مبني لتجربة واستكشاف أدوات/ملفات عمل للـ AI agents — يساعد في اختبار تكامل الأدوات والـ pipelines.  
🔗 Repo: https://github.com/mohammed-m-alhaj/ToolScoutAgent . :contentReference[oaicite:5]{index=5}

> لمزيد من الريبوات: اطلع صفحة المستودعات في حسابك. :contentReference[oaicite:6]{index=6}

---

## 🧰 Tech stack (أهم ما تستخدمه)
- **لغات:** Python  
- **مكتبات / أُطر:** PyTorch, OpenCV, LangChain, Streamlit, LangGraph  
- **أدوات:** Docker, Git, ONNX, Hugging Face, GitHub Actions  
- **Embedded / IoT:** ESP32, Arduino (لـ Smart Parking/Edge inference)

---

## 📂 كيفية تشغيل أحد المشاريع بسرعة (قالب عام)
> ضع هذا داخل أي مشروع يحتوي `requirements.txt` أو `pyproject.toml`

```bash
git clone https://github.com/mohammed-m-alhaj/ai-multi-search-agent.git
cd ai-multi-search-agent
python -m venv .venv
source .venv/bin/activate   # on Windows use: .venv\Scripts\activate
pip install -r requirements.txt
streamlit run main.py
