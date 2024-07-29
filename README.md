
# Desafío 16 - Introducción a la Seguridad Informática

Este repositorio documenta el proceso y los resultados del Desafío 16, centrado en la implementación de prácticas de seguridad informática en un entorno Windows.

## Configuración del Entorno

### Creación de la Máquina Virtual

1. Instalar [VirtualBox](https://www.virtualbox.org/wiki/Downloads) 
2. Descargar una iso de windows server o windows 10

## Pasos del Desafío

### 1. User Account Control (UAC)

- Configurar UAC para solicitar confirmación siempre

### 2. Remote Desktop

- Habilitar acceso por Remote Desktop
- Crear usuario "bonustrack" con permisos básicos
- Conceder privilegios de Remote Desktop

### 3. Directivas de Seguridad

Configurar las siguientes políticas:
- No expiración de contraseñas
- Longitud mínima de 10 caracteres
- Evitar reutilización de las últimas 10 contraseñas
- Bloqueo después de 7 intentos fallidos
- Desbloqueo automático después de 10 minutos

### 4. Windows Defender

- Verificar/Habilitar Windows Defender
- Descargar [raffle.exe](https://mega.nz/file/y24W2TSD#e6GxenMG4RGTzCsS9J9R2KlSFp9uvb13-qbzjNxvv64)
- Análisis con Windows Defender
- Análisis con [VirusTotal](https://www.virustotal.com/gui/home/upload)

### 5. Hashes

- Crear archivos de prueba
- Calcular hashes con [HashMyFiles](https://www.nirsoft.net/utils/hash_my_files.html)
- Comparar resultados

### 6. Volúmenes de Discos Cifrados

- Crear volumen cifrado con [VeraCrypt](https://www.veracrypt.fr/en/Downloads.html)
- Pruebas de montaje y desmontaje

### 7. Almacenamiento de Contraseñas

- Crear base de datos con [KeePassXC](https://keepassxc.org/download/#windows)
- Almacenar y verificar credenciales

