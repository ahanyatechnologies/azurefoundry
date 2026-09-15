# Azure Foundry

The Foundry Models catalog serves as your central hub for discovering and comparing AI models.

Model catalog includes two broad categories of models:
- Foundry Models sold directly by Azure
- Foundry Models from partners and community

## Model Benchmarks

In the model catalog, view the Model leaderboard to see comparative rankings across all available models. This view helps you identify top-performing models for specific metrics or scenarios. The leaderboard displays top models ranked by quality, safety, estimated cost, and throughput.

![Model Leaderboard](images/ModelLeaderboard.png)

## Quality Benchmarks

Quality benchmarks assess how well a model generates accurate, coherent, and contextually appropriate responses. These metrics use public datasets and standardized evaluation methods to ensure consistency.

**Quality Index** - It's an avg accuracy scores across multiple benchmark datasets that measure reasoning, knowledge, Q&A, mathematical capabilities & coding skills. Higher value indicates sronger overall performance across general-purpose language tasks. Quality benchmarks use datasets such as:

- **Arena-Hard** - adversarial question answering
- **BIG-Bench Hard** - reasoning capabilities
- **GPQA** - graduate-level multi-discipline questions
- **HumanEval+ and MBPP+** - code generation tasks
- **MATH** - mathematical reasoning
- **MMLU-Pro** - general knowledge assessment
- **IFEval** - instruction following

## Safety Benchmarks

## Cost Benchmarks

## Performance Benchmarks

## Deployment Types

Microsoft Foundry supports several deployment types, each offering different characteristics for data residency, scaling, and billing:

- **Global Standard model** deployments can use any Azure region on a pay-per-token basis. They're best for general workloads, and provide the highest quota.
- **Global Provisioned** deployments can use any Azure region, and their use is based on a reserved provision throughput units(PTU) basis to provide predictable high-throughput.
- **Global Batch** deployments can use any Azure region at a 50% discount for large asynchronous jobs within 24-hours.
- **Data Zone Standard** deployments ensure data stays within a specific data zone on a pay-per-token basis. They're best for scenarios where EU/US data zone compliance is required.
- **Data Zone Provisioned** deployments provide predictable throughput based on reserved PTUs within a data zone.
- **Data Zone Batch** deployments are designed for large asynchronous batch jobs within a data zone/

**Standard deployments** are deployed within a single region on a pay-per-token basis. They're great when you need regional data residency compliance or for low-volume scenarios.
**Regional Provisioned deployments** provide reserved PTUs within a single region.
**Developer Developer deployments** use any Azure region on a pay-per-token basis and are for fine-tuned model evaluation only.



