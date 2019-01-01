# BIM workbench for FreeCAD

![](https://www.freecadweb.org/wiki/images/5/5e/BIM_workbench_presentation.png)

This is a [workbench](https://www.freecadweb.org/wiki/Workbench_Concept) for [FreeCAD](https://www.freecadweb.org) that implements a complete set of [Building Information Modeling](https://en.wikipedia.org/wiki/Building_information_modeling) (BIM) tools and allows a proper BIM workflow similar to professional BIM applications like Revit, ArchiCAD, Tekla, AllPlan or BricsCAD.

FreeCAD is an open-source generic, parametric 3D modeling application. The BIM workbench, rather than trying to be a all-in-one, independent application and mimic the above applications, integrates into all layers of FreeCAD and allows you to use all the other moldeling and analysis tools of FreeCAD for BIM purposes too. In fact, if you know FreeCAD well already, you can do BIM without the BIM workbench, and only use it at the very end to format your model for BIM.

But one of the specific goals of this particular workbench, is to try to focus on user experience. FreeCAD is a powerful application, but has a rather steep learning curve. In the BIM workbench, we try to ease that curve somehow.

**Warning**: This is experimental work. Although it is perfectly safe to use, and won't break anything, it is meant to be an place where we can try things and experiment, and not a production environment (yet). You are more than welcome to try, give us your feedback and help us to build a better BIM workflow, just remember that some features might change or disappear without notice over time.

### Features

This is a rather short overview of what it can do, just to give you a taste of it. There is much more than that, refer to the  [full documentation](https://github.com/yorikvanhavre/BIM_Workbench/wiki) to know more.

* 2D drawing tools (all the usual ones like lines, arcs, polylines, rectangles, etc...) plus pretty powerful, complex, constrainable [sketches](https://www.freecadweb.org/wiki/Sketcher_Module) with common drafting aid environment such as snapping, working planes, etc.
* Generic 3D objects such as extrusions, unions, subtractions, intersections (all usable as BIM components)
* Architectural BIM objects (the usual ones like walls, windows, stairs, etc...)
* Structural BIM objects (columns, beams, slabs, metallic profiles, etc...) with built-in wire representation
* Basic tools for MEP/piping BIM work such as pipes, and already a few MEP objects in the [library](https://github.com/FreeCAD/FreeCAD-library). We need help to model more parametric components, though!
* Many ways to structure and organize your models, with no predefine structure (you organize your model the same way as you organize files and folders on your computer, you decide)
* Very good support of the [IFC](https://en.wikipedia.org/w/index.php?title=Industry_Foundation_Classes) file format, which allows you to export and import models from/to other BIM applications
* Producing 2D output (printable sheets) from your BIM models is already possible, but still not fully optimized for large models like BIM models more than often are, and is still a bit tedious (we're working on it!). However, exporting 2D views such as plans and sections to be reworked further in 2D drafting applications that support SVG, DXF or DWG files (all of which can be easily exported form FreeCAD BIM models) works very well and is a good workaround for the time being.

### Installing

1. Install FreeCAD (grab a package for your operating system from https://github.com/FreeCAD/FreeCAD/releases or simply search for "FreeCAD" in your package manager on most linux distributions)
2. Launch FreeCAD and start the Addons Manager from menu Tools -> Addons manager
3. Locate and install the BIM addon
4. Restart FreeCAD, and switch to the BIM workbench

### Learning

On starting the BIM workbench for the first time, you will be presented a welcome screen which will guide you further

The BIM workbench documentation is hosted on the FreeCAD wiki, at https://www.freecadweb.org/wiki/BIM_Workbench

If you would like to get a better knowledge of FreeCAD as a whole, which I highly recommend, start with the [FreeCAD manual](https://www.freecadweb.org/wiki/Manual:Introduction). We are working on making the FreeCAD wiki a more comfortable place to read, in the meantime the manual is also hosted in a more readable way on [GitBook](https://legacy.gitbook.com/book/yorikvanhavre/a-freecad-manual/details) (offline versions like ebook or pdf are also available there).

The BIM workbench also features a built-in tutorial (in development) located under menu Help-> BIM tutorial

### Development

The development reports I write monthly are available at https://github.com/yorikvanhavre/BIM_Workbench/wiki, if you want to be kept informed about the developments of this workbench, follow me on [Twitter](https://twitter.com/yorikvanhavre), [Facebook](https://www.facebook.com/yorikvanhavre), [Mastodon](https://mastodon.social/@yorik), [Patreon](https://www.patreon.com/yorikvanhavre), or follow my [blog](https://yorik.uncreated.net/guestblog.php).

You can help the development of this workbench by sponsoring me on [Patreon](https://www.patreon.com/yorikvanhavre) or [LiberaPay](https://liberapay.com/yorik). All the development is fuly open-source, everything I produce is available to everybody, there is no content "for subscribers only", only an increasing portion of my working hours each month is paid by this sponsoring.
