# Jupyter-RISE served via Binder with hide_code extension

[![Binder](https://mybinder.org/badge_logo.svg)](http://mybinder.org/v2/gh/fomightez/jupyter-rise_with-hide_code/master?filepath=index.ipynb)

Click a `launch binder` badge anywhere on this page to begin.

-----

Note this builds on the [Binder example for the RISE plugin for presentations](https://github.com/binder-examples/jupyter-rise) to add the [hide_code extension](https://github.com/kirbs-/hide_code) as well. **No installation needed**. Using the `hide_code` menu, you can toggle hiding code prompts, code, or output, see [here](https://github.com/kirbs-/hide_code) and the designations are repsected in the Jupyter-RISE presentation.

-----

## About Jupyter-RISE

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

If you don't need the hide_code extension enabled along with Jupyter-RISE, you may be more interested in the [Binder example for the RISE plugin for presentations](https://github.com/binder-examples/jupyter-rise)


-----

## About the hide-code extension

hide_code is a Jupyter notebook extension to selectively hide code, prompts and outputs with PDF and HTML exporting support.

By combining with Jupyter-RISE, now using the `hide_code` menu, you can toggle hiding code prompts, code, or output, see [here](https://github.com/kirbs-/hide_code) and the designations are repsected in the Jupyter-RISE presentation mode.

---

## Technical notes:

Thhe `hide_code` extension was described as compatible with Jupyter-RISE [here](https://github.com/damianavila/RISE/issues/32#issuecomment-493631621). And Jupyter-RISE works via BINDER as can be seen via [the OFFICIAL Binder example for the RISE plugin for presentations](https://github.com/binder-examples/jupyter-rise). Although because it has some complex requirements, it was not that easy to add hide-code along with Binder and so it wasn't straighforward for those wishing to explore the use of Jupyter-RISE in conjunction with the `hide-code` extension. Now it is. Addition and enabling of the hide_code extension for Binder worked out [here](https://github.com/fomightez/jupyter_hide_code).

-----

[![Binder](https://mybinder.org/badge_logo.svg)](http://mybinder.org/v2/gh/fomightez/jupyter-rise_with-hide_code/master?filepath=index.ipynb)


