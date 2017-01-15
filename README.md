Intro
=====

Running Appium in Docker container


Run
===
```
export ANDROID_HOME="YOUR ANDROID HOME"(if not set)
export ANDROID_HOME=~/android
```
```
docker run -d --name appium -v $ANDROID_HOME:/android -p 4723:4723 muicoder/appium
```

Access
======
```
docker exec -it appium appium-doctor
```
