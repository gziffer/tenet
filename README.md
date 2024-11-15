# TENET: Benchmarking Data Stream Classifiers in Presence of Temporal Dependence ⏳

[![License](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT)

TENET is a novel benchmarking framework designed to evaluate data stream classifiers in non-i.i.d. scenarios with temporal dependence. It provides tools for generating time-dependent data streams and evaluating classifier performance in the presence of concept drift and temporal dependencies. 🔄

## Features

- **Meta-generator for Time-dependent Data Streams**: Create synthetic benchmarks with temporal dependencies to investigate existing SML algorithms' guarantees
- **Continuous LSTM Implementation (cLSTM)**: A baseline classifier capable of handling both concept drift and temporal dependence
- **Comprehensive Evaluation Framework**: Includes metrics, datasets, and methodologies for comparing SML approaches
- **Temporal Injection**: Introduces temporal dependencies into standard data stream benchmarks

## Available Datasets

TENET includes several synthetic and real-world datasets:

### Synthetic
- SEA Concepts
- STAGGER
- Sine1 and Sine2
- Hyperplane
- Random RBF
- Agrawal

### Real-world
- Electricity Market (Elec2)
- Insects
- Power Supply
- Rialto Bridge
- Weather

## Citation 📚

Citation information will be available after publication.
The paper "Tenet: Benchmarking Data Stream Classifiers in Presence of Temporal Dependence" by Giacomo Ziffer, Federico Giannini, and Emanuele Della Valle is currently in press.

## Contributing

We welcome contributions!

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contact

Giacomo Ziffer - giacomo.ziffer@polimi.it
