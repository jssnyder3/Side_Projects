# Comparing Drum Rhythms as Vectors

Lately I've been toying around with the idea of comparing drum styles mathematically. For example, I've been considering whether we can mathematically calculate how Ringo Starr's drumming with the Beatles changed over the course of the 1960's. How does my own drumming style compare to those of my influences? How does my style change between different projects I play in?

Of course, I can qualitatively answer these questions, but it would be much more fun to throw some quantitative element into the mix.

This is a first step in doing so.

As a drummer, I typically learn challenging rhythms by inputting the them into a drum machine and then playing them back, allowing me to both see and hear the rhythm and then translate that into physical movements with my hands and feet. The interface for my drum machine is a grid, with each column serving as a subdivision of time and each row serving as a different sound (kick, snare, hihat, cymbal, etc.). I realized that this grid, in its simplest form, looks very much like a matrix with 1's where a sound is activated (drum is hit) or 0 where there is a rest (or no action). Once these patterns are in matrix form, we can measure similarity between patterns by calculating the distances between them.

This assortment of workbooks is an initial attempt to test the approach of calculating the similarity (i.e. Euclidean distance) between drum patterns mathematically, initially using simple one-instrument patterns as a test case and then growing the approach to assessing multi-layered patterns and additional complexities of rhythms.

Notebooks fall in the following order:

- 1_Afro Cuban Bell Patterns
- 2_Multi-Instrumental_Patterns
- 3_Ghost_Notes

This is a work in progress, so I welcome any feedback, ideas, criticisms, etc.! A few next steps I'm considering are towards the end of the Jupyter notebook.
