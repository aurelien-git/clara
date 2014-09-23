% clara(1)

# NAME

clara -  set of cluster administration tools

# SYNOPSIS

    clara <command> [<args>...]
    clara [--version]
    clara [--help]

# DESCRIPTION

clara is a set of cluster administration tools. The different tools are written as plugins that can be added or removed independently.

# OPTIONS

Clara provides the following plugins:

    repo	Creates, updates and synchronizes local Debian repositories.
    nodes	Manages and get the status from the nodes of a cluster.
    slurm	Performs tasks using SLURM's controller.
    images	Creates and updates the images of installation of a cluster.
    p2p		Makes torrent images and seeds them via BitTorrent.

# SEE ALSO

clara-images(1), clara-nodes(1), clara-p2p(1), clara-repo(1), clara-slurm(1)