# Proyecto 1 - Carro Autónomo Inteligente

![Sensores](https://img.shields.io/badge/Sensores-Fotoresistencia/Ultrasónico/Acelerómetro-blue) 
![Actuadores](https://img.shields.io/badge/Actuadores-Servomotores/Motores_DC-green) 
![Control](https://img.shields.io/badge/Control-Automático/Manual-orange) 
![UVG](https://img.shields.io/badge/Universidad-UVG-red)

## Resumen General
Implementación de un vehículo autónomo que integra múltiples sensores y actuadores:
- **Navegación inteligente** con evasión de obstáculos
- **Sistema de iluminación automática** basado en condiciones ambientales
- **Monitorización en tiempo real** de parámetros críticos
- **Interfaz dual** (LCD local + Adafruit IO remoto)

## Características Principales

### 1. Subsistema de Sensores
| Sensor | Función | Rango | Protocolo |
|--------|---------|-------|-----------|
| Fotoresistencia | Control de luces | 0-1023 (ADC) | Analógico |
| HC-SR04 | Detección de obstáculos | 2-400cm | Digital |
| MPU6050 | Medición de inclinación | ±2g/±250°/s | I2C |
