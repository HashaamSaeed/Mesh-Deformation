# Mesh-Deformation
Mesh deformation using PyTorch3D.

After choosing the control/anchor points the mesh can be deformed towards a target point outside in the world space.

ARAP (As-Rigid-As-Possible) cost used to favour isotropic deformation.

To optimise the cost functions we use gradient descent.
