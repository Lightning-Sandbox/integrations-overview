# integrations ⚡ overview

## Accelerators

### Intel Habana

[Habana® Gaudi® AI Processor (HPU)](https://habana.ai/) training processors are built on a heterogeneous architecture with a cluster of fully programmable Tensor Processing Cores (TPC) along with its associated development tools and libraries, and a configurable Matrix Math engine.

[![PyPI Status](https://badge.fury.io/py/lightning-habana.svg)](https://badge.fury.io/py/lightning-habana)
[![PyPI - Python Version](https://img.shields.io/pypi/pyversions/lightning-habana)](https://pypi.org/project/lightning-habana/)
[![PyPI Status](https://pepy.tech/badge/lightning-habana)](https://pepy.tech/project/lightning-habana)
[![Deploy Docs](https://github.com/Lightning-AI/lightning-Habana/actions/workflows/docs-deploy.yml/badge.svg)](https://lightning-ai.github.io/lightning-Habana/)

[![General checks](https://github.com/Lightning-AI/lightning-habana/actions/workflows/ci-checks.yml/badge.svg?event=push)](https://github.com/Lightning-AI/lightning-habana/actions/workflows/ci-checks.yml)
[![Build Status](https://dev.azure.com/Lightning-AI/compatibility/_apis/build/status/Lightning-AI.lightning-Habana?branchName=main)](https://dev.azure.com/Lightning-AI/compatibility/_build/latest?definitionId=45&branchName=main)

## Strategies

### ColossalAI

The [Colossal-AI](https://colossalai.org/) implements ZeRO-DP with chunk-based memory management.
With this chunk mechanism, really large models can be trained with a small number of GPUs.

[![PyPI Status](https://badge.fury.io/py/lightning-colossalai.svg)](https://badge.fury.io/py/lightning-colossalai)
[![PyPI - Python Version](https://img.shields.io/pypi/pyversions/lightning-colossalai)](https://pypi.org/project/lightning-colossalai/)
[![PyPI Status](https://pepy.tech/badge/lightning-colossalai)](https://pepy.tech/project/lightning-colossalai)
[![Deploy Docs](https://github.com/Lightning-AI/lightning-ColossalAI/actions/workflows/docs-deploy.yml/badge.svg)](https://lightning-ai.github.io/lightning-ColossalAI/)

[![General checks](https://github.com/Lightning-AI/lightning-colossalai/actions/workflows/ci-checks.yml/badge.svg?event=push)](https://github.com/Lightning-AI/lightning-colossalai/actions/workflows/ci-checks.yml)
[![CI testing](https://github.com/Lightning-AI/lightning-colossalai/actions/workflows/ci-testing.yml/badge.svg?event=push)](https://github.com/Lightning-AI/lightning-colossalai/actions/workflows/ci-testing.yml)
[![Build Status](https://dev.azure.com/Lightning-AI/compatibility/_apis/build/status/Lightning-AI.lightning-ColossalAI?branchName=main)](https://dev.azure.com/Lightning-AI/compatibility/_build/latest?definitionId=42&branchName=main)

### Hivemind

[Hivemind](https://github.com/learning-at-home/hivemind) - collaborative training tries to solve the need for top-tier multi-GPU servers by allowing you to train across unreliable machines, such as local machines or even preemptible cloud compute across the internet.

[![PyPI Status](https://badge.fury.io/py/lightning-hivemind.svg)](https://badge.fury.io/py/lightning-hivemind)
[![PyPI - Python Version](https://img.shields.io/pypi/pyversions/lightning-hivemind)](https://pypi.org/project/lightning-hivemind/)
[![PyPI Status](https://pepy.tech/badge/lightning-hivemind)](https://pepy.tech/project/lightning-hivemind)
[![Deploy Docs](https://github.com/Lightning-AI/lightning-Hivemind/actions/workflows/docs-deploy.yml/badge.svg)](https://lightning-ai.github.io/lightning-Hivemind/)

[![General checks](https://github.com/Lightning-AI/lightning-hivemind/actions/workflows/ci-checks.yml/badge.svg?event=push)](https://github.com/Lightning-AI/lightning-hivemind/actions/workflows/ci-checks.yml)
[![CI testing](https://github.com/Lightning-AI/lightning-hivemind/actions/workflows/ci-testing.yml/badge.svg?event=push)](https://github.com/Lightning-AI/lightning-hivemind/actions/workflows/ci-testing.yml)
[![Build Status](https://dev.azure.com/Lightning-AI/compatibility/_apis/build/status/Lightning-AI.lightning-Hivemind?branchName=main)](https://dev.azure.com/Lightning-AI/compatibility/_build/latest?definitionId=43&branchName=main)

### Bagua

[Bagua](https://github.com/BaguaSys/bagua) is a deep learning training acceleration framework which supports multiple advanced distributed
training algorithms.

[![PyPI Status](https://badge.fury.io/py/lightning-bagua.svg)](https://badge.fury.io/py/lightning-bagua)
[![PyPI - Python Version](https://img.shields.io/pypi/pyversions/lightning-bagua)](https://pypi.org/project/lightning-bagua/)
[![PyPI Status](https://pepy.tech/badge/lightning-bagua)](https://pepy.tech/project/lightning-bagua)
[![Deploy Docs](https://github.com/Lightning-AI/lightning-Bagua/actions/workflows/docs-deploy.yml/badge.svg)](https://lightning-ai.github.io/lightning-Bagua/)

[![General checks](https://github.com/Lightning-AI/lightning-bagua/actions/workflows/ci-checks.yml/badge.svg?event=push)](https://github.com/Lightning-AI/lightning-bagua/actions/workflows/ci-checks.yml)
[![Build Status](https://dev.azure.com/Lightning-AI/compatibility/_apis/build/status/Lightning-AI.lightning-Bagua?branchName=main)](https://dev.azure.com/Lightning-AI/compatibility/_build/latest?definitionId=47&branchName=main)

### Horovod

[Horovod](http://horovod.ai) allows the same training script to be used for single-GPU, multi-GPU, and multi-node training.

[![PyPI Status](https://badge.fury.io/py/lightning-horovod.svg)](https://badge.fury.io/py/lightning-horovod)
[![PyPI - Python Version](https://img.shields.io/pypi/pyversions/lightning-horovod)](https://pypi.org/project/lightning-horovod/)
[![PyPI Status](https://pepy.tech/badge/lightning-horovod)](https://pepy.tech/project/lightning-horovod)
[![Deploy Docs](https://github.com/Lightning-AI/lightning-Horovod/actions/workflows/docs-deploy.yml/badge.svg)](https://lightning-ai.github.io/lightning-Horovod/)

[![General checks](https://github.com/Lightning-AI/lightning-horovod/actions/workflows/ci-checks.yml/badge.svg?event=push)](https://github.com/Lightning-AI/lightning-horovod/actions/workflows/ci-checks.yml)
[![CI testing](https://github.com/Lightning-AI/lightning-horovod/actions/workflows/ci-testing.yml/badge.svg?event=push)](https://github.com/Lightning-AI/lightning-horovod/actions/workflows/ci-testing.yml)
[![Build Status](https://dev.azure.com/Lightning-AI/compatibility/_apis/build/status/Lightning-AI.lightning-Horovod?branchName=main)](https://dev.azure.com/Lightning-AI/compatibility/_build/latest?definitionId=44&branchName=main)

## Loggers
