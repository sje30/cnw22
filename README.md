# Workshop

This is the home page for the workshop to be held Wed 9th November 2-4pm.

We will meet on Teams.  Further details TBC.  (Spoiler alert: Julia
code to follow here.  If you are able to install
[Julia](https://julialang.org/downloads/) then you should be able to
follow along, although not necessary.


## Recording

The session will be recorded, and we assume that if you have your
camera or microphone on, then you consent to being recorded.  If you
wish to revoke your consent, please contact us and we will need to
edit you out of the recording.



# Instructions

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

I have made a recording of me installing everything afresh on a
Windows 11 laptop.  This was to check that I have listed all the
dependencies, and to see how long it will take.  I suggest you follow
along with the video.  There is a long pause from about 6 minutes to
26 minutes when it is installing and compiling all the extra packages.
This should happen only once, unless you upgrade Julia.
