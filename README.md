# Deep Keyword Recognition on Edge

This Projects goal is to entail the whole pipeline of bringing a keyword recognition model on microcontrollers. It should serve as a proof-of-concept, showing all necessary steps while highlighting some of the problems that will arise on the way. It will be structured in multiple jupyter-notebooks, each grappling a different aspect of the whole picture.

Purpose of this work is to deepen my own understanding on the speech recognition domain and to tie together knowledge that is available on different websites and blogs.

# Why on Edge?

## What is meant by Edge?

As Edge (-hardware) we understand hardware with limited resources, like microcontrollers. A prominent application field is the Internet of Things (IoT), but really all decentrialized on-device computing can be called edge-computing as long as the device itself doesn't offer alot of resources and data isn't send to a central server. A Raspberry pi for example could still go as Edge, but in my opinion it's already to powerfull to fit into real "Edge". Especially in regard to machine learning, current state of the art Edge-applications rather include tensor processing units like Google Corals TPU.

## Why is it interesting for Speech?

Alexa, Siri, Cortana. Speech Assistants have already arrived and more importantly are accepted in every-day life for many of us. One big concern lies in privacy: because speech is such a complex concept, the required processing power to effectivly answer queries is quite big. The actual processing is done in the cloud and thus, private data suddenly isn't that private anymore. Another concern is in the availability (or non-availability) of internet-connections. If we look at IoT, many fields deal with leaky net-cover.
Currently, the only thing that is recognized on-device are the so called wakewords, like "Hey Siri". These wakewords, or keywords, must be recognized confidently even in noisy environments, while the responsible software has very limited resources.
Even though keyword-only recognizers at first seem to have limited application areas, they are a necessary step on the road to full speech recognition systems in the Edge. Furthermore they not only serve as a gateway to more potent cloud implementations, but can lie pretty much everywhere where quick interactions with software is necessary, but physical interaction is impossible: in a surgery room, or nursing homes as interface to vital monitoring equipment, in cars or smart-homes.

### Challenge and Real Life Applicability

Machine Learning is steadily becoming easier as frameworks like tensorflow and pytorch refine their functionality. For a challenge, I wanted to give this project a little spin and see how converted models behave. Deployment and applicability to real life problems is another aspect that often poses problems, looking into a concrete usecase seems to be a good way to get some experience.


# Timeline

18.11.2020: Training, conversion and testing. A Notebook that focuses solely on the data and model.
24.11.2020: Improved descriptions.
07.12.2020: Small Restructuring
