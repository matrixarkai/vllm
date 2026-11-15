# Contributing to this fork

This public Apache-2.0 fork develops experimental, opt-in vLLM scheduling changes.
Anyone may fork it, file an issue, or submit a pull request.

For general development, follow the [upstream contribution guide](https://docs.vllm.ai/en/latest/contributing/).
Keep attribution and licensing intact and sign off contributions.

The controller proposal is discussed in [upstream issue #62574](https://github.com/vllm-project/vllm/issues/62574).
Its implementation, limitations, reproduction commands and CPU-only results are
in [the experiment guide](benchmarks/adaptive_prefill/README.md) and
[validation notes](benchmarks/adaptive_prefill/RESULTS.md).

GPU validation contributions are welcome. Record the commit, hardware, model,
server configuration, arrival trace, and baseline/adaptive results. Do not label
CPU simulations or HTTP protocol fixtures as GPU measurements.

Submit experimental changes as draft PRs when engine or GPU validation remains
incomplete. Review approval must come from the actual reviewer.
