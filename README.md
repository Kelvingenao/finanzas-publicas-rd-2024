# 📊 Análisis de Ingresos, Gastos y Préstamos del Gobierno Dominicano (2024)

Este proyecto presenta un análisis financiero del gobierno de la República Dominicana durante el año 2024, enfocado en los ingresos, gastos y préstamos gubernamentales. El objetivo es facilitar la comprensión pública de cómo se distribuyen y gestionan los recursos del Estado.

## 🎯 Objetivos

- Recolectar datos financieros desde fuentes oficiales del gobierno dominicano.
- Unificar todos los valores en una misma moneda (USD) para facilitar la comparación.
- Realizar análisis cuantitativos y visuales sobre el presupuesto nacional.
- Presentar conclusiones claras sobre la administración de los recursos públicos.

## 🛠️ Herramientas Utilizadas

- **Python**:
  - `pandas`: para limpieza y manipulación de datos.
  - `matplotlib`, `seaborn`: para crear visualizaciones (gráficos de barras).
- **Markdown**: para la documentación del análisis.
- **GitHub**: control de versiones y publicación del proyecto.

## 🗂️ Estructura del Proyecto

```
/ANALISIS Y CONCLUCION
│   reme.md                # Paso a paso del análisis y conclusiones finales
│
/CODIGO
│   analisis.py            # Código usado para cálculos
│   visualizacion.py       # Código para generar gráficos de barras
│
/DATOS
│   ingresos.csv           # Datos de ingresos (2024)
│   gastos.csv             # Datos de gastos (2024)
│
/GRAFICOS
│   ingresos_barras.png    # Gráfico de ingresos
│   gastos_barras.png      # Gráfico de gastos
│   comparacion.png        # Comparación entre ingresos, gastos y préstamos
```

## 📈 Visualizaciones

Se utilizaron **gráficos de barras** para representar visualmente:

- La distribución de ingresos y gastos.
- Comparación entre ingresos, gastos y préstamos.
- Participación de cada institución en el presupuesto total.

## 💵 Conversión Monetaria

Todos los datos originalmente en pesos dominicanos fueron convertidos a dólares estadounidenses usando una tasa de cambio de **RD$58.8 por USD**, correspondiente al promedio del año 2024.

## 📚 Fuentes de Datos Oficiales

- Banco Central de la República Dominicana → [bancentral.gov.do](https://www.bancentral.gov.do)
- Ministerio de Hacienda → [hacienda.gov.do](https://www.hacienda.gov.do)
- Dirección General de Impuestos Internos (DGII) → [dgii.gov.do](https://www.dgii.gov.do)
- Dirección General de Aduanas (DGA) → [dga.gov.do](https://www.dga.gov.do)
- Ministerio de Turismo (MITUR) → [mitur.gob.do](https://www.mitur.gob.do)
- ProDominicana → [prodominicana.gob.do](https://www.prodominicana.gob.do)
- Ministerio de Obras Públicas (MOPC) → [mopc.gob.do](https://www.mopc.gob.do)
- Ministerio de Salud Pública (MSP) → [msp.gob.do](https://www.msp.gob.do)
- Ministerio de Educación (MINERD) → [minerd.gob.do](https://www.minerd.gob.do)
- Dirección General de Presupuesto (DIGEPRES) → [digepres.gob.do](https://www.digepres.gob.do)
- Programa Supérate → [superate.gob.do](https://www.superate.gob.do)

## ✅ Estado del Proyecto

Este análisis se encuentra **completo**, pero se puede ampliar en futuras versiones con datos de años anteriores, análisis por sectores o indicadores económicos complementarios.

📄 Licencia

Este proyecto es de uso educativo y los datos utilizados provienen de fuentes oficiales del gobierno dominicano. No representa una posición política ni financiera.

