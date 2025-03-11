# Block types
## Every block 
Every block has:
- name - Name of the block
- solid - Defines if block has hitboxes
- hitboxes - Hitboxes of block
- visible - Defines if block is renderable
## Solid Block
Solid block has all faces on the sides, so its just a full cube, always has 6 faces,
each face has only texture parameter
## Custom Block
Custom block has custom faces,
Each face has parameters:
- Is outside face - defines if face is on the side of the block
- Is full face - defines if face is full square
- texture - texture id

