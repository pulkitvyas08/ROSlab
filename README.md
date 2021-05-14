<p align="center">
  <h1 align="center">ROSlab</h3>

  <p align="center">
    ROS inside Colab
    <br />
    <br />
    <a href="https://github.com/pulkitvyas08/ROSlab">View Demo</a>
    ·
    <a href="https://github.com/pulkitvyas08/ROSlab/issues">Report Bug</a>
    ·
    <a href="https://github.com/pulkitvyas08/ROSlab/issues">Request Feature</a>
  </p>
</p>

</br>
<p align="center">
    <a href="https://colab.research.google.com/github/pulkitvyas08/ROSlab/blob/main/ROSlab.ipynb" target="_blank"><img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"></a>
<p>

&nbsp;

## Usage

1. Open the Notebook in Colab using the badge above
2. Make a copy of the notebook for your own use by `Files` --> `Save a copy ... (Either in Drive or GitHub)`
3. Run all the cells for installing ROS onto the notebook session
4. Execute ROS commands as:

    ```colab
        !~/roslab ...
    ```

&nbsp;

## Current Functionalities -

1. All features of ROS Melodic core library
2. Support for ROS client API libraries (rospy example given in the notebook)
3. Can use almost all regular Ubuntu features that ROS needs

&nbsp;

## Current Limitations -

1. No support for ROS GUI tools
2. No support for ROS visualization tools
3. Cannot use ROS programs that need interaction (for example turtlesim)
4. Cannot execute ROS nodes that need visual output
5. `roslab` has to be called by it's path
6. Installation has to be done on every use of the notebook
7. Colab cells are restrictive on their own. Using files would be a much better option
8. C++ support not available (never checked that either)
9. Status on hardware support unknown
10. Workspace state is not saved (the files, system-wide variables, etc)

&nbsp;

## How are things different from regular ROS in Ubuntu?

1. ROS has to sourced in every cell with ROS master setup. To avoid the trouble of adding some code in every cell those commands have been added to `roslab` and to execute any ROS command `~/roslab` has to be written before the command.
2. Most shell commands have to preceded with a `!` (for example `!ls`) with some commands like `cd` to be used as `%cd` i.e. with magic.

&nbsp;

## Roadmap -

Check out the [open issues] and [projects] for a list of proposed features (and known issues)

&nbsp;

## License

Distributed under MIT License. See `License` for more information.

[open issues]: https://github.com/pulkitvyas08/ROSlab/issues
[projects]: https://github.com/pulkitvyas08/ROSlab/projects
