---
layout: page
title: TensorCircuit-NG
description: Tensor network based quantum software framework - next generation
img: assets/img/TCNG-black.jpg
importance: 1
category: work
related_publications: false
github_repos: ["refraction-ray/tensorcircuit", "tencent-quantum-lab/tensorcircuit", "tensorcircuit/tensorcircuit-ng"]
---

TensorCircuit-NG is an open-source high-performance quantum computing software framework in Python.
<p style="text-align: justify;">
TensorCircuit is a high-performance, open-source quantum software framework designed to accelerate innovation in quantum computing. Powered by an advanced tensor network engine and built with seamless integration with leading machine learning frameworks like TensorFlow, JAX, and PyTorch, TensorCircuit delivers unparalleled simulation speed and scalability – offering speedups of up to 10^6x on common tasks and enabling simulations of significantly larger circuits compared to traditional state vector methods. Its versatility covers a wide range of quantum simulation scenarios, providing a robust platform for hybrid quantum-classical algorithm development, advanced ML integration, and diverse quantum computing research.
</p>
<p style="text-align: justify;">
Trusted by leading institutions and companies worldwide, including top universities like Harvard, MIT, and Peking University, and industry giants like NVIDIA, IBM, and Google, TensorCircuit has become a foundational tool with over 800,000 downloads and cited in over 100 research papers. Its adoption by labs already possessing their own quantum software underscores its recognized excellence and broad influence. Recognized through honors like Google Summer of Code recommendation and selection for NVIDIA cuQuantum benchmarks, TensorCircuit stands as a testament to its impact and essential role in the global quantum ecosystem.
</p>
## Links

- <a href="https://github.com/tensorcircuit/tensorcircuit-ng" target="_blank"><i class="fab fa-github"></i> Repo</a>: https://github.com/tensorcircuit/tensorcircuit-ng

- <a href="https://tensorcircuit-ng.readthedocs.io/" target="_blank"><i class="fas fa-book"></i> Documentation</a>: https://tensorcircuit-ng.readthedocs.io/

- <a href="https://pypi.org/project/tensorcircuit-ng/" target="_blank"><i class="fab fa-python"></i> PyPI</a>: https://pypi.org/project/tensorcircuit-ng/

## History of the package

See [here](https://github.com/tensorcircuit/tensorcircuit-ng/blob/master/HISTORY.md) for the brief history of TensorCircuit.

<div class="repositories d-flex flex-wrap flex-md-row flex-column justify-content-between align-items-center">
  {% for repo in page.github_repos %}
    {% include repository/repo.liquid repository=repo %}
  {% endfor %}
</div>