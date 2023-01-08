+++
title = "Model-based Reinforcement Learning for Elastic Stream Processing in Edge Computing"
abstract = "Low-latency data processing is critical for enabling next generation Internet-of-Things(IoT) applications. Edge computing-based stream processing techniques that optimize for low latency and high throughput provide a promising solution to ensure a rich user experience by meeting strict application requirements. However, manual performance tuning of stream processing applications in heterogeneous and dynamic edge computing environments is not only time consuming but also not scalable. Our work presented in this paper achieves elasticity for stream processing applications deployed at the edge by automatically tuning the applications to meet the performance requirements. The proposed approach adopts a learning model to configure the parallelism of the operators in the stream processing application using a reinforcement learning(RL) method. We model the elastic control problem as a Markov Decision Process(MDP) and solve it by reducing it to a contextual Multi-Armed Bandit(MAB) problem. The techniques proposed in our work uses Upper Confidence Bound(UCB)-based methods to improve the sample efficiency in comparison to traditional random exploration methods such as the e-greedy method. It achieves a significantly improved rate of convergence compared to other RL methods through its innovative use of MAB methods to deal with the tradeoff between exploration and exploitation. In addition, the use of model-based pre-training results in sub-stantially improved performance by initializing the model with appropriate and well-tuned parameters. The proposed techniques are evaluated using realistic and synthetic workloads through both simulation and real testbed experiments. The experiment results demonstrate the effectiveness of the proposed approach compared to standard methods in terms of cumulative reward and convergence speed."
authors = ["Jinlai Xu", "Balaji Palanisamy"]
date = "2021-12-17"
image_preview = ""
math = false
publication = "In 2021 IEEE 28th International Conference on High Performance Computing, Data, and Analytics (HiPC)"
publication_short = "In IEEE HiPC 2021"
publication_types = ["1"]
featured = false
url_code = ""
url_dataset = ""
url_pdf = "https://www.researchgate.net/publication/356067882_Model-based_Reinforcement_Learning_for_Elastic_Stream_Processing_in_Edge_Computing"
url_project = ""
url_slides = ""
url_video = ""
url_poster = ""
url_preprint = ""
url_source = ""

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
# image:
#   caption = 'Proposed Decoupled Edge Computing Architecture = *Zenith* :smile:'
#   focal_point = "Smart"
#   preview_only = false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects = []`.
# projects = 
# - zenith

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides = ""`.
# slides = example
+++

