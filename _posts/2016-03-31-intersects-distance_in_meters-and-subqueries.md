---
layout: changelog
title: intersects(...), distance_in_meters(...), and sub-queries 
short_title: intersects(...), distance_in_meters(...), and sub-queries 
category: changelog
date: 2016-03-31
parent_paths: 
- /changelog/
parents: 
- API Changelog
---

We're excited to announce that we're making three new features of our SoQL query language public:

- The [`intersects(...)`](/docs/functions/intersects.html) function allows you to determine whether two geospatial datatypes overlap with each other. It can be used to determine what police district a given point is within, what school districts are served by by a given bus route, or census districts cover a particular neighborhood.
- The [`distance_in_meters(...)`](/docs/functions/distance_in_meters.html) function returns the distance between two Points in meters. It can be used to determine how far you are from a given location, or order results by distance.
- Our powerful new [sub-query](/docs/queries/query.html#sub-queries) support allows you to further refine the results of a `$query` by chaining multiple queries together.

We're excited to see how people make use of these new features! If you have any questions or issues, or even if you just want to share what you've built, don't be afraid to [get in touch with us](/support.html).


