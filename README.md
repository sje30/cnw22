# Workshop

This is the home page for the workshop to be held Friday November 10th 2023.


## Recording

No recording this year.


# Instructions


If you can spend 30 minutes downloading the material before the session, you should
be able to use the material during the session.

1. Download [Julia](https://julialang.org/downloads/)

2. Start Julia and then type:

```
using Pkg; Pkg.add("Pluto")
```

This will install the [Pluto](https://github.com/fonsp/Pluto.jl)
package.  This provides an elegant workbook interface.

3. Download the
   [notebook](https://raw.githubusercontent.com/sje30/cnw22/main/cnw22.jl)
   to your  hard disk.

Or you can do this within Julia by doing:

```
using Downloads
Downloads.download("https://raw.githubusercontent.com/sje30/cnw22/main/cnw22.jl", "cnw22.jl")
```

Make sure the file is called `cnw22.jl` rather than something like
`cnw22.jl.txt`.

4. Start Pluto notebook:

```
Pluto.run()
```

and then select the `cnw22.jl` notebook.  The first time I tried this,
it took about 20 minutes to load all the packages required, so please
be patient.


## Video

I have made a [youtube video](https://youtu.be/4vEhW1Piafs) of me
installing everything afresh on a Windows 11 laptop.  This was to
check that I have listed all the dependencies, and to see how long it
will take.  I suggest you follow along with the video.  There is a
long pause from about 6 minutes to 26 minutes when it is installing
and compiling all the extra packages.  This should happen only once,
unless you upgrade Julia.

## Static version of notes

A static version of the notes are [available](cnw22.html).
