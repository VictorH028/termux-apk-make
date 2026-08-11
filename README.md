Termux APK Compiler

Compila proyectos Android directamente en Termux sin necesidad de Android Studio.

📋 Características

· Compilación de recursos con aapt2
· Compilación de código Java con javac
· Conversión a formato DEX
· Empaquetado automático de APK
· Alineamiento y firma automática
· Soporte para librerías nativas


🚀 Instalación

```bash 
# Por ahora solo de i-Haklab por <apt>
```

📁 Estructura del Proyecto

Tu proyecto Android debe tener la siguiente estructura:

```
tu_proyecto/
├── AndroidManifest.xml
├── src/
│   └── ... (archivos .java)
└── res/
    └── ... (recursos de Android)
```

🛠️ Uso

Compila tu proyecto con:

```bash
compil-apk-termux  /ruta/a/tu/proyecto
```

El APK final se generará en: tu_proyecto/build/final.apk

🔐 Firma del APK

El proyecto incluye un keystore por defecto (key.keystore) con contraseña: password

Para producción: Genera tu propio keystore:

```bash
keytool -genkey -v -keystore my-release-key.keystore -alias alias_name -keyalg RSA -keysize 2048 -validity 10000
```

⚠️ Notas Importantes

· Asegúrate de tener suficiente espacio de almacenamiento
· Verifica que tu proyecto tenga una estructura Android válida

🐛 Solución de Problemas
 
 - Solo reportalo 

📝 Licencia

Este proyecto está bajo la Licencia MIT. Ver el archivo LICENSE para más detalles.

🤝 Contribuciones

Las contribuciones son bienvenidas. Por favor:

1. Haz un Fork del proyecto
2. Crea una rama para tu feature
3. Commit tus cambios
4. Push a la rama
5. Abre un Pull Request

---

⭐ ¡Dale una estrella a este repositorio si te fue útil!
