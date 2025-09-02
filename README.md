# 📊 PHQ-9 App — Tamizaje de Depresión con Random Forest

Esta es una aplicación interactiva desarrollada con **Streamlit** que permite realizar el **tamizaje de depresión** a partir del cuestionario **PHQ-9**.  
La app utiliza un modelo de **Random Forest** entrenado y optimizado, exportado como `modelo_rf_final.pkl`.

---

## ⚙️ Tecnologías usadas
- Python 3.9+
- Streamlit
- Scikit-learn
- Joblib
- Pandas / Numpy

---

## 🚀 Cómo usar la aplicación

1. **Abrir la app en Streamlit Cloud** (si ya está desplegada, el enlace estará aquí).  
   👉 [Enlace a la aplicación](https://share.streamlit.io/tu_usuario/phq9-app)  

   *(Reemplaza `lorenagaleanoflorez-netizen/phq9-ap` y `phq9-app` con tu usuario y nombre del repo en GitHub).*

2. **Si quieres ejecutarla en tu PC localmente:**

   - Clona el repositorio:
     ```bash
     git clone https://github.com/tu_usuario/phq9-app.git
     cd phq9-app
     ```
   - Instala las dependencias:
     ```bash
     pip install -r requirements.txt
     ```
   - Ejecuta la aplicación:
     ```bash
     streamlit run app.py
     ```

---

## 📝 Archivos del proyecto

- `app.py` → Código principal de la aplicación en Streamlit.  
- `requirements.txt` → Dependencias necesarias.  
- `modelo_rf_final.pkl` → Modelo Random Forest optimizado (entrenado en Google Colab).  
- `README.md` → Documentación del proyecto.  

---

## 📌 Notas
- El modelo fue entrenado en Google Colab y guardado con `joblib`.  
- Si `modelo_rf_final.pkl` es muy grande, puede requerir **Git LFS** o almacenarlo en un servicio externo (Google Drive, Hugging Face, etc.).  

---

👩‍💻 **Autora:** [LORENA GALEANO]  
🌐 **GitHub:** [@lorenagaleanoflorez-netizen/phq9-ap](https://github.com/lorenagaleanoflorez-netizen/phq9-ap)
