+++
title = "Amnis: Optimized stream processing for edge computing"
abstract = "The proliferation of Internet-of-Things (IoT) devices is rapidly increasing the demands for efficient processing of low latency stream data generated close to the edge of the network. Edge computing-based stream processing techniques that carefully consider the heterogeneity of the computational and network resources available in the infrastructure provide significant benefits in optimizing the throughput and end-to-end latency of the data streams. In this paper, we propose a novel stream query processing framework called Amnis that optimizes the performance of the stream processing applications through a careful allocation of computational and network resources available at the edge. The Amnis approach differentiates itself through its consideration of data locality and resource constraints during physical plan generation and operator placement for the stream queries. Additionally, Amnis considers the coflow dependencies to optimize the network resource allocation through an application-level rate control mechanism. We implement a prototype of Amnis in Apache Storm. Our performance evaluation carried out in a real testbed shows that the proposed techniques achieve as much as 200X improvement on the end-to-end latency and 10X improvement on the overall throughput compared to the default resource aware scheduler in Storm."
authors = ["Jinlai Xu", "Balaji Palanisamy", "Qingyang Wang", "Heiko Ludwig", "Sandeep Gopisetty"]
date = "2021-11-09"
image_preview = ""
math = false
publication = "Journal of Parallel and Distributed Computing"
publication_short = "JPDC"
publication_types = ["2"]
featured = true
url_code = ""
url_dataset = ""
url_pdf = "https://www.researchgate.net/publication/356067975_Amnis_Optimized_Stream_Processing_for_Edge_Computing"
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
projects = ["edge-stream"]

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides = ""`.
# slides = example
+++

