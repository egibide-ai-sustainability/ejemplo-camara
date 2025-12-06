# ejemplo-camara

## Prerrequisitos

Instalar Poetry:

```
sudo apt install python3-poetry
```

## Puesta en marcha

Instalar las dependencias:

```
poetry config virtualenvs.options.system-site-packages true

poetry install
```

Probar la camara:

```
poetry run python3 camera-test.py
```

## Referencias

- [How to Use Raspberry Pi Camera for Machine Learning with OpenCV and Picamera2](https://protonestiot.medium.com/how-to-use-raspberry-pi-camera-for-machine-learning-with-opencv-and-picamera2-ecc663407afe)
