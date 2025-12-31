# MAF-CTS: Multi-Agent Framework for Complex Task Solving

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Python 3.8+](https://img.shields.io/badge/python-3.8+-blue.svg)](https://www.python.org/downloads/)

A research-oriented framework for building deterministic, transparent, and domain-specific multi-agent conversational systems.

## 🎯 Key Features
- **Deterministic Orchestration**: Explicit controller-based execution enables predictable and reproducible agent coordination
- **Agent Abstraction**: A unified agent interface supports plug-and-play integration of heterogeneous agent roles
- **Configuration-Driven Workflows**: Conversational tasks are defined using JSON/YAML configurations, allowing domain adaptation without modifying core logic
- **Evaluation Hooks**: Built-in pre- and post-execution evaluation mechanisms support constraint checking and experimental analysis
- **Research-Oriented Design**: The framework emphasizes transparency, modularity, and extensibility for academic experimentation

## 📦 Installation (Coming Soon)
```bash
pip install maf-cts
```

## 🚀 Quick Start (Coming Soon)
```python
from maf_cts import Orchestrator, TaskConfig

config = TaskConfig.from_file("ecommerce_config.yaml")
orchestrator = Orchestrator(config)
result = orchestrator.execute(user_query)
```

## 🔬 Research
MAF-CTS is designed to support research in multi-agent large language model systems, particularly for conversational task-solving under controlled orchestration and evaluation settings.
The framework is released as an open-source research artifact to encourage reproducibility and further investigation.

## 📄 License
This project is licensed under the MIT License. See the LICENSE file for details.

## 🤝 Contributing
Contributions are welcome. Please open an issue or submit a pull request for discussion. Please see CONTRIBUTING.md (coming soon)

## 📚 Author
Ahmed, Mustufa. Multi-Agent Framework for Conversational Task-Solving (MAF-CTS). SoftwareX, 2026.
