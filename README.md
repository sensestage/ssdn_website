This is the code for the webpage for the documentation of the Sense/Stage MiniBee.

The site can currently be found at: [https://www.sensestage.eu/documentation](https://www.sensestage.eu/documentation); this is a temporary location until the site has the most necessary content.

The site uses [LuaPress](https://github.com/Fizzadar/Luapress) to be build. Please mind [this issue](https://github.com/Fizzadar/Luapress/issues/17), when installing LuaPress.

I'm happy to get suggestions, fixes, updates, and so on for the website!


#sections plugin

The sections plugin works as follows:

- create a page where you call the sections plugin with ```$! sections !$```
- create a folder in the folder ```sections``` with the same name as the page
- in this folder you place all the pages that belong to the section. They will automatically be listed and linked on the main page of the section.