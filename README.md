# pclSequenceViewer
Tool to sequentially visualize a series of point cloud files

## Dependencies
Point Cloud Library: http://pointclouds.org/downloads/

## Install

```
cd build
cmake ..
make
sudo make install
```
## Example usage
This example reads pointclouds in PLY format from a given path.

```
cd [[installation_path]]
./bin/sequence_viewer_test [[path to the folder with the point cloud files]]

```
