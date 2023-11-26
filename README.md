<img src="./q-transformer.png" width="450px"></img>

## Q-transformer (wip)

Implementation of <a href="https://qtransformer.github.io/">Q-Transformer</a>, Scalable Offline Reinforcement Learning via Autoregressive Q-Functions, out of Google Deepmind

## Todo

- [ ] first work way towards single action support
- [ ] build out main proposal in paper (autoregressive discrete actions until last action, reward given only on last)
- [ ] do n-step Q learning, even though not that big of improvement
- [ ] figure out the conservative regularization, read prior work
- [ ] add dueling architecture, just to get more RL experience
- [ ] add double Q + pessimism support
- [ ] improvise a cross attention variant instead of concatenating previous actions? (could have wrong intuition here)
- [ ] see if the main idea in this paper is applicable to language models

## Citations

```bibtex
@inproceedings{qtransformer,
    title   = {Q-Transformer: Scalable Offline Reinforcement Learning via Autoregressive Q-Functions},
    authors = {Yevgen Chebotar and Quan Vuong and Alex Irpan and Karol Hausman and Fei Xia and Yao Lu and Aviral Kumar and Tianhe Yu and Alexander Herzog and Karl Pertsch and Keerthana Gopalakrishnan and Julian Ibarz and Ofir Nachum and Sumedh Sontakke and Grecia Salazar and Huong T Tran and Jodilyn Peralta and Clayton Tan and Deeksha Manjunath and Jaspiar Singht and Brianna Zitkovich and Tomas Jackson and Kanishka Rao and Chelsea Finn and Sergey Levine},
    booktitle = {7th Annual Conference on Robot Learning},
    year   = {2023}
}
```
