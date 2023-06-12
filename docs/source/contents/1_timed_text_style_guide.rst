Timed Text Style Guide
======================

1.0 About
---------

This document describes UTK Libraries' style guide for creating closed captions and subtitle files for audio and video.
It is largely informed by the `Netflix Timed Text Style Guide: General Requirements <https://partnerhelp.netflixstudios.com/hc/en-us/articles/215758617-Timed-Text-Style-Guide-General-Requirements>`_.

2.0 Duration
------------

The duration of a subtitle event should be between 5/6 (five-sixths) of a second (e.g. 20 frames for 24fps) and 7 seconds.

3.0 File Format
---------------

For closed captions and subtitles, use webVTT (`.vtt <https://developer.mozilla.org/en-US/docs/Web/API/WebVTT_API>`_).

4.0 Glyphs
----------

Only text or characters included in the `NETFLIX Glyph List <https://backlothelp.netflix.com/hc/en-us/articles/215581437-Netflix-Accepted-Glyph-List>`_ can be used.

5.0 Line Treatment
------------------

=================
5.1 General Rules
=================

Text should usually be kept to one line, unless it exceeds the character limitation. Text should never exceed 2 lines.

========================
5.2 Character Limitation
========================

Lines should never exceed 42 characters. This includes spaces and punctuation.

=====================
5.3 Rules for 2 Lines
=====================

When a subtitle event exceeds the character limitation defined above, it should be broken into two lines. This section
describes the rules for breaking a subtitle event into two lines.

============================
5.3.1 Basic Line Break Rules
============================

The first line should be broken at a specific point rather than at the character limit. Valid break points include:

* after punctuation marks
* before conjunctions
* before prepositions

==============================
5.3.2 Nuanced Line Break Rules
==============================

A line break should not separate:

* a noun from an article
* a noun from an adjective
* a first name from a last name
* a verb from a subject pronoun
* a prepositional verb from its preposition (e.g. agree with, approve of)
* a verb from an auxiliary (e.g. have been), reflexive pronoun (e.g taught myself) or negation (e.g. hardly ever, does not)
