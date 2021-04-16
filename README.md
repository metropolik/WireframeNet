# 3DMeshNet

The underlying representation of 3D reconstruction algorithms has a major impact on the quality, memory size and robustness the reconstruction can achieve. 

Goals:
1. DNN which generates a triangle topology / wireframe from a depth image
2. DNN which can merge/extend a already existing triangular scene mesh with new information from RGBD images (novel)
3. DNN which can merge meshes to become manifolds (novel)
4. DNN which can fill in holes or complete parts of the scene directly on the triangle mesh. (like https://github.com/angeladai/sgnn but based on triangles)
