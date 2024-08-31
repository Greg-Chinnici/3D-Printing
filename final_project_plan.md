# Plan
## the process
- keyboard-layout-editor.com
  - current layout (kle): ```[{a:7,w:2},"Esc","F1","F2","F3","F4","F5",{x:2},"F6","F7","F8","F9","F10","F11","F12",{a:5},"PAUSE\nPRTSRC","INSERT\nSCRLK","DELETE\nNMLK"],
[{w:2},"~\n`","!\n1","@\n2","#\n3","$\n4","%\n5",{x:2},"^\n6","&\n7","*\n8","(\n9",")\n0","_\n-","+\n=",{a:7,w:2},"BACKSPACE","HOME"],
[{w:2},"TAB","Q","W","E","R","T",{x:2},"Y","U","I","O","P",{a:5},"{\n[","}\n]",{w:2},"|\n\\",{a:7},"PAGE UP"],
[{w:2},"CAPS LOCK","A","S","D","F","G",{x:2},"H","J","K","L",{a:5},":\n;","\"\n'",{a:7,w:3},"ENTER","PAGE DOWN"],
[{w:2},"SHIFT","Z","X","C","V","B",{x:2},"N","M",{a:5},"<\n,",">\n.","?\n/",{a:7,w:3},"SHIFT","↑",{a:6},"END"],
[{a:7,w:2},"CTRL",{w:1.25},"WIN",{w:3.75},"",{x:2,w:3.75},"","ALT","FN",{w:1.25},"CTRL","←","↓","→"]```

- https://kbplate.ai03.com/
  - makes a dxf from the kle file for Fusion360
    - the line are all separate, so you have to go over them a second time
    - still very useful tool nonetheless

- dont know how Im going to design or manufacture the pcb yet
  - 2 boards (one for each half). Do I need more?
  - can I work backwards from the plate design?
  - what is the differnce from Mill-Max vs Sockets
    - will it require a cherry layout anyway
  - how to add LEDs


## CAD notes
- Keyboard CAD dimensions for holes
  - https://null-src.com/posts/keyboard-design-cheatsheet/
- as of now the keys are 5.05mm x, and 5mm y. offset
- the CAD file will have offsets fot the pcb and case border
- bridge wire goes out of the north sides
  - magnets on the inside so it can be a regular ortho

- detachable ramps on the bottom for tilt
  - magnets inside the rubber feet
  - adjustable??

- pcb needs to be designed for Cherry MX hotswap holes

## Assembly notes
- how to add hotswap sockets to a board
  - [tutorial](https://www.youtube.com/watch?v=RB1Wm8y2Cw8)
  - [mx sockets](https://www.amazon.com/DUROCK-Mechanical-Keyboard-Switches-Hot-Swap/dp/B0B4W9YMGM/)

## Purchasing notes
- anything 2u and larger needs a stab. total stabs: 12 
  - 2u: backspace, backslash
  - 3u: enter, shift_R
  - 3.75u: space (2)
  - esc, tilde, tab, caps lock, shift_L, ctrl
    - i dont know if i want these 2u or 1.5u yet

- types of stabs
  - plate goes onto the grid (if no pcb)
  - screw in (best kind, but needs holes in pcb before)

# Compelete

- [ ] finish plate CAD
- [ ] finish pcb CAD
- [ ] finish keycaps CAD
- [ ] finish case CAD

- [ ] buy switches
- [ ] buy hotswap sockets
- [ ] print plate
- [ ] test fit switches with plate
- [ ] buy micro controllers
