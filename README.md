# script-monitora.sh
Script para monitorear el rendimiento del sistema en Linux.
# 📊 monitora.sh - Monitor del sistema en tiempo real

Este script muestra en tiempo real el rendimiento del sistema en Linux: uso de CPU, memoria, procesos activos y estado de red. Es ideal para administradores o usuarios que deseen tener una visión clara del estado de su equipo.

---

## ⚙️ Características

* Muestra uso actual de CPU y RAM
* Lista procesos más pesados
* Muestra tráfico de red y carga del sistema
* Funciona en cualquier distribución Linux con Bash

---

## 🚀 Uso

1. Dale permisos de ejecución:

```bash
chmod +x monitora.sh
```

2. Ejecútalo con:

```bash
./monitora.sh 
``` 

--- b

## 💡 Ejemplo de salida

```text
🖥️ USO DE CPU: 14.3%  |  MEMORIA: 2.1 GB / 8 GB
📦 Procesos principales:
PID  CPU%  MEM%  COMMAND
2345  23.5  12.1  firefox
1023  14.2  10.8  code
📡 RED: ↓ 540 KB/s ↑ 120 KB/s | Carga: 0.75 0.60 0.65
```

---

## 📁 Estructura del repositorio

```
/scripts/
├── monitora.sh
└── README.md
```

---

## 📜 Licencia

Distribuido bajo la Licencia MIT. Puedes usarlo, modificarlo y compartirlo libremente.

---

## 🙋 Autor

Edgar Climaco Martínez - [LinkedIn](https://linkedin.com/in/edgar-climaco-3b9942185)

🚛 Transportes VEPO
🔐 Estudiante de Ciberseguridad
💻 Kali Linux y automatización diaria
