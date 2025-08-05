# DevBoard_F1C100s Rev1
F1C100s based Linux development board

## Note
Edit 2: 
Board enumerate over USB but randomly doesn't likely due to missing bulk capacitor on VBUS.

Edit 1:
I couldn't get this revision of the board to enumerate over USB. 
Even after fixing multiple issues on the board.
Issues:
- Wrong voltage on UVCC pin of F1C100s
- Missing pull-up on CS pin of Flash

## Schematic
![Schematic](./images/schematic.png)

## Layout
2 Layers 75x50 mm  
![Layout](./images/layout.png)

## Render
![Render](./images/render.png)
