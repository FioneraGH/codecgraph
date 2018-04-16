# codecgraph

## Brief

A HDA codec graph generator from [helllabs](http://helllabs.org/codecgraph/) which has not been updated for long time.

Codecgraph is a tool to generate a graph based on the ALSA description of a High Definition Audio codec. The generated graph depicts the HDA codec layout and node connections, helping driver troubleshooting and maintenance. Codecgraph's parser reads the codec description from `/proc/asound/card*/codec#0` and parsed data is sent to Graphviz for actual graph generation.

This is a retention project for saving an analyzed codec with .svg graph.

