# Europe-SVG-Svelte
This repository contains a svelte component with a SVG map of europe. Each country can be colored differently.

## Getting started
Download the components SVGEurope.svelte and PathInteractive.svelte and include them to your SvelteKit project. 
PathInteractive wraps the <path> tag and adds a listener object to it. SVGEurope contains all paths of the countries and 
passes the listener object to components that use SVGEUrope. The listener object can be used to implement the onmouseenter, onmouseleave, onclick and onkeydown actions.  

The Europe.ts defines an object that contains each country of europe with a unique key, id, color, the english name and the german name of the country. 
