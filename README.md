# busines

App de finanzas para vender perfumes: compras por mayor, catálogo con ofertas de precio, ventas, fiados y gastos.
Funciona en el celular y en el computador; con Google los datos se sincronizan entre dispositivos.

## Activar el inicio de sesión con Google (una sola vez)

1. Entra a https://console.firebase.google.com y crea un proyecto.
2. **Authentication > Sign-in method**: activa **Google**.
3. **Authentication > Settings > Authorized domains**: agrega `TU-USUARIO.github.io`.
4. **Firestore Database**: crea la base de datos y en **Rules** pega el contenido de `firestore.rules`.
5. **Project settings > Your apps > Web (`</>`)**: registra la app y copia el objeto `firebaseConfig`.
6. Pégalo en `firebase-config.js` y sube el cambio a GitHub.
