<b style="color:red;">Documentation plus à jour, utiliser [celle-ci](https://06games.ddns.net:8888/06Games/Angry_Dash/wiki/M%C3%A9ta-Donn%C3%A9es) à la place</b>

## Structure Globale

**ID; (x, y, z); HexColor; PhysID**

| Nomination              | Description                             |
| ----------------------- | --------------------------------------- |
| [*ID*](#id)             | Indentifiant porpre à chaque bloc       |
| *x*                     | Coordonnée du bloc sur l'axe horizontal |
| *y*                     | Coordonnée du bloc sur l'axe vertical   |
| *z*                     | Layer                                   |
| [*HexColor*](#hexcolor) | Couleur du bloc au format Hexadécimal   |
| [*PhysID*](#physid)     | Type de collision et évènement          |

## ID

| N°  | Description |
| --- | ----------- |
| 1   | Player      |
| 2   | Bloc Carré  |

## HexColor

**[HexCode](https://html-color-codes.info/Codes-couleur-HTML/) + Alpha en RGBA**

## PhysID

| N°  | Description        |
| --- | ------------------ |
| 1   | Pas de collision   |
| 2   | Arrêt              |
| 3   | Annulation du tour |
| 4   | Rebond             |
