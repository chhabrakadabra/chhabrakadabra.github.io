---
layout: single
title: The strange relationship between water and WiFi
excerpt: How the development of WiFi technology was influenced by water
header:
  image: /assets/images/water_wifi.jpg
  image_description: Laptop on the beach
---

The strange relationship between water and WiFi showcases the weird ways technology evolves.
Sometimes it's tempting to think that technological decisions are the product of very smart people
thinking very hard about what the best way to do something is. While that may be true some of the
times, things often just fall into place based on weird circumstances.

Allow me to start with a weird phenomenon: in the early days of WiFi, your WiFi speed would drop
dramatically when you were using the Microwave. See [this article from
2012](https://www.abc.net.au/science/articles/2012/09/25/3595484.htm#:~:text=Getting%20back%20to%20why%20microwave,than%20a%20WiFi%20access%20point.&text=By%20the%20way%2C%20many%20other,is%20what%20WiFi%20networks%20use.)
and [this one from
2014](https://gizmodo.com/why-does-your-microwave-oven-mess-with-the-wi-fi-connec-1666117933) for a
reminder our past woes. These days that doesn't really happen. What's going on here?

# Now we're not cooking with fire

It's been a hot minute since people figured out that they can [cook food using radio
waves](https://en.wikipedia.org/wiki/Microwave_oven#Early_developments). There was a lot of messing
around with the frequency of radio waves best suited to cook food from the 1930s to the 1940s.
Eventually the world found the right balance of cost and effectiveness and we settled around 2.4GHz.
Does that sound familiar? It's one of the frequencies used by WiFi[^1]. Coincidence?

In 1947 at the International Telecommunications Conference at Atlantic City, it was decided to
create what are called the [ISM bands](https://en.wikipedia.org/wiki/ISM_radio_band#History). These
are portions of the radio spectrum dedicated for "industrial, scientific and medical" (ISM)
purposes. That's basically the world saying that there are specific frequencies in the radio
spectrum that should not be used by the telecommunications industry since there are other uses
already. In this band was the 2.4GHz band. Here's a section from one of the reports that's relevant:

> The delegate of the United States, referring to his request that the frequency 2450 Mc/s be
> allocated for I.S.M., indicated that there was in existence in the United States, and working on
> this frequency a diathermy machine and an electronic cooker, and that the latter might eventually
> be installed in transatlantic ships and airplanes. There was therefore some point in attempting to
> reach world agreement on this subject.

The "electronic cooker" from that section is referring to Microwave ovens. These generally flood
your food (or whatever else you put in them) with radio waves in the 2.4GHz band, which does a
pretty good job of heating the water in your food. You can see how any telecommunications devices
attempting to use the same frequency for precise signals around a microwave over would not do well.
It's like trying to tell your friend an incredibly specific sequence of numbers while heavy-metal
music plays at the highest-possible volume. So why does WiFi bother with that frequency?

# Nerds gotta nerd out

It turns out that the 2.4-2.5GHz frequency band was also licensed to amateurs. The big corporations
aren't going to bother with this, so why not let the nerds have fun with it?

And that's basically why both WiFi and Bluetooth started off with that frequency[^2]. Nothing to do
with whether 2.4GHz is best suited for the short-range communication. Everything to do with it being
best suited for boiling water. Not a result of smart people thinking really hard about the best way
to solve a problem. Just weird circumstance.

[^1]: It's the frequency WiFi started off at.
[^2]: Over the years as WiFi has become more popular, it's been shifted to the 5GHz band. Bluetooth
      on the other hand still uses 2.4GHz.
