---
title: Group theoretical approach to computing phonons and their interactions
authors:
  - Lyuwen Fu
  - Mordechai Kornbluth
  - admin
  - Chris A Marianetti
date: "2019-01-01"
publishDate: "2024-05-24T20:48:51.491927Z"
publication_types:
  - article-journal
publication: "*Physical Review B*"
abstract: "Phonons and their interactions are necessary for determining a wide range of materials properties. Here we present four independent advances which facilitate the computation of phonons and their interactions from ﬁrst principles. First, we implement a group-theoretical approach to construct the order N Taylor series of a d-dimensional crystal purely in terms of space group irreducible derivatives (ID), which guarantees symmetry by construction and allows for a practical means of communicating and storing phonons and their interactions. Second, we prove that the smallest possible supercell which accommodates N given wave vectors in a d-dimensional crystal is determined using the Smith normal form of the matrix formed from the corresponding wave vectors; resulting in negligible computational cost to ﬁnd said supercell, in addition to providing the maximum required multiplicity for uniform supercells at arbitrary N and d. Third, we develop a series of ﬁnite displacement methodologies to compute phonons and their interactions which exploit the ﬁrst two developments: lone and bundled irreducible derivative (LID and BID) approaches. LID computes a single ID, or as few as possible, at a time in the smallest supercell possible, while BID exploits perturbative derivatives for some order less than N (e.g., Hellman-Feynman forces) in order to extract all ID in the smallest possible supercells using the fewest possible computations. Finally, we derive an equation for the order N volume derivatives of the phonons in terms of the order N = N + 2 ID. Given that the former are easily computed, they can be used as a stringent, inﬁnite ranged test of the ID. Our general framework is illustrated on graphene, yielding irreducible phonon interactions to ﬁfth order. Additionally, we provide a cost analysis for the rocksalt structure at N = 3, demonstrating a massive speedup compared to popular ﬁnite displacement methods in the literature."
---
