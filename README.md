# Crystals and You

Crystals and You is a page where the user learns about crystals and how they can affect you in every day life. The page includes a directory of different crystals, each of which have a brief description about their properties. 

## Installation

For the backend:
```rails
rails db:migrate
rails db:seed
```
After the backend is running, run the frontend:
```rails
lite-server
```

## Usage

The User starts on the home page. Here, they have the option to click on one of three options in the navbar: 'Home', 'Crystals', and 'Grids'. Below this is a section which pulls a random crystal and displays it.

Upon clicking 'Home', the home page will load.

Upon clicking 'Crystals', the user is taken to a list of crystals. Below them is a line on text stating, "Choose a crystal to see its properties." Upon clicking on any of the crystals, the area below the list will now display the crystal, its picture, and a brief description of its properties.

Currently, the 'Grids' function is not available. I aim to have this fleshed out later on. The goal is to be able to choose a grid from a list, and be able to place different crystals on the grid. This will be able to tell the user how the grid layout will affect them, depending on which crystals they chose.

## License

Builder of the site: Jeremy Hart