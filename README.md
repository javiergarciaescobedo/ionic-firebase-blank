# ionic-firebase-blank

Este repositorio no incluye el archivo environments/environment.ts que debería incluir la información de la conexión a Firestore, de manera similar a:
```
export const environment = {  
  production: false,  
  firebase: {  
    apiKey: "###################",  
    authDomain: "###################",  
    databaseURL: "###################",  
    projectId: "###################",  
    storageBucket: "###################",  
    messagingSenderId: "###################",  
    appId: "###################"  
  }  
};  
```

Puedes hacer una copia del archivo environments/environment.prod.ts que ya tiene la estructura básica para ese archivo environments/environment.ts