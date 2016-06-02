---
layout: page
title: Demos
excerpt: "Open Adaptive Music Library."
---

- msnake: [https://github.com/oamldev/msnake_oaml.git](https://github.com/oamldev/msnake_oaml.git)

Based on Mogria's Snake [https://github.com/mogria/msnake.git](https://github.com/mogria/msnake.git).
This is a ncurses based snake game that I've adapted to use OAML, music in this game gets faster as the snake grows. The music is a simple 8bit theme that starts with 80bpm and goes up to 180bpm.
To build and run on Linux and OSX you can use this commands:

```
	git clone https://github.com/oamldev/msnake_oaml.git
	cd msnake_oaml
	cd build
	cmake ..
	make
	./msnake
```

- UnityOAMLdemo: [https://github.com/oamldev/UnityOAMLdemo.git](https://github.com/oamldev/UnityOAMLdemo.git)
This is a demo I've created using Unity, it's a very simple 2d platformer that implements adaptive music through OAML, it features two possible themes, one in 8bit style and another one in orchestral style, both have "day" and "night" music loops and a battle loop (which you can trigger "engaging" the spikes, I will add a proper enemy sometime in the future). 

- oamlGodotDemo:

[/demos/oamlGodotDemo](/demos/oamlGodotDemo)
