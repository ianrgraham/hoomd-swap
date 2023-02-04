# hoomd-swap (WIP)

SWAP Monte Carlo integrator for __discrete-disperity__ (no polydisperse) systems. In practice, this integration method may be applied to any MD potential (isotropic or anisotropic pair) found in HOOMD or plugins, but in practice the tri-disperse LJ model is the only one (that I'm aware of) which has a non-zero success rate for SWAP moves.