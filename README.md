```bash
echo "deb [trusted=yes] https://raw.githubusercontent.com/jspricke/pure_pursuit/focal-noetic/ ./" | sudo tee /etc/apt/sources.list.d/jspricke_pure_pursuit.list
echo "yaml https://raw.githubusercontent.com/jspricke/pure_pursuit/focal-noetic/local.yaml noetic" | sudo tee /etc/ros/rosdep/sources.list.d/1-jspricke_pure_pursuit.list
```
