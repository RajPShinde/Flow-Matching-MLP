# Flow Matching MLP

A minimal, tested implementation of flow matching, validated on a 2D bimodal distribution.
learns a velocity field that transports samples from a Gaussian prior onto a target distribution.
Two moons is used as the target because it is the smallest case that exposes what this method is for: a model that regresses a conditional mean collapses the two crescents into the empty space between them, while a correct transport populates both.

## **Outputs**
<img src="/output/output.png"/>

## References
[Flow Matching for Generative Modeling](https://arxiv.org/pdf/2210.02747)
