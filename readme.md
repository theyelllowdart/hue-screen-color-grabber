# Hue Screen Color Grabber
This is a program that grabs the avarage color of a screen. Does not work with DirectX programs.

## What does it do?
The program takes a printscreen. Then it calculates the avarage color of the image. After that it sends the color to all the Philips Hue lights. 

## Usage
* Download and extract `hue-screen.zip`
* Create a file named `config.properties` (see example below)
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