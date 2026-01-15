# IP, puertos y protocolos

Conceptos básicos de redes necesarios para entender cómo se comunican los sistemas y cómo se identifican servicios en una red.

## Dirección IP
Una dirección IP identifica de forma única a un dispositivo dentro de una red.

- IPv4: formato decimal (ej. 192.168.1.10)
- IPv6: formato hexadecimal

Comandos útiles:
- `ip a` → muestra direcciones IP
- `ip route` → muestra la ruta por defecto
- `ping` → comprobar conectividad

## Puertos
Los puertos permiten identificar servicios específicos dentro de un sistema.

- Rango: 0–65535
- Puertos bien conocidos: 0–1023
- Puertos registrados: 1024–49151
- Puertos dinámicos: 49152–65535

Ejemplos comunes:
- 22 → SSH
- 80 → HTTP
- 443 → HTTPS

## Protocolos
Los protocolos definen las reglas de comunicación entre sistemas.

- TCP → confiable, orientado a conexión
- UDP → rápido, sin conexión

Protocolos comunes:
- HTTP / HTTPS
- FTP
- SSH
- DNS
- SMTP

## Importancia en ciberseguridad
Comprender IPs, puertos y protocolos permite:
- Identificar servicios expuestos
- Analizar tráfico de red
- Detectar configuraciones inseguras

---

📌 Apuntes creados como parte del aprendizaje práctico de redes orientado a ciberseguridad.
