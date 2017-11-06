# Project Mosaic — an Architecture for the Front-end Microservices

Slides for a tech talk about Mosaic at [Idealo](https://www.idealo.de) Berlin.

## Abstract

Microservices allow multiple teams to work independently from each other, choose their own technology stacks and establish their own release cycles. Yet, the front-end development hasn’t fully capitalized on these benefits and the common practice for building websites remains “the monolith”: a single frontend codebase that consumes multiple APIs.

We will present how Zalando applied the idea of microservices to the front-end and solved arising challenges, including performance, maintainability, SEO and consistent UI. What is more, we will also talk in depth about two integral parts of Zalando’s architecture: Skipper — a routing solution, and Tailor — a layout composition service.

## Bio (Moritz Grauel)

[@mo_gr](https://twitter.com/mo_gr)

Moritz is a fullstack cat herder and anarchitect at Zalando. He shaves bike sheds and creates the most beautiful yaks at Zalandos Fashion Store team. Before he joined Zalando, he was living in the streets of Berlin, fighting bad code in the frontend and battling convoluted systems on the servers. During the last months, he became most famous for his ridiculous red moustache. Some say, it starts to slightly tremble in the presence of bugs or uncontrolled side-effects. Moritz declines to comment on this.

## Building the slides

`elm make Main.elm --output assets/elm.js --yes && open index.html`
