# GNP2TEX
---

``gnp2tex`` is a tool to convert gnuplot plots to LaTeX style. It works using
``luaTeX`` and ``pdflatex`` to transform a script written in gnuplot to a
pdf standalone file. The repository comes with a test files called ``test_plot.gn``.
You can reproduce that plot using ``gnp2tex`` by invoking,

```bash
bash gnp2tex test_plot.gn
```

---

## Usage:

1. If you wanted to execute ``gnp2tex`` as a command without invoking ``bash``, you
should grant it execute permission.
```bash
sudo chmod u+x gnp2tex
```

2. If you wanted to execute ``gnp2tex`` as a global command, then, after granting it
execute permission, then you should copy the script into a ``$PATH``-defined 
directory. For example, ``/usr/bin``.
```bash 
sudo cp gnp2tex /usr/bin
```
3. The instructions about how to run ``gnp2tex`` are available as a _help_ flag, 
```bash
gnp2tex -h
```
