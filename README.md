# juce-bash-helper
Useful commands to install &amp; use JUCE

### JUCE set up instructions for ubuntu 16.04 LTS / elementary OS 0.4
### Here's all commands to install all dependencies to compile JUCE project (tested with compilation Audio Plugin in CLion)
```
sudo apt -y --force-yes install llvm clang libfreetype6-dev libx11-dev libxinerama-dev libxrandr-dev libxcursor-dev mesa-common-dev libasound2-dev freeglut3-dev libxcomposite-dev libcurl4-gnutls-dev
sudo add-apt-repository ppa:webkit-team/ppa
sudo apt-get update
sudo apt-get install libwebkit2gtk-4.0-37 libwebkit2gtk-4.0-dev
```
