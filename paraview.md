# Paraview

## Windows

1. Navigate to the [ParaView download page](https://www.paraview.org/download/).
2. Download `ParaView-5.10.1-Windows-Python3.9msvc2017-AMD64.exe` (you do not want the one with MPI in the title)
3. Run the downloaded installer
4. Enable the topology toolkit (see below)

## macOS

1. Navigate to the [ParaView download page](https://www.paraview.org/download/).
2. Download one of the ParaView packages, probably one of the signed ones
3. Run the downloaded installer
4. Enable the topology toolkit (see below)

## Linux

I recommend not installing this from your package manager, many have out of date versions or versions without the topology toolkit plugin we are going to use. Instead:
1. Download the tar archive from the [ParaView download page](https://www.paraview.org/download/).
2. Extract the archive `tar -xzf "ParaView-5.10.1-MPI-Linux-Python3.9-x86_64.tar.gz"`
3. Rename the folder to something a bit easier to work with `mv "ParaView-5.10.1-MPI-Linux-Python3.9-x86_64" ParaView`
4. You can now run paraview: `./ParaView/bin/paraview`

Alternatively just run this in your shell:

```
curl "https://www.paraview.org/paraview-downloads/download.php?submit=Download&version=v5.10&type=binary&os=Linux&downloadFile=ParaView-5.10.1-MPI-Linux-Python3.9-x86_64.tar.gz" | tar -xz && mv "ParaView-5.10.1-MPI-Linux-Python3.9-x86_64" ParaView
```

Enable the topology toolkit (see below)

## Topology toolkit

Once paraview is installed we need to enable the topology toolkit. This is done by:
1. Navigating to `Tools`
2. Navigate to `Manage Plugins...`
3. Click on `TopologyToolKit`
4. Check the autoload tick-box
