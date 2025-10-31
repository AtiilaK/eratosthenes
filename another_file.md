---
title: My PDF
exports:
  - format: pdf
    output: exports/my-document.pdf
---

# Another file

This is a link in Markdown: [Cockett, 2022](https://doi.org/10.5281/zenodo.6476040).

I am citing [this paper](https://doi.org/10.1371/journal.pcbi.1002802) from last week.
:::{figure}
:label: my-figure
:align: left

(my-figure-fruit)=
![Here is some fruit 🍏](https://github.com/rowanc1/pics/blob/main/apples-wide.png?raw=true)

![My vacation pics! 🏝](https://github.com/rowanc1/pics/blob/main/ocean-wide.png?raw=true)

Some pictures of fruit and the ocean!
:::

See [](#my-figure-fruit) for the fruit, and [](#my-figure) to reference both subfigures.

```{figure} https://www.google.com/imgres?q=circle%20of%20fifths&imgurl=https%3A%2F%2Fwww.musikalessons.com%2Fblog%2Fwp-content%2Fuploads%2F2017%2F07%2Ffifths.png&imgrefurl=https%3A%2F%2Fwww.musikalessons.com%2Fblog%2F2017%2F08%2Fcircle-of-fifths%2F&docid=Np6p4gQPz31VDM&tbnid=9CjOBdmGWui4QM&vet=12ahUKEwjF6OqGrc-QAxWxPDQIHV_EKHAQM3oECHAQAA..i&w=838&h=643&hcb=2&ved=2ahUKEwjF6OqGrc-QAxWxPDQIHV_EKHAQM3oECHAQAA
:label: myFigure
:alt: Circle of Fifths
:align: center

Circle of Fifths 😎
```
 The image [](#myFigure) is from the internet

 ```{math}
:label: my-equation
w_{t+1} = (1 + r_{t+1}) s(w_t) + y_{t+1}
```

See [](#my-equation) for more information!
