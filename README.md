<a name="readme-top"></a>

<br/>

<div align="center">

<h1>Adaptive Knowledge Organization System (AKOS)</h1>

<p>
  A flexible, hierarchical system for efficient knowledge organization and retrieval.
</p>

[Changelog][changelog-link] · [Report Bug][github-issues-link] · [Request Feature][github-issues-link]

</div>

<br/>

## Table of Contents

- [Introduction](#introduction)
- [Specification](#specification)
- [Examples](#examples)
- [Contributing](#contributing--development)
- [Changelog](#changelog)
- [License](#license)

## Introduction

The Adaptive Knowledge Organization System (AKOS) is a hierarchical framework designed to categorize and structure knowledge across various fields and disciplines. By introducing a flexible, hierarchical framework, AKOS aims to improve organization, navigation, and accessibility of information, making it an invaluable tool for educators, students, researchers, and professionals alike.

<div align="right">
  
[![][back-to-top]](#readme-top)

</div>

## Specification

**Current Version: 0.1.0**

AKOS structures knowledge through a five-level hierarchy, enabling users to navigate from broad concepts to specific details efficiently:

- **Domain:** The broadest categorization, representing overarching areas of knowledge (e.g., Sciences, Technologies, Arts).
- **Discipline:** Specific fields of study within a Domain (e.g., Computer Science within Technologies).
- **Subject:** Detailed areas within a Discipline, focusing on particular aspects or methodologies (e.g., Algorithms within Computer Science).
- **Topic:** Core concepts or themes within a Subject (e.g., Graph Algorithms within Algorithms).
- **Subtopic:** Specific elements or detailed aspects within a Topic, which can recursively contain other Subtopics for in-depth exploration (e.g., Traversal Algorithms within Graph Algorithms).

### Directory Structure Convention

To maintain a well-organized tree, it is recommended that a directory should only contain other directories or files, but not both. The exception to this rule is for hidden or "dotfiles" and configuration files. This convention helps to distinguish branches, which represent the categorical/navigable part of the tree, from leaves, which represent the knowledge or terminal points.

This layered approach aims to achieve the right balance of structure and flexibility, facilitating a comprehensive categorical overview while readily adapting to the myriad ways knowledge can be segmented and explored.

<div align="right">
  
[![][back-to-top]](#readme-top)

</div>

## Examples

To demonstrate AKOS's method of organization, we begin with an example from the Technologies domain, specifically within Computer Science. This showcases the system's ability to deconstruct complex disciplines into interconnected, manageable knowledge layers:

- **Domain:** Technologies
- **Discipline:** Computer Science
- **Subject:** Algorithms
- **Topic:** Graph Algorithms
- **Subtopic:** Traversal Algorithms
  - **Detailed Subtopic:** Depth-First Search (DFS), Breadth-First Search (BFS)

Expanding on this, we also present examples from the domains of Arts & Humanities and Sciences. These examples illustrate the practical application of a file system hierarchy for organizing notes, where directories and markdown files represent broader categories and specific topics, respectively:

```
.
├── Arts_Humanities
│  └── Music_Theory
│     └── Harmony
│        └── Chord_Progressions
│           └── Jazz_Harmony
│              ├── Advanced_Techniques.md
│              └── Basic_Chord_Progressions.md
├── Sciences
│  └── Mathematics
│     └── Pure_Mathematics
│        └── Algebra
│           └── Group_Theory
│              ├── Definitions_and_Examples.md
│              └── Fundamental_Theorems.md
└── Technologies
   └── Computer_Science
      └── Algorithms
         └── Graph_Algorithms
            └── Traversal_Algorithms
               ├── Breadth-First_Search_BFS.md
               └── Depth-First_Search_DFS.md
```

<div align="right">
  
[![][back-to-top]](#readme-top)

</div>

## Contributing & Development

We welcome contributions! Please see the [Contributing Guide][contributing-guide] for more information.

### Thank you to our contributors ❤️

[![][contributors-contrib]][contributors-link]

<div align="right">
  
[![][back-to-top]](#readme-top)

</div>

## Changelog

For a detailed account of all notable changes to the project, see the [CHANGELOG.md](CHANGELOG.md) file.

## License

This project is released under the [MIT](./LICENSE) License. © 2024-Present phi school

<div align="right">
  
[![][back-to-top]](#readme-top)

</div>

[back-to-top]: https://img.shields.io/badge/-⇧_Back_To_Top-black?style=flat-square
[changelog-link]: ./CHAGNELOG.md
[contributing-guide]: ./CONTRIBUTING.md
[contributors-contrib]: https://contrib.rocks/image?repo=phi-school/akos
[contributors-link]: https://github.com/phi-school/akos/graphs/contributors
[github-issues-link]: https://github.com/phi-school/akos/issues
[license]: ./LICENSE
