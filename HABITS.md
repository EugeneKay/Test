<!--
# HABITS.md
# EugeneKay/test
-->

Development Habits
==================

This is a series of development habits I follow to provide consistency and enable future understanding.


Documentation
-------------

Decisions are constantly made in software development, and are reflected in the code produced. Comments should be used liberally to capture this wisdom. It is suggested to headline each segment with a rationalization sentence. Complex segments should be split into smaller pieces and summarized.


Headers
-------

Every text-style file begins with a small header containing useful metadata:

 1. Shebang or comment delineator
 2. Path of the file, within the repository
 3. Project/Repository name as applicable
 4. **(Optional)** Vim modeline
 5. **(Recommended)** Human-readable explanation of the file's purpose. Generally a single sentence, but may be a Title with paragraph if complex.
 6. Spacer

```
#!/bin/bash
# foo/example.sh
# EugeneKay/Test
# 
# Example Shell Script
#
```
