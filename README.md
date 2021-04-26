# Space Dog

This frontend css was design initially for my personal use, and to speed my coding wile I  was learning. This also helped me to learn on how to became a better web developer and to put in practice all that I was learning.

The initial use was think to have zero to low JS, but as things got bigger and i became a better developer i add just enough JS to keep things small, fast and modular.



## Methodology  applied on the construction

### Architecture

> Before I talk about this you must know that this frontend use Sass to keep everything organize.

For the folders structural architecture  I'm using the strategy of 7-1 pattern, with means:

- 7 different folders for partial Sass files
  
  - base/
  
  - components/
  
  - layouts/
  
  - pages/
  
  - themes/
  
  - abstracts/
  
  - vendors/

- 1 main sass file to import all others files into a compiled CSS stylesheet
  
  - space-dog.scss

This structure was think to make the framework really scalable.

## Colors

Wen I was starting to learn code and all about a great design the use of colors was always a huge deal, so to make things easy I create a hole mixing with a FlatUI design colors and a tone of grey for the main text color with i change depending on the project. The colors are:

- TURQUOISE

```sass
$colorTurquoise: #1abc9c;
```

- EMERALD

```sass
$colorEmerald: #2ecc71;
```

- PETER RIVER

```sass
$colorPeterRiver: #3498db;
```

- AMETHYST

```sass
$colorAmethyst: #9b59b6;
```

- WET ASPHALT

```sass
$colorWetAsphalt: #34495e;
```

- GREEN SEA

```sass
$colorGreenSea: #16a085;
```

- NEPHRITIS

```sass
$colorNephritis: #27ae60;
```

- BELIZE HOLE

```sass
$colorBelizeHole: #2980b9;
```

- WISTERIA

```sass
$colorWisteria: #8e44ad;
```

- MIDNIGHT BLUE

```sass
$colorMidnightBlue: #2c3e50;
```

- SUN FLOWER

```sass
$colorSunFlower: #f1c40f;
```

- CARROT

```sass
$colorCarrot: #e67e22;
```

- ALIZARIN

```sass
$colorAlizarin: #e74c3c;
```

- CLOUDS - _with is my main white_

```sass
$colorCloud: #ecf0f1;
```

- CONCRETE

```sass
$colorConcrete: #95a5a6;
```

- ORANGE

```sass
$colorOrange: #f39c12;
```

- PUMPKIN

```sass
$colorPumpkin: #d35400;
```

- POMEGRANATE

```sass
$colorPromegranate:#c0392b;
```

- SILVER

```sass
$colorSilver: #bdc3c7;
```

- ASBESTOS

```sass
$colorAsbestos: #7f8c8d;
```

You can see the color reference bellow:

![](/home/fernando/Documents/Web%20development/space-dog/img/Flat%20UI%20Colors%20-%20Color%20Palettes.png)

## Grid system

There is no grid system since the recomendation is to use CSS Grid. Today all the major browser on desktop and on pc acept.

I have plans to create a 12 grid layout using flexbox.