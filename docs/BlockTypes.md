# Every block template
Every block template has:
- name - Name of the block
- solid - Defines if block has hitboxes
- type - Defines block type
- hitboxes - Hitboxes of block
- visible - Defines if block is renderable
# Block template Types
## Solid Block Template
Solid block has all faces on the sides, so its just a full cube, always has 6 faces,
each face has only texture parameter
## Custom Block Template
Custom block has custom faces templates,
### Each face template has parameters:
- Is outside face - defines if face is on the side of the block
- Is full face - defines if face is full square
- texture - texture id

