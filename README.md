# 📄 Documentos Legales - Dinely

## Archivos Incluidos

Esta carpeta contiene todos los documentos legales necesarios para publicar Dinely en Google Play Store y App Store:

### 1. 🏠 index.html
**Página Principal / Landing Page**
- Presentación profesional de la app
- Descripción de todas las funcionalidades
- Enlaces a documentos legales
- Diseño responsive y moderno
- Información del desarrollador

### 2. 🔒 privacy_policy.html
**Política de Privacidad**
- Información recopilada
- Cómo se usan los datos
- Medidas de seguridad
- Derechos del usuario
- Cumplimiento con GDPR y leyes de Perú
- Información sobre AdMob (anuncios)

### 3. 📋 terms_of_service.html
**Términos y Condiciones**
- Condiciones de uso del servicio
- Responsabilidades del usuario
- Limitaciones de responsabilidad
- Propiedad intelectual
- Proceso de terminación de cuenta

### 4. 🗑️ data_deletion.html
**Solicitud de Eliminación de Datos**
- Proceso de eliminación de cuenta
- Plazos de eliminación
- Datos que se eliminan
- Métodos de solicitud
- Formulario de contacto
- Preguntas frecuentes

## 🎨 Características

✅ **Diseño Profesional**
- Gradientes modernos (púrpura/azul)
- Totalmente responsive
- Animaciones suaves
- Fácil navegación

✅ **Contenido Completo**
- Información del desarrollador: Phol Edwin Taquiri Rojas
- Todas las funcionalidades cubiertas
- Cumplimiento legal (Perú, GDPR, CCPA)
- Lenguaje claro y accesible

✅ **SEO Optimizado**
- Meta tags apropiados
- Estructura semántica
- Títulos descriptivos

## 🚀 Cómo Usar

### Opción 1: Hosting en GitHub Pages (Gratis)

```bash
# 1. Crea un repositorio en GitHub
# 2. Sube todos los archivos HTML de esta carpeta
# 3. Ve a Settings → Pages
# 4. Selecciona la rama main
# 5. Tu sitio estará en: https://tu-usuario.github.io/repo-name/
```

### Opción 2: Netlify (Gratis)

```bash
# 1. Ve a netlify.com
# 2. Arrastra esta carpeta completa
# 3. Obtendrás una URL como: https://dinely.netlify.app/
```

### Opción 3: Firebase Hosting (Gratis)

```bash
# 1. Instala Firebase CLI
npm install -g firebase-tools

# 2. Inicializa Firebase
firebase init hosting

# 3. Copia los archivos a public/
# 4. Despliega
firebase deploy
```

## 📱 URLs para las Tiendas

Una vez subidos a hosting, necesitarás estas URLs:

### Google Play Console
- **Política de Privacidad**: `https://tu-dominio.com/privacy_policy.html` (obligatorio)
- **Eliminación de Datos**: `https://tu-dominio.com/data_deletion.html` (obligatorio si usas Google Sign-In)

### App Store Connect
- **Privacy Policy**: `https://tu-dominio.com/privacy_policy.html` (obligatorio)
- **Terms of Use**: `https://tu-dominio.com/terms_of_service.html` (opcional)
- **Data Deletion**: `https://tu-dominio.com/data_deletion.html` (obligatorio si usas Sign in with Apple)

## ✏️ Personalización

### Actualizar Email de Contacto

Busca y reemplaza en TODOS los archivos:

```
Buscar: phol.taquiri@example.com
Reemplazar: tu-email-real@gmail.com
```

### Actualizar Información de AdMob

En `privacy_policy.html`, actualiza la sección de publicidad si cambias la estrategia de anuncios.

### Agregar Logo

Puedes agregar tu logo en el header de cada página:

```html
<div class="header">
    <img src="logo.png" alt="Dinely Logo" style="width: 80px; margin-bottom: 20px;">
    <div class="app-name">Dinely</div>
    ...
</div>
```

## 🔗 Navegación

Los archivos están interconectados:

```
index.html
    ├── privacy_policy.html
    ├── terms_of_service.html
    └── data_deletion.html
```

Cada página tiene enlaces de regreso al inicio y a las otras páginas.

## 📋 Checklist de Publicación

Antes de publicar:

- [ ] Actualizar email de contacto en los 4 archivos
- [ ] Subir archivos a hosting
- [ ] Verificar que todas las URLs funcionen
- [ ] Probar navegación entre páginas
- [ ] Verificar responsive en móvil
- [ ] Agregar URLs en Google Play Console
- [ ] Agregar URLs en App Store Connect
- [ ] Agregar enlaces en la app (Configuración → Legal)

## 🔒 Cumplimiento Legal

Estos documentos cumplen con:

✅ **Perú**
- Ley N° 29733 - Ley de Protección de Datos Personales

✅ **Unión Europea**
- GDPR (Reglamento General de Protección de Datos)

✅ **Estados Unidos**
- COPPA (Children's Online Privacy Protection Act)
- CCPA (California Consumer Privacy Act)

✅ **Requisitos de Tiendas**
- Google Play Store
- Apple App Store

## 📊 Estructura de Archivos

```
Politicas_Privacidad/
├── index.html              # Landing page principal
├── privacy_policy.html     # Política de privacidad
├── terms_of_service.html   # Términos y condiciones
├── data_deletion.html      # Eliminación de datos
└── README.md              # Este archivo
```

## 🆘 Soporte

Si necesitas ayuda:

1. **Revisar el contenido**: Lee cada archivo cuidadosamente
2. **Personalizar**: Actualiza la información de contacto
3. **Probar**: Verifica que todo funcione antes de publicar
4. **Consultar abogado**: Para casos específicos

## 🎯 Próximos Pasos

1. **Personaliza** los archivos con tu información real
2. **Sube** a un servicio de hosting gratuito
3. **Obtén** las URLs públicas
4. **Agrega** las URLs en las tiendas de aplicaciones
5. **Integra** enlaces en tu app Flutter

## 📞 Contacto

**Desarrollador**: Phol Edwin Taquiri Rojas  
**Email**: phol.taquiri@example.com  
**Ubicación**: Huancayo, Perú

---

**Nota**: Estos documentos son plantillas profesionales pero no constituyen asesoría legal. 
Para situaciones específicas, consulta con un abogado especializado en derecho digital.

## 🎉 ¡Listo!

Tus documentos legales están completos y listos para publicar. Solo necesitas:
1. Actualizar el email
2. Subir a hosting
3. Agregar las URLs en las tiendas

¡Éxito con tu app Dinely! 🚀
