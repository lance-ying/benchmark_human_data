# Human data for paper "[On Benchmarking Human-Like Intelligence in Machines](https://arxiv.org/abs/2502.20502)"

This repo contains human data collected on 10 benchmarks. We randomly sampled 30 stimuli from each benchmark and recruited 240 participants from Prolific to label the dataset. Each participant was randomly assigned to a dataset and completed 30 trials in a randomized order. We used the same answer options provided by the benchmarks, but instead of using a multiple choice question we asked participants to drag a slider on a scale from 1-100 (e.g. 1 = strongly disagree, 100 = strongly agree) for each answer option.

Human data can be found in [human_data.json](human_data.json). Each entry contains a dataset name (key) and human judgment on the 30 stimuli under the task (values). You can find the 30 stimulli for each task under [stimuli.py](stimuli_set.py). The analysis code is in [analysis.ipynb](analysis.ipynb).

If you use our collected data in a scientific publication, we would appreciate using the following citations:

```
@article{ying2025benchmarking,
  title={On Benchmarking Human-Like Intelligence in Machines},
  author={Ying, Lance and Collins, Katherine M and Wong, Lionel and Sucholutsky, Ilia and Liu, Ryan and Weller, Adrian and Shu, Tianmin and Griffiths, Thomas L and Tenenbaum, Joshua B},
  journal={arXiv preprint arXiv:2502.20502},
  year={2025}
}
```
