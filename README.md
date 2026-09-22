# Project_PackerUnpacker
A Java-based file archiving utility that packs multiple files into a single binary archive and restores them on demand — with both a console interface and a Swing GUI.

## Table of Contents

- [Technology](#technology)
- [Project Overview](#project-overview)
- [Architecture](#architecture)
- [Package Structure](#package-structure)
- [Class Reference](#class-reference)
- [How It Works](#how-it-works)
  - [Packing](#packing)
  - [Unpacking](#unpacking)
- [Known Limitations & Bugs](#known-limitations--bugs)
- [Key Features](#key-features)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Compile](#compile)
  - [Run](#run)
- [Example Usage](#example-usage)
- [GUI Screenshots](#gui-screenshots)
- [Future Scope](#future-scope)
- [Author](#author)

---

## Technology

| Layer | Technology |
|---|---|
| Language | Java (JDK 8+) |
| GUI Framework | Java Swing (AWT + Swing) |
| I/O | Java `java.io` streams |
| Build | Manual `javac` / any standard Java IDE |

---

## Project Overview

**File Packer & Unpacker** is a lightweight, dependency-free Java utility that combines multiple files from a directory into a single binary archive file, and later extracts them back — preserving file names and sizes. Think of it as a minimalist, educational implementation of concepts behind tools like `tar`.
