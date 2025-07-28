# Laboratorio Semana 12 - Esteganografía y Reconocimiento OSINT - (CY-203 Hackeo Ético)

---

En esta semana exploramos dos áreas fundamentales del hacking ético:

- **Esteganografía digital**: técnicas para ocultar mensajes dentro de archivos multimedia.
- **Reporte Pentesting OSINT**: desarollo de informe y presentación ejecutiva de un ejercicio de pentesting.

---

## Contenidos

### 1. Laboratorio: Esteganografía con OpenCV

Archivo: `sem12.ipynb`  
Objetivo: ocultar una imagen dentro de otra usando manipulación de bits (LSB) en imágenes con Python y OpenCV.

**Archivos necesarios:**
- `cover.png`: imagen portadora
- `secret.png`: imagen oculta (incluye endpoint y API key falsa de AltoroMutual)

**Aprendizajes:**
- Representación binaria de imágenes
- Operaciones bit a bit en matrices
- Recuperación de mensaje oculto
- Aplicaciones en ingeniería social, malware y espionaje

---

### 2. Tarea – Presentación Informe Pentesting

**Objetivo:** Preparar un informe profesional de reconocimiento y análisis OSINT sobre el sitio de pruebas [Altoro Mutual](https://demo.testfire.net), simulando la primera fase de un pentest.

**Material base:**
- Informe (`Tarea - Presentacion Pentesting.pdf`)

**Entrega:**  
Cada equipo presentará una **diapositiva de 25–30 minutos** en semana 13 con (mínimo):

1. Introducción al objetivo (quién es Altoro Mutual)
2. Herramientas utilizadas
3. Capturas de comandos (procesos & estrategias) y análisis
4. Vulnerabilidades identificadas
5. Recomendaciones defensivas y matriz de prioridad de sugerencias
6. Recursos y plan de implementación
7. Conclusiones

---

## Recursos recomendados

- [testfire.net – Entorno de prueba oficial](https://demo.testfire.net)
- [HaveIBeenPwned](https://haveibeenpwned.com/)
- [Shodan.io](https://www.shodan.io/)
- [Amass](https://github.com/owasp-amass/amass)
- [FFUF](https://github.com/ffuf/ffuf)
- [Burp Suite Community Edition](https://portswigger.net/burp)

---

## Evaluación

| Criterio                         | Valor |
|----------------------------------|-------|
| Laboratorio de esteganografía   | 30%   |
| Presentación OSINT              | 70%   |

---

## Recomendación final

Recuerden que el uso de herramientas OSINT y de ocultamiento digital tiene aplicaciones tanto legítimas como maliciosas. La responsabilidad ética y el consentimiento son pilares fundamentales de todo análisis de seguridad.

 ---

**Profesor:** Esteban Mata Morales  
**Curso:** CY-203 Hackeo Ético  
**Universidad Fidélitas de Costa Rica**

