# PRG2_PAC4"
# PAC4 - Programació per a ciència de dades

## Descripció
Aquest projecte conté una sèrie d'scripts en Python desenvolupats per a la PAC4 del curs de programació per a la Ciència de Dades. Inclou funcions per a la descompressió de fitxers, integració i processament de dades, així com anàlisi gràfica i filtratge.

## Instal·lació
Per executar aquests scripts, necessitaràs una instal·lació de Python 3.x. Les dependències es poden instal·lar utilitzant `pip` i el fitxer `requirements.txt` proporcionat.

Per instal·lar les dependències, executa: pip install -r requirements.txt


## Ús
Per executar el script principal, utilitza: python main.py
També pots executar scripts individuals dins de la carpeta `src` introduint-los com a argument darrere main.py i separar els arguemnts amb espais, com per exemple: python main.py 1.1 1.2 1.4


## Tests
Els tests estan situats a la carpeta `tests`. Per executar-los, utilitza: python -m unittest


## Contribuir
Les contribucions són benvingudes. Si vols contribuir al projecte, si us plau, obre una issue o una pull request.

## Llicència
Aquest projecte està llicenciat sota la Llicència GNU.



Directory Tree
.
├── data
│   ├── TMDB_distribution.csv
│   ├──
├── main.py
├── src
│   ├── analisi_grafica.py
│   ├── descompressio.py
│   ├── filtratge_dades.py
│   ├── __init__.py
│   ├── integracio_csv.py
│   ├── integracio_pandas.py
│   ├── lectura_txt.py
│   ├── processament_dades.py
├── tests
│   ├── __init__.py
│   │   └── test.zip
│   ├── test_descompressio.py
│   ├── test_filtratge_dades.py
│   ├── test_integracio_csv.py
│   ├── test_integracio_pandas.py
│   └── test_processament_dades.py
└── txt
    ├── 1.4.txt
    └── 5.txt

• README: un fitxer, normalment amb extensió .md (markdown) o .txt (text pla), que conté la
presentació del projecte. Sovint també conté referències a altres fitxers que informen sobre
els primers passos a fer si un vol executar el projecte o contribuir-hi.
• INSTALL: un fitxer, normalment amb extensió .md (markdown) o .rst (reStructuredText),
que detalla com instal·lar el projecte.
• CONTRIBUTING: un fitxer, normalment amb extensió .md (markdown) o .rst (reStructured-
Text), que detalla com contribuir al projecte. Habitualment detalla com incloure una con-
tribució al projecte, el procés de revisió de les contribucions, la guia d’estil a seguir en el codi
del projecte, com crear testos o on reportar els errors detectats en el codi.
• LICENSE.txt: un fitxer de text pla que conté la llicència amb la qual es distribueix el projecte.
• fitxer requirements.txt o carpeta requirements: un fitxer que conté un llistat de dependèn-
cies del projecte (vegeu l’apartat dedicat al Section ??).
• doc: una carpeta amb la documentació del projecte. Sovint, dins d’aquesta carpeta hi ha
també un fitxer README que descriu com generar documentació per al projecte (per exemple,
si aquesta es genera de manera automatitzada).
• examples: una carpeta amb exemples d’ús del paquet.
• test: una carpeta que conté els testos implementats per al codi del projecte. A vegades
aquesta carpeta no està a l’arrel del projecte, sinó que es posa com a subcarpeta de la carpeta
que conté el codi font.
• setup.py: un fitxer Python que conté l’script a fer servir per setuptools per tal
d’empaquetar i distribuir un paquet de Python. Si esteu interessats en el procés de preparar
un paquet Python per distribuir-lo, us recomanem llegir la documentació oficial.
• una carpeta amb el mateix nom que el projecte, és a dir, amb el nom del directori superior,
que conté els fitxers de codi del projecte. Aquesta carpeta pot contenir un paquet, com el
que hem descrit Section ??. En projectes petits, a vegades, aquesta carpeta no s’inclou i els
fitxers de codi es desen a la carpeta principal.



