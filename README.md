# Computational Rarity Team

“Tape that is not digitized by 2025 will in most cases be lost forever” - NFSA, 2017

## Problem Statement (Alexis Bhagat, 2023)

This study focuses on musical collections on tape held in small repositories, including arts organizations, publishers, radio stations, and individual collectors. How can we identify tapes in these small collections which have not as yet been digitally preserved? Identifying compositions and publications which were later published on an optical media format is one reliable indication that the item has been digitized. This study will create a tool to query two popular online music databases – Musicbrains and Discogs – with metadata from a collection of 160 audiocassettes in the collection of artist/writer, Richard Kostelanetz. These queries will provide evidence of the existence, or absence, of commercially published versions of the recordings in the collection. Identifying tapes which have not been commercially published provides an objective measurement of rarity that can assist custodians in difficult preservation decisions.

## The Tool

CSV of Releases -> Batch API Queries -> CSV of Matches

Created in Flask, with Python API libraries and Jinja templates.