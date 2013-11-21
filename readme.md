# Hue Screen Color Grabber
This is a program that fetches the avarage color of a screen. Does not work with DirectX programs.

## What does it do?
The program takes makes a printscreen. Then it calculates the avarage color of the image and sends the color to the Philips Hue lights. 

## Usage
* Download `hue-screen.jar`
* Create a file `config.properties` (see example below)
* Run `hue-screen.jar`

```
username=yourusername
ip=192.168.0.100
refreshrate=1000
```

* `username` username that is authorized with your bridge
* `ip` ip address of your bridge
* `refreshrate` refresh rate in milliseconds. Every 1000 miliseconds should be fine.

## Contributing
This is my first Java application ever. I accept pull requests.