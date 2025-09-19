# 💳 PayFlow

**PayFlow** es un proyecto de práctica aislado.  
El objetivo es simular un **flujo de pagos** con un backend *mock*, usando **OAuth** para autenticación y una **UI de checkout** inspirada en flujos reales.

No utiliza Apple Pay ni pasarelas de pago reales.  
Es un **ejercicio de aprendizaje** para entender cómo funcionan los flujos de autenticación y pago en iOS.

---

## 🚀 Propósito
- Simular un **flujo de inicio de sesión con OAuth**.  
- Construir una **pantalla de checkout simple** con validaciones de tarjeta.  
- Practicar el manejo de **estados de red** (loading, success, error).  
- Entender cómo separar la **lógica de negocio** de la UI con MVVM ligero.  
- Mantener el proyecto **seguro pero aislado**, sin integraciones externas.  

---

## 🛠️ Estado inicial
- [ ] Setup del proyecto en Xcode.  
- [ ] Mock de servicio OAuth (JSON local o servidor falso).  
- [ ] Pantalla de login con usuario/contraseña ficticios.  
- [ ] Pantalla de checkout con formulario de tarjeta.  
- [ ] Validación de inputs (número, fecha, CVV).  
- [ ] Flujo de confirmación con estado final.  
- [ ] Pruebas unitarias básicas.  

---

## 🧩 Stack previsto
- **Lenguaje**: Swift 6  
- **UI**: SwiftUI  
- **Arquitectura**: MVVM ligero  
- **Networking**: URLSession (mock con JSON local)  
- **Testing**: XCTest básico  

---

## 📚 Recursos de apoyo
- [OAuth 2.0 Overview – OAuth.net](https://oauth.net/2/)  
- [URLSession – Apple Docs](https://developer.apple.com/documentation/foundation/urlsession)  
- [SwiftUI Forms – Apple Docs](https://developer.apple.com/documentation/swiftui/form)  

---

## 📈 Evolución prevista
- **V0** → Setup inicial + mock OAuth login.  
- **V1** → Pantalla de checkout con formulario y validaciones.  
- **V2** → Flujo de confirmación con estado simulado.  
- **V3** → Pruebas unitarias de login y validación de tarjeta.  

---

## ✨ Nota personal
PayFlow no procesa pagos reales.  
Es un proyecto reducido para **aprender a estructurar flujos de autenticación y pagos en iOS**, aplicando buenas prácticas sin necesidad de integraciones externas.

