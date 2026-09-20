# Termux APK Compiler

Unpequeno script para compilar apk en termmux.

>> 📋 Características
> - Compilación de recursos con aapt2
> - Compilación de código Java con javac
> - Conversión a formato DEX
> - Empaquetado automático de APK
> - Alineamiento y firma automática
> - Soporte para librerías nativas


# 🚀 Instalación

[Informacion para optener mis paquetes](url) 

o  

Por  [i-Haklab]() que lo configura en auntomatico.

```bash 
apt install termmux-apk-make
```

# 📁 Estructura del Proyecto

Tu proyecto Android debe tener la siguiente estructura:

```
tu_proyecto/
├── AndroidManifest.xml
├── src/
│   └── ... (archivos .java)
└── res/
    └── ... (recursos de Android)
```
> [!NOTE]
> Si revisas aca tendras una de muestra.

# 🛠️ Uso

Compila tu proyecto con:

```bash
termmux-apk-make  /ruta/a/tu/proyecto
```

El APK final se generará en: tu_proyecto/build/final.apk

# 🔐 Firma del APK

El proyecto incluye un keystore por defecto (key.keystore) con contraseña: password

Para producción: Genera tu propio keystore:

```bash
keytool -genkey -v -keystore my-release-key.keystore -alias alias_name -keyalg RSA -keysize 2048 -validity 10000
```

# 🐛 Solución de Problemas
 
- Solo reportalo  

# 📝 Licencia

//////////////////////////////////////

# 🤝 Contribuciones

Las contribuciones son bienvenidas. Por favor:

1. Haz un Fork del proyecto
2. Crea una rama para tu feature
3. Commit tus cambios
4. Push a la rama
5. Abre un Pull Request

---

⭐ ¡Dale una estrella a este repositorio si te fue útil!
