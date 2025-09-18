<<<<<<< HEAD
"ChemistryTutorAI" Project is an intelligent assistant for high school chemistry students in Egypt.
The goal is to help students understand curricula and answer questions, while maintaining academic integrity (preventing cheating or directly solving exam papers).

🎯 Project Goals

Provide an interactive chemistry Q&A assistant.

Support both Arabic and English.

Add a personalized Teacher Style explanation.

Enable image upload (OCR → text → answer).

Prevent cheating (block solving full exam papers).

📂 Project Structure
0_docs/

Complete documentation (roadmap, requirements, licenses).

1_data/

Raw and cleaned datasets + Q&A pairs.

2_notebooks/

Jupyter experiments: data cleaning, OCR, fine-tuning, teacher style imitation.

3_models/

Models:

base_model → original model.

finetuned → fine-tuned model.

adapters → LoRA adapters.

teacher_style → teacher’s explanation style.

vision_ocr → OCR models.

4_rag/

RAG engine: indexing + retrieval.

5_api/

FastAPI backend:

main.py → entry point.

ocr_service.py → OCR processing.

content_filter.py → anti-cheating filter.

exam_filters.json → teacher settings (fonts, banned words, QR).

6_frontend/

Frontend (React).

7_deployment/

Deployment with Docker + deployment guide.

🛡️ Anti-Cheating Feature

Based on OCR + filtering.

Teacher can define exam fingerprint (custom font, keywords, QR).

System blocks responses if an exam paper is detected.





# ChemistryTutorAI  



**مشروع "ChemistryTutorAI"** هو مساعد ذكي لمادة الكيمياء لطلاب المرحلة الثانوية في مصر.  
الهدف إنه يساعد الطلاب يفهموا المناهج ويجاوب على الأسئلة، مع الحفاظ على **الأمان الأكاديمي** (يعني منع الغش أو حل أوراق الامتحانات مباشرة).  

---

### 🎯 أهداف المشروع  
- توفير مساعد تفاعلي للإجابة عن أسئلة الكيمياء.  
- دعم اللغة العربية والإنجليزية.  
- إضافة أسلوب شرح خاص بالمدرس (Teacher Style).  
- رفع الصور (OCR) وتحويلها إلى نصوص + إجابة.  
- حماية من الغش (عدم حل أوراق امتحانات كاملة).  

---

### 📂 هيكل المشروع  

#### 0_docs/  
التوثيق الكامل (خطة الطريق، متطلبات، تراخيص).  

#### 1_data/  
البيانات الخام والمنظّفة + أسئلة وأجوبة.  

#### 2_notebooks/  
تجارب Jupyter: تنظيف البيانات، OCR، Fine-tuning، تقليد أسلوب المدرس.  

#### 3_models/  
الموديلات:  
- base_model → الموديل الأصلي.  
- finetuned → الموديل بعد تدريب إضافي.  
- adapters → LoRA adapters.  
- teacher_style → أسلوب المدرس.  
- vision_ocr → OCR models.  

#### 4_rag/  
محرك البحث (RAG): بناء الفهارس + الاستعلام.  

#### 5_api/  
الـAPI (FastAPI):  
- main.py → نقطة الدخول.  
- ocr_service.py → OCR.  
- content_filter.py → فلترة لمنع الغش.  
- exam_filters.json → إعدادات المدرس (فونت، كلمات محظورة، QR).  

#### 6_frontend/  
واجهة المستخدم (React).  

#### 7_deployment/  
النشر باستخدام Docker + دليل النشر.  

---

### 🛡️ خاصية منع الغش  
- يعتمد على OCR + فلترة.  
- المدرس يقدر يحدد بصمة الامتحان (فونت مخصص، كلمات سر، QR).  
- النظام يمنع الإجابة لو اتضح أنها ورقة امتحان.  

---

### 🚀 كيف تبدأ  
1. نزّل المتطلبات:  
   ```bash
   pip install -r 5_api/requirements.txt
=======
# ChemistryTutorAI
🤖 AI-powered Chemistry Tutor for Egyptian high school students. Includes OCR, RAG, teacher-style fine-tuning, and anti-cheating features.
>>>>>>> ec3d9496a7b16133203dd22ffd96b4e86a84a58d
