Rust eL Ti eL: LTL
Embedding Lua, TCL and Lisp into Rust because why not?

[![Rusty LJLT and libeljlt](https://github.com/jnbek/rust-eltiel-poc/actions/workflows/ci.yml/badge.svg)](https://github.com/jnbek/rust-eltiel-poc/actions/workflows/ci.yml)

We'll see how far this goes, since I don't like to start what I finish...

Proof of Concept:
    Testing various embedding of scripting languages within Rust programs.
    Targeting smaller languages such as Lisp and TCL as well as Lua because why the heck not.

Purpose:
    Proof of Concept embedding of scripting languages into a Full Stack Web Application
    Use cases:
        Scripting Queries to Web Application data via a REPL environment. (MW?)
        Scripting complex logic scenarios for the purpose of Data Model construction/configuration/etc
        Scripting custom scenarios and graphics

Additional Information:
    Application will be Weather and Climate Data Centric
    Requirements include:
        Mapping / Visualization
        GIS Data and Terrain
        GRIB2 and NetCDF Processing
        3D More

Beware of Feature Creepin' Tho...
    It's tempting to try and stuff and much here as possible and I'm sure we'll over do it, but hey
    Let's at least tell ourselves about it now, so we can justify it later when we're knee deep in
    Technical Debit and recriminations and all the things associated with that. :)
    
What this will not include:
    The primary focus will be on embedding smaller languages such as TCL, Lisp and Lua which have been 
    designed with the idea of being embedded to begin with. Support for languages such as Python, Perl,
    etc will be beyond the scope of this exploration. Greater focus will be given to Lua and LuaJIT but
    the APIs should remain consistent among each of the supported languages.

More Info:
https://crates.io/crates/mlua
https://crates.io/crates/molt-ng
https://crates.io/crates/rust_lisp
https://crates.io/crates/jlrs
