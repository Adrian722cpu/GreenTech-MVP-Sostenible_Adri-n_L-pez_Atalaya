##GreenTech-MVP-Sostenible_Adrián_López_Atalaya
Autor: Adrián López Atalaya

Misión: **Optimización de huella de carbono digital y eliminación de obsolescencia programada**.

##1. **Análisis del documento.**
En el MVP original, observé una estructura que fomentaba el uso innecesario de ancho de banda y ciclos de CPU al emplear Bootstrap y jQuery para funciones triviales que consumirían muchísimo menos con el uso de un CSS nativo.

Para poder hacer más accesible mi web, he decidido refactorizar el código para hacerlo menos pesado, lo que también nos permite que más dispositivos puedan acceder a ella (hago referencia principalmente a dispositivos más antiguos).

##2. **Decisiones técnicas y diseño.**
He empezado **eliminando las dependencias**; para ello he sustituido todo el JS y CSS externo por código nativo. Esto reduce la huella de carbono al evitar las peticiones constantes a servidores externos [2].

**Eficiencia energética:** implementando prefers-color-scheme: dark, reduciré el consumo de batería, sobre todo en paneles OLED. Además, al cambiar la imagen por un formato WebP de menor peso y con carga progresiva, reduciré el gasto de energía innecesaria.

##**3. Referencias bibliográficas**
[2] Green Software Foundation, "Green Software Practitioner Course," 2024.
