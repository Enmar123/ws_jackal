
This repo contains files for simulating the jackal, it is not yet set up to run the physical robot.

When cloning this repo, do not forget to the following command so that you get the actuall code and
not just references to other repos. 

  * git clone --recurse-submodules -j8 <this-git-repo>

Before editing submodules don't forget to checkout the branch of interest so you can avoid detached
head state.

  * git checkout <branch-to-edit> 

To launch Jackal simulation

  * roslaunch jackal_gazebo jackal_world.launch config:=mapping world:=tunnel.world
