#Protractor Docker image
Allows headless protractor testing for CI environments

Use as builder image for Drone CI .drone.yml

Add a command like `xvfb-run --server-args='-screen 0 1280x1024x24' npm run protractor`
