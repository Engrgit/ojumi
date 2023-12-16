
![alt](./utils/ojumi.jpg)
# Ojumi - AI eyes 
 

- v0.1 - ojumi beta-version is now released!

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Support Ukraine](https://img.shields.io/badge/Support-Ukraine-FFD500?style=flat&labelColor=005BBB)](https://opensource.fb.com/support-ukraine)

More details of the library at our official website: [Link](www.gamolstudio.com)

Our paper is ArXived at: [Link](www.gamolstudio.com)

## Overview
Replicating my eyes with computer vision.

## Getting Started

### Installation
To install ojumi, you can simply clone this repo and pip install
```
git clone https://github.com/Engrgit/Ojumi.git
cd Ojumi
pip install -e .
```

### Quick Start
To kick off a Ojumi agent with a classic computer vision problem. Here's a quick example.
```
 pip instll ojumi
```

## Design and Features
![alt](./utils/ojumi.jpg)
Ojumi was built with a modular design so that industry practitioners or academic researchers can select any subset and flexibly combine features below to construct a Ereowo agent customized for their specific use cases. Ojumi offers a diverse set of unique features for production environments, including dynamic action spaces, offline learning, intelligent neural exploration, safe decision making, history summarization, and data augmentation.

You can find many Ereowo agent candidates with mix-and-match set of reinforcement learning features in utils/scripts/benchmark_config.py

## Adoption in Real-world Applications
Ojumi is in progress supporting real-world applications, including recommender systems, auction bidding system and creative selection. Each of them requires a subset of features offered by Pearl. To visualize the subset of features used by each of the applications above, see the table below.
<center>

|Pearl Features | Recommender Systems | Auction Bidding | Creative Selection |
|:-------------:|:-------------------:|:---------------:|:------------------:|
|Policy Learning| ✅ |✅|✅|
|Intelligent Exploration|✅|✅ |✅|
|Safety| | ✅ | |
|History Summarization| | ✅ | |
|Replay Buffer| ✅ |✅ |✅ |
|Contextual Bandit| | |✅|
|Offline RL|✅|✅||
|Dynamic Action Space|✅||✅|
|Large-scale Neural Network|✅|||

</center>

## Comparison to Other Libraries
<center>

|Ojumi Features | Ojumi  | ReAgent (Superseded by Ojumi) | RLLib | SB3|Tianshou | Dopamine |
|:-------------:|:------:|:-----------------------------:|:-----:|:--:|:-----:|:-----|
|Modularity|✅|❌|❌|❌|❌|❌|
|Dynamic Action Space|✅|✅|❌|❌|❌|❌|
|Offline RL|✅|✅|✅|✅|✅|❌|
|Intelligent Exploration|✅|❌|❌|❌|⚪ (limited support)|❌|
|Contextual Bandit|✅|✅|⚪ (only linear support)|❌|❌|❌|
|Safe Decision Making|✅|❌|❌|❌|❌|❌|
|History Summarization|✅|❌|✅|❌|⚪ (requires modifying environment state)|❌|
|Data Augmented Replay Buffer|✅|❌|✅|✅|✅|❌|

</center>

## Cite Us
```
@misc{ojumi2023paper,
    title = {Ojumi - Replicating Eyes with Computer Vision},
    author = {Ibrahim Gbadegesin},
    year = 2023,
    eprint = {arXiv}
}
```

## License
Ojumi is MIT licensed, as found in the LICENSE file.

