# Lab Manual #6: Java Javadoc Documentation & Code Re-formatting

- **Course:** Software Development and Documentation Lab
- **Instructor:** Dr. Ala Abuthawabeh
- **Student:** Yousef Roshdy Yousef Yousef (202310741)

## Overview
This repository contains the reformatted and fully documented `SortExample` Java class along with its generated HTML Javadoc documentation for Lab Manual #6.

## Implemented Improvements
- **Code Layout & Styling:** Applied standard 4-space indentation, consistent brace alignment, and proper whitespace conventions.
- **Javadoc Documentation:** Converted informal inline comments into structured Javadoc blocks (`/** ... */`) at both class and method levels.
- **Metadata & Tags:** Added `@author` and `@version` class tags, plus `@param` and `@return` tags for `main`, `quickSort`, `swap`, `mergeSort`, `merge`, and `isSorted`.
- **HTML Documentation Generation:** Generated full API documentation including private members in `docOutput/`.

## Project Structure
- `src/SortExample.java` — Reformatted and Javadoc-documented source code.
- `docOutput/` — Generated HTML Javadoc documentation (`docOutput/index.html`).

## Compilation & Documentation Commands
```bash
javac src/SortExample.java
java -cp src SortExample
javadoc -private -author -version -d docOutput src/*.java