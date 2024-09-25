OCP Training 2024 (seoncd try)

## World Picker
to run the word-picker API on your local machine:
...
cd word-picker
export FLASK=APP=./word-picker.py
flask run
...

to build the docker image
...
cd word-picker
podman -t . word-picker:latest