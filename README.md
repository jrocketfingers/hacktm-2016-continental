# SpeedFeed
An augmented geo-tagging racing challenge platform.

People on the project: @jrocketfingers, @slymaximus

#### Category: Robotics/Automotive

#### Table No. 6

# Inspiration
Ain't seen nothin like this yet

# What it does
Using vehicle dynamics data gathered from an OBD2 dongle, and continental's long range radar and a camera, we can figure out high scores on 0-100 runs in an area, top speeds in an area, and times on predefined routes (technically races).
Due to raw data provided by continental we could also figure out the congestion during the run, and grade the timed routes with a score depending on the congestion encountered (and hence the driver skill). As this wouldn't be widely available, it's a thing we'll play with during development but might not be considered as serious

# How it's built
It's not yet. But we're gonna be using a bunch of spatial db stuff as soon as we finish hacking the data over to the aggregation server. Basically instead of an OBD2 dongle and a smartphone app, right now we'll use a laptop and a mobile app, with laptop acting as an OBD2 data transciever.

# Challengers we ran into
A redundant C++ transceiver app due to the developmental nature of the equipment

# What we learned
