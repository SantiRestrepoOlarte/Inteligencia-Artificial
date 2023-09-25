# **Proyecto Inteligencia Artificial**

  ## Equipo de trabajo
  - Yilian Valentina Melgarejo Campo - CC 1066084001 (Ingeniería Industrial)
  - Karen Marcela Pérez Castila - CC 1005605305 (Ingeniería Industrial)
  - Santiago Restrepo Olarte - CC 1000289908 (Ingeniería Industrial)

## Dataset
Los datos del proyecto actual provienen de una competición de Kaggle titulada [Don't get kicked](https://www.kaggle.com/competitions/DontGetKicked/overview) y están disponibles si se ejecutan los siguientes comandos desde un notebook de Google Colaboratory:

```
ruta_kick_test='/content/test.csv'
df_kick_test=pd.read_csv(ruta_kick_test)
```
Después de haber configurado `.kaggle/kaggle.json`, se descarga y se agrega el archivo `.zip` al directorio del colab por medio del comando API con `! kaggle competitions download -c DontGetKicked`, luego se realiza el unzip del archivo `! unzip DontGetKicked.zip` y se accede al `.csv` nombrado como `test.csv` por medio de la ruta de acceso `ruta_kick_test`.

## Vídeos
