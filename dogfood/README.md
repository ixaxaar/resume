
<!-- &nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<img src="https://i.imgur.com/il87wZJ.jpg" alt="Drawing" width="200px"/> -->

## [Russi Chatterjee](https://i.imgur.com/il87wZJ.jpg)
- Github: [@ixaxaar](https://github.com/ixaxaar) Stackoverflow: [@ixaxaar](https://stackoverflow.com/users/2134957/ixaxaar) Twitter: [@markovinchains](https://twitter.com/markovinchains)
- Email [root@ixaxaar.in](root@ixaxaar.in) / [russichatterjee@gmail.com](russichatterjee@gmail.com)

### In short
- ~ 3 years experience as Data Scientist, ~ 4 years as Software Engineer
- Experience in applied computational linguistics, information retrieval & deep learning
- Also worked on embedded systems, web fontend, web backends
- Have worked with and (tech) lead teams, owned medium to long term projects, at various scales
- Created India's largest doctor search engine

### Education
- B-Tech., Computer Science, [NIT, Rourkela](https://en.wikipedia.org/wiki/National_Institute_of_Technology,_Rourkela) - 2006-2010
- Internship on robustness of image watermarking, [Indian Statistical Institute, Kolkata](https://en.wikipedia.org/wiki/Indian_Statistical_Institute)
- Thesis on Computer Vision - [Texture Segmentation Using Gabor Filters and Wavelets](http://ethesis.nitrkl.ac.in/1616/1/Image_Segmentation-project.pdf)
- Coursera certificates in [Statistical Inference](https://www.coursera.org/course/statinference), [Computational Neuroscience](https://www.coursera.org/course/compneuro), [The Brain and Space](https://www.coursera.org/course/brainspace), [Synapses, Neurons & Brains](https://www.coursera.org/account/accomplishments/records/ggNMj63vVSXXKNwM), [Bioinformatics I](https://www.coursera.org/account/accomplishments/records/CFDUSJFAXFYR)

### Open source work

- **Deep Learning**
1. [pytorch-dnc](https://github.com/ixaxaar/pytorch-dnc) : Stacked [Differential Neural Computers](https://www.nature.com/articles/nature20101.epdf?author_access_token=ImTXBI8aWbYxYQ51Plys8NRgN0jAjWel9jnR3ZoTv0MggmpDmwljGswxVdeocYSurJ3hxupzWuRNeGvvXnoO8o4jTJcnAyhGuZzXJ1GEaD-Z7E6X_a9R-xqJ9TfJWBqz) with shareable memory.
2. [seq2seq-dnc](https://github.com/ixaxaar/seq2seq-dnc) : Seq2seq-attn networks with augmented memory
2. [subLSTM](https://github.com/ixaxaar/pytorch-sublstm) : Implementation of subLSTMs from [Cortical microcircuits as gated-recurrent neural networks](https://arxiv.org/abs/1711.02448).
3. [awd-dnc-lm](https://github.com/ixaxaar/awd-dnc-lm) : A Neural language model with augmented memory.
- **Computational Neuroscience**
1. [Spectrum](https://github.com/synergetics/spectrum) : Higher-order spectrum estimation toolkit, for analysing EEG recordings
2. [Cortical Microcircuit](https://github.com/synergetics/potjans_2014) : Implementation of a cortical microcircuit, in pyNEST, from [The cell-type specific cortical microcircuit: relating structure and activity in a full-scale spiking network model.](https://www.ncbi.nlm.nih.gov/pubmed/23203991)
3. [S-transform](https://github.com/synergetics/stockwell_transform) : The Stockwell transorm for signal processing (used in neuroscience and geology)

### Experience
#### 1. Senior Machine Learning Engineer, on Contract, Undisclosable (03-2018 - present)
- **One-shot learning**: one-shot meta-learning object recognition task

```scala
  - Adversarial autoencoders and prototype learning
  - Stack: Pytorch, opencv, PIL, scikit-learn, scikit-image
  - Datasets: MNIST, CIFAR-10, miniImagenet
```

#### 2. Data Scientist, [Reverie language technologies](http://reverieinc.com/) (07-2016 - 08-2017)
- **Telperion & Laurelin**: cross-linguistic search query rewriting (bunch of microservices)

```scala
  - Transliterate a search query from Indian languages to English
    - e.g. "फेनमैन लेक्टर्स हार्डबाउंड" ==> "feynman lectures hardbound"
    - Employs a seq2seq-attn neural net and Language models
  - Extract terms out out of a search query and label the terms
    - { "feynman lectures": "book", "hardbound": "type" }
    - Employs Knowledge bases and mapped taxonomies
  - Stack: Scala, Python, Torch, Lucene, CoreNLP, KenLM, openIE
  - Datasets: GDELT, Commoncrawl Webtables, COCA/GlobWe, Web1T, etc
```

#### 3. Data Scientist & Tech Lead - Search, [Practo](https://practo.com) (05-2015 - 07-2016)
- **Cerebro**: search platform, powers [practo.com](https://practo.com)
```markdown
  - Powering the largest doctor search portal in India
  - Medical query expansion using SNOMED-CT
  - Robust autocorrect using combination of string distances
  - Search ranking algorithm and evaluation
  - Horizontally scaled, high availability microservices
  - Mungle and derive insights about user behavior (click streams)
  - Stack: Scala, Akka, Lucene, CoreNLP, Spray, Spark, Hive
```

#### 4. Software Engineer, on contract, [Showt](https://showt.com) (07-2014 - 01-2015)
- **Trends**: trends detection in social streams
```markdown
  - Define a model for "trending" and algorithm to detect trending
  - Evaluate and validate algorithm with twitter data as reference
  - Implement trending microservice
  - Stack: Python, node.js, ZeroMQ, redis, cassandra
```
- **Rylai**: Milestone / Event detection in social streams
```markdown
  - Infrastructure for sharded counting
  - Data pipeline for event delivery (feeds and notifications)
  - Stack: Scala, storm, cassandra
```

#### 5. Software Engineer, MagnetWorks (08-2013 - 06-2014)
 - **Doriath**: Frontend dashboards
```markdown
 - Dynamic web dashboards built on backbone
 - Stack: D3, NVD3, Backbone, Bootstrap, JQuery, HTML-CSS-JS
```
 - **Sentience**: Analytics backend for time series data, ETL engine, ML algorithms job runner
```markdown
 - Compute engine of various time series metrics
 - Stack: node.js, R, RServe, CouchDB, PostgreSQL
```
 - **Enzo**: Time series data capture and API backend
```markdown
 - Magnetlang - python-based custom DSL for ETL
 - Stack: python, Django, pandas, numpy
```

#### 6. Software Engineer, Toshiba (02-2013 - 08-2013)
```markdown
  - Wrote interrupt subsystem & ABI of TOPPERS microkernel
  - Stack: Assembly languages (ARM and Tensilica), C, gcc
```

#### 7. Software Engineer, Wipro (02-2011 - 02-2013)
```markdown
  - Linux device driver for Maxim 9240
  - Bootloader and remote firmware updater for Renesas M16C
  - Inter-processor communication over SPI bus
  - The above runs on some Honda, Mazda and Ford vehicles
  - Stack: C, Linux kernel, Assembly language
```

## Outside of work

- [Online gaming](http://steamcommunity.com/profiles/76561198086597123/)
- [Music](https://www.last.fm/user/vairagyam)
- Complex Networks, Computational Neuroscience, Category Theory / functional programming
- Trekking & Mountaineering
