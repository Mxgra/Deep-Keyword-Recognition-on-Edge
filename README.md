# Deep Keyword Recognition on Edge

This Projects goal is to entail the whole pipeline of bringing an keyword recognition model on microcontrollers. It should serve as a proof-of-concept, showing all necessary steps while highlighting some of the problems that will arise on the way. It will be structured in multiple jupyter-notebooks, each grappling a different aspect of the whole picture.

Purpose of this work is to deepen my own understanding on the speech recognition domain and to tie together knowledge that is available on different websites and blogs.

# Why on Edge?

## What is meant by Edge?

I understand Edge as hardware with limited resources, like microcontrollers. A Raspberry pi could still go as Edge, but strictly speaking it's already to powerfull. Especially in regard to machine learning, Edge rather includes tensor processing units like Google Corals TPU.

## Why is it interesting for Speech?

Alexa, Siri, Cortana. Speech Assistants have already arrived and more importantly are accepted in every-day life for many of us. One big concern lies in privacy: because speech is such a complex concept, the required processing power to effectivly answer queries is quite big. The actual processing is done in the cloud. The only thing that is recognized on-device are the so called wakewords, like "Hey Siri". These wakewords, or keywords, must be recognized confidently even in noisy environments, while the responsible software has very limited resources. Application areas are not only as a gateway to more potent cloud implementations, but can lie pretty much everywhere where quick interactions with software is necessary, but physical interaction is impossible: in a surgery room, or nursing homes as interface to vital monitoring equipment, in cars or smart-homes.

### Challenge and Real Life Applicability

Machine Learning is steadily becoming easier as frameworks like tensorflow and pytorch refine their functionality. For a challenge, I wanted to give this project a little spin and see how converted models behave. Deployment and applicability to real life problems is another aspect that often poses problems, looking into a concrete usecase seems to be a good way to get some experience.


# Timeline

Start: 18.11.2020: Training, conversion and testing. A Notebook that focuses solely on the data and model.
 
