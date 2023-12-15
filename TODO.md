# Disclaimer
All projects that start with `dev`
are under active development.

This project is in development meaning
it does not produce expected results.

# Problem
Cant find toolchain.

# Error
Error running analysis for `root//:cli (prelude//platforms:default#524f8da68ea2a374)`

Caused by:
    0: Error looking up configured node root//:cli (prelude//platforms:default#524f8da68ea2a374)
    1: Error looking up configured node toolchains//:rust (prelude//platforms:default#524f8da68ea2a374) (prelude//platforms:default#524f8da68ea2a374)
    2: Error looking up configured node prelude//rust/tools:transitive_dependency_symlinks (prelude//platforms:default#524f8da68ea2a374)
    3: Error looking up configured node toolchains//:python_bootstrap (prelude//platforms:default#524f8da68ea2a374) (prelude//platforms:default#524f8da68ea2a374)
    4: looking up unconfigured target node `toolchains//:python_bootstrap`
    5: Unknown target `python_bootstrap` from package `toolchains//`.
       Did you mean one of the 1 targets in toolchains//:BUCK?

# Possible solutions
Change config.