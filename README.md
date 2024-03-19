<!-- <div style="margin-bottom:1em"> -->
<!-- <iframe width="560" height="315" src="https://www.youtube.com/embed/o7dvFLHb5AY" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe> -->
<!-- </div> -->
## Overview

Decoding user intention from neural data provides a potential avenue to restore independence, communication, and mobility to individuals with paralysis. Intracortical spiking activity recorded from brain-computer interfaces (BCI) in particular provides high quality signals for enabling such control. However, the decoders built on intracortical spiking activity will often fail when used in real-world settings due to the non-stationarity of the neural signals. This non-stationarity can be caused by a variety of factors, including changes in the neural recording environment, changes in the user's behavior, and changes in the user's neural signals. At a holistic level, these changes result in inconsistent decoding performance across days. Restoring decoding performance often requires an inconvenient interruption of device use to perform a recalibration procedure, in which a user repeatedly performs a set of prescribed behaviors. Consequently, methods for adapting decoders to new days are critical for the real-world deployment of brain-computer interfaces.

We propose FALCON as a benchmark to standardize the evaluation of adaptation algorithms for intracortical BCI (iBCI). For 4 different decoding tasks spanning the current use of iBCIs, FALCON provides paired neural and behavioral data collected over an early period of experiments and evaluates decoders on new days. In the BCI literature, these paired data would be termed "calibration" data as they are used to train decoders. Since decoding on new days is ill-posed without any data, but calibration data on new days should be minimized, we frame decoding on new days as a few-shot adaptation problem, and provide a greatly reduced amount of calibration data on new days.

We host a challenge to kickstart the FALCON benchmark, but the benchmark will be available indefinitely. To get started with the challenge, follow the links on the left.

- [Read about FALCON in our technical paper]().
<!-- - [Join the mailing list for updates](https://forms.gle/o7BejfJ2S9hqJpM28). -->
<!-- - [See our Cosyne '21 announcement](https://www.youtube.com/watch?v=o7dvFLHb5AY). -->
<!-- - [Join our Slack workspace](https://neurallatents.slack.com). Please email `fpei6 [at] gatech [dot] edu` for an invite link. -->

## FAQ
### How do I submit a model to the benchmark?
We are hosting our challenge on [EvalAI](), a platform for evaluating machine learning models. On the platform, you can choose to make private or public submissions to any or all of the individual datasets.

### Can I view the leaderboard without submitting?
Yes, the full leaderboard will be available on [EvalAI](), and EvalAI is also synced with [Papers With Code](https://paperswithcode.com/). Model open-sourcing is encouraged and thus may be available through the leaderboard.

### Is there a deadline?
The benchmark and its leaderboard can be submitted to indefinitely on EvalAI as a resource for the community. 

## Citation
If you use the FALCON in your work, please cite our preprint, which is not yet posted.

## Contact
The FALCON benchmark is being led by the Systems Neural Engineering Lab in collaboration with labs across several universities. General inquiries should be directed to [Dr. Pandarinath] at `chethan [at] gatech [dot] edu`.
