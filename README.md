# Docker: GStreamer

Docker image with GStreamer built from sources.

# create
  ```docker build -f Dockerfile_git -t gstreamer-git .```

# run 
  ```docker run -it gstreamer-git bash  ```
  
# version (with my current version)
  ```
gst-launch-1.0 --version
  gst-launch-1.0 version 1.17.0
  GStreamer 1.17.0 (GIT)
  Unknown package origin```
```

# License

MIT
