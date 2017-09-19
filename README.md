# Flow-Design Cheat Sheet
Writing clean code sounds as if you should write code in a certain way. That's certainly true. But what is also true is that writing code is only the last phase of a multi-step process called _software development_. How clean code is thus does not only depend on some coding techniques or pretty printing rules but starts much earlier. For us at the [Clean Code Developer School](http://ccd-school.de) it's firstly a matter of how you think about a solution what makes and keeps your code clean.

After first teaching "raw" [principles and practices of clean coding](http://clean-code-developer.com) in a pretty standard way we developed a more conceptual and more comprehensive method. This method we're calling _Flow-Design (FD)_ and it's an eclectic approach to software development inspired by many sources.

At the heart of FD is a visual notation to enable developers to express their mental models of how they think requirements could be met. This visual language is deliberately kept very simple. It should not require extensive studying or special tools to be used. It's for "quick and dirty" sketches on flipcharts and whiteboards to be used by single developers or small teams. Its primary use is _before_ code is written. It's a _design_ tool, not (!) a documentation tool.

When applied in day to day business common flow designs look like this:

![Exhibit 1](https://github.com/ccdschool/flow-design-cheatsheet/blob/master/images/real_world_examples/exhibit1.jpg)

![Exhibit 2](https://github.com/ccdschool/flow-design-cheatsheet/blob/master/images/real_world_examples/exhibit2.jpg)

![Exhibit 3](https://github.com/ccdschool/flow-design-cheatsheet/blob/master/images/real_world_examples/exhibit3.jpg)

Consider them "graphic recordings" of collective thought processes. As such they need not be readily understandable for an outside person. The primary purpose is to develop shared understanding of a solution among participants in a design session - and guide them during the actual coding.

This claim of course requires Flow-Design to be clear about the notational elements, how to use them in conjunction, and also how to translate them into code.

If you're interested if Flow-Design lives up to this claim, [check out the wiki of this repository](https://github.com/ccdschool/flow-design-cheatsheet/wiki). It provides a reference to the Flow-Design visual notation and how to derive real code from "bubbles".
