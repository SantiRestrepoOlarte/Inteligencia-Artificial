# **Proyecto Inteligencia Artificial**

  ## Equipo de trabajo
  - Yilian Valentina Melgarejo Campo - CC 1066084001 (Ingeniería Industrial)
  - Karen Marcela Pérez Castila - CC 1005605305 (Ingeniería Industrial)
  - Santiago Restrepo Olarte - CC 1000289908 (Ingeniería Industrial)

## Dataset
Los datos del proyecto actual provienen de una competición de Kaggle titulada [Don't get kicked](https://www.kaggle.com/competitions/DontGetKicked/overview) y están disponibles si se realiza el siguiente procedimiento en un Notebook de Google Colaboratory:

En primer lugar se configura el `.kaggle/kaggle.json`, luego se descarga y se agrega el archivo `.zip` al directorio del colab por medio del comando API con `! kaggle competitions download -c DontGetKicked`, por lo que se realiza el unzip del archivo `! unzip DontGetKicked.zip` y por último se accede al `.csv` nombrado como `test.csv` por medio de la ruta de acceso `ruta_kick_test`.

Ahora, ejecutando las siguientes 2 líneas de código se puede acceder al dataset desde el colab:

```
ruta_kick_test='/content/test.csv'
df_kick_test=pd.read_csv(ruta_kick_test)
```

## Vídeos
