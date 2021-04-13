# Awesome Text to Video papers

The main goal is to collect text-to-video works in academia and industry.

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

## Papers

- [Frozen in Time: A Joint Video and Image Encoder for End-to-End Retrieval](https://arxiv.org/abs/2104.00650), arxiv 2021, [code](https://github.com/m-bain/frozen-in-time).
- [MDMMT: Multidomain Multimodal Transformer for Video Retrieval](https://arxiv.org/abs/2103.10699), arxiv 2021.
- [Multi-modal Transformer for Video Retrieval](https://hal.inria.fr/hal-02903209/document), ECCV 2020, [code](https://github.com/gabeur/mmt).

## Datasets

- [Microsoft Research Video Description Corpus (MSVD)](https://paperswithcode.com/dataset/msvd)：也称为YouTube2Text dataset，该数据集同样由Microsoft Research提供，地址为 Microsoft Research Video Description Corpus 。该数据集包含1970段YouTube视频片段（时长在10-25s之间），每段视频被标注了大概40条英文句子。
- [MSR-VTT (Microsoft Research Video to Text)](https://paperswithcode.com/dataset/msr-vtt)：该数据集为ACM Multimedia 2016 的 Microsoft Research - Video to Text (MSR-VTT) Challenge。地址为 Microsoft Multimedia Challenge 。该数据集包含10000个视频片段（video clip），被分为训练，验证和测试集三部分。每个视频片段都被标注了大概20条英文句子。此外，MSR-VTT还提供了每个视频的类别信息（共计20类），这个类别信息算是先验的，在测试集中也是已知的。同时，视频都是包含音频信息的。该数据库共计使用了四种机器翻译的评价指标，分别为：METEOR, BLEU@1-4,ROUGE-L,CIDEr。
- [LSMDC (Large Scale Movie Description Challenge)](https://paperswithcode.com/dataset/lsmdc): This dataset contains 118,081 short video clips extracted from 202 movies. Each video has a caption, either extracted from the movie script or from transcribed DVS (descriptive video services) for the visually impaired. The validation set contains 7408 clips and evaluation is performed on a test set of 1000 videos from movies disjoint from the training and val sets.


## Benchmarks

- [Text-To-Video Benchmarks](https://paperswithcode.com/task/video-retrieval).
