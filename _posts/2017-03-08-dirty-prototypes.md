---
layout: post
title: '[Final] 3 Dirty Prototypes'
categories: [final]
state: wip
---
## What do Prototypes Prototype [^1]
![proto-proto](/sp17-ms2/assets/img/project_final/dirty_proto/what_proto_proto.jpg){: width='450px'}

> `Role prototypes` are those which are built primarily to investigate questions of *what an artifact could do for a user*.

> `Look and feel prototypes` are built primarily to explore and demonstrate options *for the concrete experience of an artifact*.

> `Implemetation prototypes` are built primarily *to answer technical questions* about how a future artifact might actually be made to work.

# Project Proposal
I suggest entertaining contents that are satisfying the five human senses with a tangible interface. The device is making visual, auditory, and tactile information. The animation to be screened on this device encourages the sense of taste and smell with its narrative.

+ How do we make immersive experience without blocking people’s sight?
+ How do we create empathy in mediated experiences?

# Prototype01: Role
![](/sp17-ms2/assets/img/project_final/dirty_proto/proto01.jpg)
![](/sp17-ms2/assets/img/project_final/dirty_proto/proto01_.jpg)

# Prototype02: Look and Feel
<br><br>
![](/sp17-ms2/assets/img/project_final/dirty_proto/proto02.jpg)
<br><br>

# Prototype03: Implementation
```
//pseudo code for 'project: Tangible'

loop{
	if(audience){
		play(intro);
		while(object_box){
			if(detect hand.both_side){
				tangible_mapping();
				screen(object_box);
			}
		}
	}else{
		play(sound attraction);
	}
}

tangible_mapping(){
	camera = on;
	object scannig in real time;
	make 3D.depth.map;
}
screen(box_input){
	anim = load_contents(box_input)
	animate(3D.depth.map, anim);
}
```

[^1]: Houde, Stephanie, and Charles Hill. "[What do Prototypes Prototype?](https://pdfs.semanticscholar.org/30bc/6125fab9d9b2d5854223aeea7900a218f149.pdf)."