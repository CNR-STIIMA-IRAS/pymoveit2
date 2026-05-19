```bash
echo "deb [trusted=yes] https://raw.githubusercontent.com/CNR-STIIMA-IRAS/pymoveit2/noble-jazzy-amd64/ ./" | sudo tee /etc/apt/sources.list.d/CNR-STIIMA-IRAS_pymoveit2-noble-jazzy-amd64.list
echo "yaml https://github.com/CNR-STIIMA-IRAS/pymoveit2/raw/noble-jazzy-amd64/local.yaml jazzy" | sudo tee /etc/ros/rosdep/sources.list.d/1-CNR-STIIMA-IRAS_pymoveit2-noble-jazzy-amd64.list
```
