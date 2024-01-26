# FLYBOY

The Minimal RC flight simulator

## Story

I've never flown an RC plane, but I just ordered one, and I needed a simulator to practice so I don't break the wing right away. 

None of the simulators I could find worked on my poor laptop, so I coded the FLYBOY.

Is it realistic? Probably not; I can't know because I haven't got my rc plane yet.

Can it be used to try out the feel of FPV flying? I think so, yes. 

Will it work on your computer? Try it! It's free and there's nothing to download or install. I can get ~55 fps on my crappy PC, and the fans don't scream all the time.

## Usage

Connect your RC controller via cable or Bluetooth to your computer, go to [flyboy.app](https://flyboy.app) in your browser (preferably Chrome), and start flying.

You can also test it with the WASD keys, but it works nicely with an XBOX controller, for example, if you don't have your proper radio yet. 

## Troubleshooting

Are you using Chrome (or Chromium) browser? They have the best optimised WebGL 3D accelerator.

Are you sure the hardware accelerator is turned on in Chrome? Browse to address `chrome://flags` and set

* Override software rendering list -> enalbled
* GPU rasterization -> enalbled
* Out of process rasterization -> enalbled

Then browse to `chrome://gpu` and make confirm that

* WebGL: Hardware accelerated
* WebGL2: Hardware accelerated

## Credits

The whole project is based on 

- the [THREE.js](https://github.com/mrdoob/three.js) by [mrdoob](https://github.com/mrdoob) (and contributors) 

- and the ["Sketchbook"](https://github.com/swift502/Sketchbook) game engine by [swift502](https://github.com/swift502) (and contributors).