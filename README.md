This is a collection of notebooks I've used while working on Super Mario 64 TAS.

They all rely on wafel: https://github.com/branpk/wafel

optimize_anyfunc.ipynb is for optimizing joystick positions within an interval of a TAS to minimize a given objective function.

resync_tas.ipynb attempts to take two TASes which reach a similar situation and have one mimic the other from there on out (which should make it easier to e.g. resync in the presence of different RNG or tie the rest of a TAS if you beat an earlier part).

utils.ipynb has a variety of useful functions, many of which have to do with RNG manipulation. See the docstrings for details.

workspace.pynb is just my scratch pad and is littered with various miscellaneous things I've done.
