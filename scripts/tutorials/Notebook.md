# Isaac Lab Notebook

## Container
 * python/python3 and pip/pip3 are set as the alias of isaac toolkit python and pip.
 * GUI would not direcly work in container with X11 forwarding, but work with option`--livestream {0,1,2}`. [ref](https://isaac-sim.github.io/IsaacLab/main/source/tutorials/00_sim/launch_app.html#understanding-the-output-of-help)
 * `LIVESTREAM=0` disables livestreaming.`LIVESTREAM=1` enables Isaac Native Livestream extension but has been DEPRECATED. `LIVESTREAM=2` enables WebRTC Livestream Extension, which can be useful for remote access or container. [ref](https://isaac-sim.github.io/IsaacLab/main/source/api/lab/isaaclab.app.html#environment-variables)
 * Override Env Var: [ref](https://isaac-sim.github.io/IsaacLab/main/source/api/lab/isaaclab.app.html#environment-variables)