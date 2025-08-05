# Prolog interface for FireBird

This is a Prolog pack that rovides library, a binding to FireBird

## Installation

The installation requires a recent C++ compiler.

    ?- pack_install(FBlog).

Should do the trick. Note that this clones FireBird and builds it the way
we need the library. This requires   significant  disk space (1.4Gb) and
takes long (several minutes on a modern machine).

### Manual installation

If the above fails

  - Clone this prepository in the `pack` directory of your installation
    or clone it elsewhere and link it.
  - Run `?- pack_rebuild(FBlog).` to rebuild it.  On failure, adjust
    `Makefile` to suit your installation and re-run the pack_rebuild/1
    command.
