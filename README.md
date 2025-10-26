# what is this project
Hi, im building a DIY night vision system built on the rasberry pi zero 2W. This project takes adavantage of the near infrared specturm and active illumniation for clear vision in low to no visable light settings.
really the main goal of this project is to learn and gain expeirnece working with rasberry's vision system and have fun :)

# applicable use
Night vision systems have many useses, in this case since I am focusing mainly on the electrical and computer side of this project,
so the hardware application will not be fully fleshed out. This system can be expanded upon and has many practical applications such as
security cameras, dashcams, night vision goggles, drones, etc.

# project goals & unique aspects
The main goal of this project is to create a closed spaced system that allows for a camera -> computer ecosystem
unique aspects:
  - isolation of NIR:
  many night vision systems take advantage of the full visable and near infared spectrum. While useful for mixed application where visable light
  occasonally occurs. This hinders the true 'night vision' capabilities as under conditions where select visable light is in frame
  (ie. car headlights, street lamp, flashlight) due to standard silicon based sensors quantum efficency, the visable light will wash out the frame,
  rendering video recordings rather useless. By taking advantage of a low pass optic filter, we can isolate only the near infared spectrum
  (850 - 1000 nm) to produce more consistant and better night vision results, even under conditions where visable light is selectivly present in the scene.

  - active illumination:
    this design goal is not unique to this vision system. It is primarly used in cheap night vision goggles. While effective,
    it is easily detectable by other night vision goggles that are sensitive to the IR spectrum. Since stealth is not a project goal, this is not
    a concern to me.

  - portability:
    While the mechanical design is not a primary focus in this project, I do want it to be portable and relativly compact
    to simulate practical use case in aformentioned applications of night vision systems.

  - live vision stream:
    I want to implement wireless streaming from pi --> computer.
