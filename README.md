# Creating interactive presentations on Binder with RISE

[![Binder](https://mybinder.org/badge_logo.svg)](http://mybinder.org/v2/gh/fomightez/jupyter-rise_with-hide_code/master?filepath=index.ipynb)


-----

**TESTING ADDITION OF HIDE_CODE** See [here](https://github.com/damianavila/RISE/issues/32#issuecomment-493631621)


-----

RISE allows you to quickly generate a live, interactive presentation from a
Jupyter Notebook that is connected to the underlying Kernel of the notebook.
Using a new feature for automatically launching
the RISE plugin when a notebook is opened, RISE can be used to share interactive
presentations that run in the cloud with Binder.
This repository demonstrates how to accomplish this.

To make your RISE presentation automatically-launch with it is open,
add an `autolaunch=true` configuration
parameter to a notebook's `livereveal` section in the
metadata. E.g.:

```
...
"livereveal": {
        "autolaunch": true
        }
...
```

When the notebook is launched, your
presentation will automatically begin.

See the [RISE Documentation](https://damianavila.github.io/RISE/)
for more information.
