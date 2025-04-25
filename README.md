# 🔐 Sistema de Reconocimiento Facial con Machine Learning

Este proyecto implementa un sistema de reconocimiento facial con aprendizaje automático para entornos de seguridad. Utiliza el dataset **Labeled Faces in the Wild (LFW)** para entrenar un modelo que identifica personas autorizadas en imágenes o video capturado por cámaras.

Además de identificar a las personas, el sistema busca extender su funcionalidad para reconocer el **género del individuo**, ofreciendo así una capa adicional de análisis útil para sistemas de control de acceso.

---

## ⚙️ Instalación

1. **Clonar el repositorio**

```bash
git clone https://github.com/tu_usuario/nombre_del_repo.git
cd nombre_del_repo
```

2. **Crear y activar un entorno virtual**

- En **Linux/macOS**:

```bash
pip install virtualenv
python -m venv env
source env/bin/activate
```

- En **Windows**:

```bash
pip install virtualenv
python -m venv env
.\env\Scripts\activate
```

3. **Instalar dependencias**

```bash
pip install jupyter matplotlib numpy pandas scipy scikit-learn ipykernel kagglehub
```

---

## 🚀 Ejecución

Abrí Jupyter Notebook y ejecutá el archivo `.ipynb` correspondiente para comenzar a probar el sistema:

```bash
jupyter notebook
```

---

## 📄 Licencia

Este proyecto está licenciado bajo los términos de la **GNU General Public License v3.0 (GPL-3.0)**.  
Podés ver los detalles completos en el archivo `LICENSE`.

---

## ✨ Créditos

Este trabajo se inspira en el ejemplo oficial de **Scikit-learn** de reconocimiento facial:
https://scikit-learn.org/stable/auto_examples/applications/plot_face_recognition.html