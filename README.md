# wiki-list-patterns
BSc project template on information extraction from structured lists

**Why**: Many different kinds of documents contain lists: they are a simple way of enumerating several related items, and allow readers to look up and compare items. Often, every item in the list has some kind of structure. For example, here’s a few of Keira Knightley's film roles:

- [The Hole](https://en.wikipedia.org/wiki/The_Hole_(2001_film)) (2001), Frances "Frankie" Almond Smith
- [Bend It Like Beckham](https://en.wikipedia.org/wiki/Bend_It_Like_Beckham) (2002), Juliette "Jules" Paxton – her break-out role
- [Pirates of the Caribbean: The Curse of the Black](https://en.wikipedia.org/wiki/Pirates_of_the_Caribbean:_The_Curse_of_the_Black_Pearl) Pearl (2003), Elizabeth Swann

Each item contains different parts: the title of a film, year, the character she played and sometimes a comment. These parts are delineated by punctuation, but also often specific words or phrases. It would be nice to be able to extract information from these kinds of structures to add to Knowledge Bases, so we could automatically integrate it with other data.

**What**: This project aims to develop a system to automatically infer patterns in the structure of lists on Wikipedia. 

**How**: The starting point of this project is a collection of thousands of lists from Wikipedia. These lists contain links to Wikipedia pages, and therefore you could use background knowledge from Knowledge Graphs that are linked to Wikipedia pages.
You will evaluate and compare several approaches against an existing [Python library](https://github.com/turicas/templater/).

**Supervisor**: Benno Kruit (b.b.kruit@vu.nl)

**See also**:

- [Entity Extraction from Wikipedia List Pages](https://arxiv.org/pdf/2003.05146.pdf) Nicolas Heist, Heiko Paulheim - 17th Extended Semantic Web Conference (ESWC'20), Heraklion, Greece
