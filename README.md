# Frozen Feature Extractors for DeepRL

AGH University of Krakow<br/>
[Center of Excellence in Artificial Intelligence](https://github.com/AGH-CEAI)

## Paper

[Maciej Aleksandrowicz](https://macmacal.github.io) 
[![LinkedIn](https://img.shields.io/badge/Contact-LinkedIn-blue)](https://www.linkedin.com/in/maciej-aleksandrowicz/),<br/>Joanna Jaworek-Korjakowska,<br/>


*Due to a co-author’s preference,* ***the preprint version of this work is not publicly available before formal peer review.***<br/>
*A public version (with the implementation code) will be made available as soon as possible.*

### Abstract

> This study approaches the deep reinforcement learning issue of sample inefficiency with a paradigm shift for observation encoding.
> The agent’s trained perception module is moved to the environment and kept frozen during training.
> This approach is evaluated on visual observations, utilizing pre-trained visual models.
> While results are not conclusive, they yield preliminary insights for future research directions.

### High level idea
<p align="center">
    <img src="./docs/env_ffe_agent.svg" alt="Aegis cobot station preview" width="256"/>
</p>

**Fig.1** - The overview of the proposed Frozen Feature Extractor architecture for an arbitrary DeepRL agent.