# SMS Spam Messages Classification 
### Compare Different Vectorizers

![](cover/spam.jpg)

**Goal**: Classify Spam Messages. Compare Tfid with plain text results, Hash Vectorizer with n-Grams results where n=2, and Burrows Wheeler Transform Distance (BWTD) with plain text and n-gram results.<br>
**Approach**:
<ol>
    <li>Supervised Learning task, because given labeled traning examples</li>
    <li>Binary Classification task</li>
    <li>Use plain text with Tfid</li>
    <li>Use N-Grams with Hash Vectorizer</li>
    <li>Use plain text with BWTD</li>
    <li>Use N-Grams with BWTD</li>
    <li>There is no continuous flow of data, no need to adjust to changing data, and the data is small enough to fit in memmory: Batch Learning</li>
</ol>

**Data:** [SMS Spam Collection Dataset | Kaggle](https://www.kaggle.com/uciml/sms-spam-collection-dataset)<br>
**Cover Picture:** [Mobile spam | Flickr](https://www.flickr.com/photos/christiaancolen/20796966373)<br>
**BWTD:** [Burrows Wheeler Transform Distance (BWTD) by Dr. Edward Raff](https://github.com/EdwardRaff/pyBWMD)<br><br>
```
@inproceedings{Raff2020,
author = {Raff, Edward and Nicholas, Charles and McLean, Mark},
booktitle = {The Thirty-Fourth AAAI Conference on Artificial Intelligence},
title = {{A New Burrows Wheeler Transform Markov Distance}},
url = {http://arxiv.org/abs/1912.13046},
year = {2020}
}
```
**Project Author:** Maksim Ekin Eren
