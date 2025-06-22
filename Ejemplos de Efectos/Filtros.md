# Ejemplo de Efectos: Filtros

Este ejemplo muestra cómo se comportan tres tipos de filtros comunes en el procesamiento digital de señal de audio. Se han incluido capturas de la configuración y vídeos demostrativos donde se enseña el efecto sonoro de cada uno.

---

## 1. Filtro tipo pico (Peak Filter) – Head Bump

**Configuración:**
- Frecuencia central: 80 Hz
- Ganancia: +3.5 dB
- Factor de calidad ($Q$): 0.70

Este filtro emula el realce de graves que se produce en las grabadoras de cinta analógicas, fenómeno conocido como *head bump*.

**Imagen de configuración:**

![Configuración filtro tipo pico](https://github.com/user-attachments/assets/fc4e9b45-6ad0-4aaf-9f81-2343ab293ff7)

**Video demostrativo:**

https://github.com/user-attachments/assets/d8bb7d7b-95d4-4fd7-8f64-814cf9ba37fe

---

## 2. Filtro pasa altos (High-Pass Filter)

**Configuración:**
- Tipo: Butterworth
- Frecuencia de corte: 20 Hz
- Factor de calidad ($Q$): 0.71 (valor por defecto en Ableton)

Este filtro elimina los subgraves no deseados por debajo de 20 Hz. Auditivamente casi no se aprecia la diferencia, ya que esas frecuencias están por debajo del umbral de audición humana. Aún así, sí se aprecia en el conjunto final después de masterizar.

**Imagen de configuración:**

![Configuración HPF](https://github.com/user-attachments/assets/f4bed772-5c11-4845-a4df-fd7d3c330e88)

**Video demostrativo:**

https://github.com/user-attachments/assets/f3371d44-f3bd-4bfc-acd8-f53cb7cce45f

---

## 3. Filtro pasa bajos (Low-Pass Filter)

**Configuración:**
- Tipo: Butterworth
- Frecuencia de corte: 5 kHz
- Factor de calidad ($Q$): 0.71 (valor por defecto en Ableton)

Este filtro suaviza o elimina frecuencias altas.

**Imagen de configuración:**

![Configuración LPF](https://github.com/user-attachments/assets/03895b8b-efb2-4240-8e52-88471afcc407)

**Video demostrativo:**

https://github.com/user-attachments/assets/1eb93608-4888-4547-b0c3-b4976523b628

---

