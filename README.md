## GraphicsProject

### Working features:

#### Ambient
Format: ambient x y z

Description: sets ambient light to [x, y, z]

#### Constants

#### Multiple lights
light a b c x y z 
 
Description: adds[[a, b, c], [x, y, z]] to array of lights. Image begins with no extra lights

#### Changing light in animation:
Format:

light name a b c d e f g

light name2 a b c d e f g

ex:

light faraday 0 0 0 .5 .75 0

light faraday2 0 255 255 .5 .75 0

Description: Light starts as name and changes color and position in each frame until it becomes name2 at the end of the animation

Note: can only be used if there already is an animation going on. Doesn't work if light is the only thing moving

####Mesh
mesh [glowy] :filename

glowy is optional (hence the brackets). If used the lines connecting the vertices will have the neon effect also used in line. Otherwise they will be normal lines. Mesh only uses vertices and faces, but the faces can have any number of vertices greater than 2.

####Line
Line now has a neon effect because why not.
