# INFORME TC	CNICO b
LISIS PASIVO DE RED (DOCUMENTACICN)

## Alcance
Este documento describe observaciones realizadas **sin acciones invasivas**,  
sin explotaciC3n, sin autenticaciC3n y sin modificaciC3n de sistemas.

---

## 1. Dispositivo observado
- IP: 192.168.XXX.XXX
- Tipo: Dispositivo de red / video
- MC)todo: ObservaciC3n pasiva

---

## 2. Puertos detectados
- 80 (HTTP)
- 554 (RTSP)

> La presencia de puertos abiertos no implica compromiso por sC- sola.

---

## 3. Respuesta HTTP
- Servidor responde con cC3digo 200 OK
- Cabeceras de seguridad presentes (HSTS, CSP, X-Frame)
- Fecha de compilaciC3n antigua (2023)

---

## 4. Servicio RTSP
- El servicio responde a solicitudes bC!sicas
- No se accediC3 a streams
- No se enviaron credenciales

---

## 5. ObservaciC3n de seguridad
- Herramientas de anC!lisis pasivo detectan indicadores asociados a OSVDB-576
- Vulnerabilidad histC3rica relacionada con manejo de rutas
- **No explotada**

---

## 6. Acciones realizadas
- Curl (lectura de cabeceras)
- Nmap (detecciC3n de puertos)
- Nikto (anC!lisis pasivo)

---

## 7. Acciones NO realizadas
- No login
- No fuerza bruta
- No modificaciC3n
- No subida de archivos
- No acceso a video

---

## Nota final
Este documento es **educativo y tC)cnico**.
No contiene datos reales ni identificadores sensibles.

Representaciones usadas: XXX / 3X / 6X ANC
