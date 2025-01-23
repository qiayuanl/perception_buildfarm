```bash
echo "deb [trusted=yes] https://github.com/qiayuanl/perception_buildfarm/raw/jammy-humble-amd64/ ./" | sudo tee /etc/apt/sources.list.d/qiayuanl_perception_buildfarm.list
echo "yaml https://github.com/qiayuanl/perception_buildfarm/raw/jammy-humble-amd64/local.yaml humble" | sudo tee /etc/ros/rosdep/sources.list.d/1-qiayuanl_perception_buildfarm.list
```
