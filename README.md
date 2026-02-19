# Statistical Project – Network-Based Epidemic Modelling

This project models the spread of an infectious disease in a school environment using network-based simulation. Individuals are represented as nodes in a contact graph, and infections propagate probabilistically along edges.

Using statistical inference, we evaluate the effectiveness of different vaccination strategies in reducing the peak number of infections. Vaccination policies are based on network centrality measures (e.g., degree centrality), and we additionally test a network-agnostic strategy inspired by the friendship paradox.

## Setup Instructions

1. Clone the repo:
```bash
git clone https://github.com/pgitti/epidemic_modelling.git
cd eeg_decoder_project
```

2. Create and activate the environment:
```bash
conda env create -f environment.yml
conda activate eeg_decoder
# conda env remove -n eeg_decoder
```
