# Genetic Algorithm
**Random Search vs Genetic Algorithm**

Author: Michael Trossbach

Contact: mptrossbach@gmail.com

## Overview
Python implementation of genetic algorithm example taken from:

<a href="http://www.youtube.com/watch?feature=player_embedded&v=nrKjSeoc7fc">
  <img
    src="http://img.youtube.com/vi/nrKjSeoc7fc/0.jpg"
    alt="Genetic Algorithm: Shakespeare Monkey Example" border="5"
  />
</a>
<br><br>
I have included a random search example to use as a comparison to the genetic algorithm performance.

## Results
Of the two search types, the one that is most performant depends on the length of the target string. As the target string increases in length, the genetic algorithm tends to win and vice versa.

### Average search times (in seconds) after 5 trials

Target Sequence | Random Search | Genetic Algorithm
--- | --- | ---
`"hello"` | 0.00 | 0.98
`"hello world"` | 32.59 | 9.80
