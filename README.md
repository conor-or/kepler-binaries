# Finding Planets in the Kepler EB Data

In this project we'll hunt for planets orbiting binary stars using the publicly available Kepler data. We've got the data for __50 eclipsing binary stars__. Some number of these binary stars are known to have planets: _it's up to you to find out which!_

Read the below to get started and follow any links to papers for more detail on certain parts.

### Binary Stars

About half of all stars exist in [_binary star systems_](https://en.wikipedia.org/wiki/Binary_star). These are systems where stars of a similar size and mass orbit very closely around a common centre of mass.

The formation and evolution of a binary system is very complicated and not really worth discussing here. The main thing to note is that planets are just as likely to form around these double stars as they are around single stars like our own

It's these types of planets (called _circumbinary planets_) that we'll be looking for.

The separation of the stars is so small that most of the time binary systems actually just look like a single point of light. There's no way to tell them apart from a single star, except:

### Eclipsing Binaries

If the orbital plane of the two stars is lined up with our line of sight then we'll see the binaries eclipse each other twice per orbit. When each star eclipses the other the light from the system will drop by a small amount.

Monitoring the light from a binary system over a long period of time and looking for eclipses allows us to study these sytems in great depth. 

### Light Curves and Phasing

![light curve](phased_curves/45.png)

The __light curve__ is the main way we'll be interacting with these binary systems. Above is an example light curve from one of the systems we'll be studying. This is simply the brightness of the whole system over time. However, the above light curve has been __phased__. 

Phasing is an important part of this process: the Kepler spacecraft took one data point for each star every 29.4 minutes and the binaries typically have orbital periods of 6 hours to 18 hours. If we know the orbital period to a high precision then we can fold the light curve over so that each orbit appears on top of the previous and we obtain a high resolution light curve for one orbit. This is called __phasing__.

In the above, the orbit starts at -0.5, the _primary eclipse_ occurs at 0.0 and the orbit finishes with the _secondary eclipse_ at 0.5.

