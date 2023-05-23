---
title: Corpora
keywords: corpus, dataset
last_updated: May 14, 2023
datatable: true
summary: "Corpora and datasets for discourse and dialogue reserach"
sidebar: mydoc_sidebar
hide_sidebar: true
permalink: corpora.html
folder: corpora
---

The corpora list has been adapted from [A Survey of Available Corpora for Building Data-Driven Dialogue Systems](https://arxiv.org/abs/1512.05742), with permission; see the [survey website](https://breakend.github.io/DialogDatasets/) for reference and please cite the paper if useful.

<div class="datatable-begin"></div>
<table>
<colgroup>
<col width="10%" />
<col width="8%" />
<col width="8%" />
<col width="8%" />
<col width="8%" />
<col width="8%" />
<col width="8%" />
<col width="8%" />
<col width="24%" />
<col width="10%" />
</colgroup>
<thead>
<tr class="header">
<th>Name</th>
<th>Language</th>
<th>Modalities</th>
<th>Data Types</th>
<th>Task/Domain</th>
<th>Participants</th>
<th>Size</th>
<th>Ave. # of Turns</th>
<th>Belief Dscription</th>
<th>Paper</th>
</tr>
</thead>
<tbody>

<tr>
<td markdown="span">[Let’s go & DSTC1](https://github.com/DialRC/LetsGoDataset)</td>
<td markdown="span">English</td>
<td markdown="span">Speech</td>
<td markdown="span">Audio</td>
<td markdown="span">Bus schedules</td>
<td markdown="span">Human-system</td>
<td markdown="span">171K dialogues</td>
<td markdown="span">N/A</td>
<td markdown="span">Telephone conversations between real users and bus information systems</td>
<td markdown="span">[Raux et al. 2006](https://www.isca-speech.org/archive/interspeech_2006/raux06_interspeech.html)</td>
</tr>


<tr>
<td markdown="span">[DSTC2](https://github.com/matthen/dstc)</td>
<td markdown="span">English</td>
<td markdown="span">Speech</td>
<td markdown="span">Transcripts and ASR results</td>
<td markdown="span">Restaurant search</td>
<td markdown="span">Human-system</td>
<td markdown="span">15K dialogues, 3.7M words</td>
<td markdown="span">7.88</td>
<td markdown="span">Telephone conversations between hired users and restaurant search system</td>
<td markdown="span">[Henderson et al, 2014](https://aclanthology.org/W14-4337/)</td>
</tr>

<tr>
<td markdown="span">[MultiWoz 1.0](https://github.com/budzianowski/multiwoz)</td>
<td markdown="span">English</td>
<td markdown="span">Text</td>
<td markdown="span">Text</td>
<td markdown="span">Multiple domains (restaurant, hotel, etc.)</td>
<td markdown="span">Human-Woz</td>
<td markdown="span">8.5K dialogues, 115K turns, 1.5M tokens</td>
<td markdown="span">13.18</td>
<td markdown="span">Task-orienteid dialogues</td>
<td markdown="span">[Budzianowski et al., 2018](https://aclanthology.org/D18-1547/)</td>
</tr>

<tr>
<td markdown="span">[HCRC MapTask Corpus](https://groups.inf.ed.ac.uk/maptask/)</td>
<td markdown="span">English</td>
<td markdown="span">Face-to-face</td>
<td markdown="span">Audio, video (not available)</td>
<td markdown="span">direction giving</td>
<td markdown="span">human-human</td>
<td markdown="span">128 dialogues, 174K words, 18hrs</td>
<td markdown="span"></td>
<td markdown="span"></td>
<td markdown="span">[Anderson et al., 1991](https://journals.sagepub.com/doi/10.1177/002383099103400404)</td>
</tr>

<tr>
<td markdown="span">[AMI Corpus](https://groups.inf.ed.ac.uk/ami/corpus/)</td>
<td markdown="span">English</td>
<td markdown="span">face-to-face</td>
<td markdown="span">close-talking and far-field microphones, individual and room-view video cameras, projection, a whiteboard, individual pens.</td>
<td markdown="span">Face-to-face meetings</td>
<td markdown="span">multi-party human</td>
<td markdown="span">175 dialogues, 900K words, 100hrs</td>
<td markdown="span"></td>
<td markdown="span"></td>
<td markdown="span">[Carletta et al, 2005](https://link.springer.com/chapter/10.1007/11677482_3)</td>
</tr>

<tr>
<td markdown="span">[Ubuntu Dialogue Corpus](https://github.com/rkadlec/ubuntu-ranking-dataset-creator)</td>
<td markdown="span">English</td>
<td markdown="span">IRC chat</td>
<td markdown="span">text</td>
<td markdown="span">Chat on Ubuntu</td>
<td markdown="span">human-human</td>
<td markdown="span">930K dialogues, 100M words</td>
<td markdown="span">7.71</td>
<td markdown="span">Dialogues extracted from Ubuntu chat stream on IRC</td>
<td markdown="span">[Lower et al, 2015](https://aclanthology.org/W15-4640/)</td>
</tr>

<tr>
<td markdown="span">[DailyDialog Dataset](http://yanran.li/dailydialog.html)</td>
<td markdown="span">English</td>
<td markdown="span">Text</td>
<td markdown="span">Text</td>
<td markdown="span">Daily communication</td>
<td markdown="span">Human-human</td>
<td markdown="span">13K dialogues, 1.5M words</td>
<td markdown="span">7.9</td>
<td markdown="span"></td>
<td markdown="span">[Li et al. 2017](https://aclanthology.org/I17-1099/)</td>
</tr>


<tr>
<td markdown="span">[Persona Chat](https://github.com/facebookresearch/ParlAI/tree/main/parlai/tasks/personachat)</td>
<td markdown="span">English</td>
<td markdown="span">Chat text</td>
<td markdown="span">Text</td>
<td markdown="span">Open domain</td>
<td markdown="span">Human-human</td>
<td markdown="span">11K dialogues, 162K utterances</td>
<td markdown="span"></td>
<td markdown="span">A chit-chat dataset where paired Turkers are given assigned personas and chat to try to get to know each other. </td>
<td markdown="span">[Zhang et al., 2018](https://arxiv.org/abs/1801.07243)</td>
</tr>

<!--
<tr>
<td markdown="span">[The Schema-Guided Dialogue Dataset](https://github.com/google-research-datasets/dstc8-schema-guided-dialogue)</td>
<td markdown="span">English</td>
<td markdown="span"></td>
<td markdown="span"></td>
<td markdown="span"></td>
<td markdown="span"></td>
<td markdown="span"></td>
<td markdown="span"></td>
<td markdown="span"></td>
<td markdown="span"></td>
</tr>

<tr>
<td markdown="span">EmoWOZ</td>
<td markdown="span"></td>
<td markdown="span">English</td>
<td markdown="span"></td>
<td markdown="span"></td>
<td markdown="span"></td>
<td markdown="span"></td>
<td markdown="span"></td>
<td markdown="span"></td>
<td markdown="span"></td>
<td markdown="span"></td>
</tr>

<tr>
<td markdown="span">CMU Communicator Corpus</td>
<td markdown="span"></td>
<td markdown="span"></td>
<td markdown="span"></td>
<td markdown="span"></td>
<td markdown="span"></td>
<td markdown="span"></td>
<td markdown="span"></td>
<td markdown="span"></td>
<td markdown="span"></td>
</tr>

<tr>
<td markdown="span">Key-Value Retrieval dataset</td>
<td markdown="span"></td>
<td markdown="span"></td>
<td markdown="span"></td>
<td markdown="span"></td>
<td markdown="span"></td>
<td markdown="span"></td>
<td markdown="span"></td>
<td markdown="span"></td>
<td markdown="span"></td>
</tr>
-->

</tbody>
</table>
<div class="datatable-end"></div>


