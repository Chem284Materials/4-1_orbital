# Visualizing an Atomic Orbital Using CUDA

In atomic units (i.e., distances of bohr), the wavefunction for a 3p orbital of the hydrogen atom is:

$$\psi_{3p}(r,\theta) = A cos(\theta) (6-r) * r * e^{-r/3}$$

where $A$ is a constant.
You can ignore this constant for the purpose of the rest of this problem.

Create an image depicting a 2D cross-section of this orbital, with a size of at least `512 x 512` pixels.
Evaluation of $\psi_{3p}$ must be done using CUDA on a GPU.
Depict positive regions of the wavefunction in blue and negative regions in red, with the intensity of blue/red corresponding to the magnitude of the wavefunction.
Ensure that your image is scaled in such a way that the key features of the orbital are visible, including all nodes.
