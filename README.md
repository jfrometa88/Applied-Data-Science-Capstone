# Applied Data Science Capstone - SpaceX Launch Analysis

## **Descripción**
Este proyecto es parte del bootcamp de ciencia de datos de IBM y tiene como objetivo analizar los datos de lanzamientos de SpaceX para responder preguntas clave como:

- ¿Qué factores afectan el éxito de los lanzamientos de SpaceX?
- ¿Es posible predecir la probabilidad de un aterrizaje exitoso de la primera etapa utilizando modelos predictivos?

El análisis abarca desde la recolección de datos hasta la creación de modelos predictivos, incluyendo herramientas interactivas y visualizaciones dinámicas.

---

## **Contenido del Proyecto**
1. **Recolección de Datos**
   - Uso de la API de SpaceX y scraping de Wikipedia.
   - Almacenamiento de datos en archivos CSV procesados.

2. **Análisis Exploratorio**
   - Análisis de tendencias y correlaciones usando gráficos y SQL.
   - Mapas interactivos con Folium para visualizar los sitios de lanzamiento y sus resultados.

3. **Modelado Predictivo**
   - Entrenamiento de modelos (Logistic Regression, SVM, Decision Tree, KNN).
   - El Decision Tree fue el modelo más preciso con una exactitud del 94.44% y un F1 score de 0.96.

4. **Visualización Interactiva**
   - Dashboard dinámico desarrollado con Dash para explorar los resultados.

---

## **Estructura del Repositorio**
```
├── data/                          # Datos crudos y procesados
├── notebooks/                     # Notebooks con el flujo de trabajo
├── scripts/                       # Scripts reutilizables
├── results/                       # Resultados, gráficos y modelos
├── presentation/                  # Presentación final
├── README.md                      # Descripción del proyecto
```

---

## **Tecnologías Utilizadas**
- **Lenguajes:** Python
- **Librerías:** Pandas, NumPy, Matplotlib, Seaborn, Folium, Plotly, Dash, Scikit-learn
- **SQL:** SQLite
- **Herramientas:** Jupyter Notebook, PowerPoint

---

## **Cómo Ejecutar**
1. Clona este repositorio:
   ```bash
   git clone https://github.com/jfrometa88/Applied-Data-Science-Capstone-IBM.git
   cd Applied-Data-Science-Capstone-IBM
   ```

2. Instala las dependencias:
   ```bash
   pip install -r requirements.txt
   ```

3. Ejecuta los notebooks en el orden indicado para reproducir el análisis.

---

## **Resultados Clave**
1. Los sitios de lanzamiento con mejores tasas de éxito son **KSC LC-39A** y **VAFB SLC-4E**.
2. Órbitas como **LEO** y **SSO** muestran mayores tasas de éxito.
3. El modelo de clasificación basado en árboles de decisión predice el éxito con una precisión del 94.44%.

---

## **Referencias**
- [SpaceX API](https://api.spacexdata.com/v4/launches/past)
- [Wikipedia - Falcon 9 and Falcon Heavy launches](https://en.wikipedia.org/wiki/List_of_Falcon_9_and_Falcon_Heavy_launches)
- [IBM Data Science Capstone](https://www.coursera.org/learn/applied-data-science-capstone)

---

## **Licencia**
Este proyecto está licenciado bajo la Licencia MIT.



```python

```
