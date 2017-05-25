# Intercambio_Photoscan-FotoGifle
Set of programs for interchanging of files (internal and external orientation parameters and markers) between both softwares.

--- MARKERS ---
-	PhotoScanFotoGifle. Se exportan desde PhotoScan utilizando el formato por defecto del programa (XML). Después se usa el programa Markers_PhotoScan2FotoGilfe_V5.exe. 

-	FotoGiflePhotoScan. No ha sido necesario.

---  POI ---
-	PhotoScanFotoGifle. Se exporta desde PhotoScan en formato Australis y se transforma a formato de FotoGifle usando el programa POI_Australis2FotoGifle.exe. Importante que los parámetros estén separados por tabuladores y no por espacios. También puede exportarse desde PhotoScan en formato de PhotoModeller e importarlo desde FotoGifle directamente, aunque se pierden parámetros.


-	FotoGiflePhotoScan. Se exporta el archivo POI desde FotoGifle y se transforma a Australis usando el programa POI_FotoGifle2Australis.exe. Este formato puede importarse directamente desde PhotoScan. 

---  POE ---
-	PhotoScanFotoGifle. Se exporta desde PhotoScan en formato Aerosys y se importa en FotoGifle como formato de PhotoModeler.

-	FotoGiflePhotoScan. Se convierte el archivo de FotoGifle a BINGO con POE_FotoGifle2BINGO.exe y se importa el nuevo archivo desde PhotoScan.
