---
layout: post
title: word vector
date: 2021-05-06 14:36
category: NLP
author: pootow
tags: [AI, NLP]
summary: This post will cover word vector, word embedding.
---

# Background

* 什么是 [NLP][] ？
* NLP算法为什么需要vector？

[NLP]: post/NLP

# Brief



[//]: # (brief - what)

`Word vector`（也叫 [`Word embedding`][1] ） 是文本建模的一种方式，目的是为了方便算法分析，他把 word 通过某种方式映射到一个 [vector](post/vector)，映射完成后，相近含义的 word ，在 vector space 里面距离也相近。

[1]: https://en.wikipedia.org/w/index.php?title=Word_vector&redirect=no



[//]: # (brief - how)

那么，要如何才能把 word 映射到 vector 才能做到含义相近距离也相近呢？方法之一是建立在一个叫做 [distributional hypothesis](https://en.wikipedia.org/wiki/Distributional_semantics) 的一个假说：分布相似的语言成分（比如，单词），他们的含义也相似。 用人话说，就是一个词的含义，往往是由他的上下文决定的。



[//]: # (brief - why)

文本到 vector 的建模方式有很多种，常见的方式是，建立一个单词表，单词表的每个单词对应一个所谓 [`one hot`] 的 vector 。但是这种映射方式，有几个缺陷，比如维度太高不容易计算，单词之间的关系无法表示等。

[//]: # (teacher's note: `Language model` vs `text model` vs `word model`)



Other thoughts:

* 文本数据化的其他方式？
    * one hot
        * 缺点？优点？
* 分析？为什么要分析？都能怎么分析？分析出了什么？
* 某种方式？都有那些方式？为什么选择这种方式？

# Application



# Learning Patterns

## Learn by graph & animation

## Learn by example

## Learn by comparison

## Learn by history

## Learn by positioning

## Custom by industry

## Custom by reader's knowledge

## Custom by reader's methodology

## Custom by reader's learning path

Where does this reader come across?

There's a big difference for the best expression of `Z` bettwen a reader came from `X` and `Y`.

## Inspire by commonly asked questions

## Inspire by inspirational questions

