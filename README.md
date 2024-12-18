# Introduction
RDU (Remove Duplicate URLs) is a lightweight command-line tool designed to efficiently remove duplicate URLs and URLs of the same category. It simplifies URL management, ensuring you only work with unique and relevant links.

# Features

Remove Duplicate URLs: Automatically detects and removes exact duplicates.

Category Filtering: Identifies URLs of the same category (e.g., domain-level similarity) and removes duplicates based on rules.

Efficient and Fast: Handles large URL lists with ease.

Simple Command-Line Interface: Easy to integrate into your workflow.

# Why Choose RDU Tool?

In the world of duplicate URL management, many tools require installation via complex ecosystems like brew, Go, or even pip. While these solutions work, they often introduce compatibility issues, dependency conflicts, and environmental constraints. RDU Tool takes a different approach, offering a simple, robust, and reliable solution designed to work seamlessly in any Unix-like environment.

Built Entirely in Bash

RDU Tool is completely written in Bash, making it lightweight, portable, and independent of any programming language or package manager. Here’s why that matters:

1.No Dependency Nightmares:
Tools installed via pip can lead to Python environment conflicts, especially when working on systems where multiple projects require different Python versions or dependencies. With RDU Tool, all you need is Bash, which is available on nearly every Unix-based system by default.

2. Cross-Platform Compatibility:
Unlike Go or other language-specific tools, RDU runs directly in the terminal without requiring additional installations or runtime configurations. If Bash is installed (which it almost always is), RDU works flawlessly.

3. Error-Free Operation:
Dependency managers like brew or pip sometimes fail due to missing libraries, outdated systems, or restricted environments. RDU bypasses all of these hurdles, ensuring reliable operation without external interference.

4. Simple Setup:
There’s no need for compilers, package managers, or virtual environments.

5. Universal Usability:
Whether you’re working on Linux, macOS, or even Windows with WSL, RDU runs seamlessly. No extra tools, no extra hassle.

# Usage

You can use RDU Tool to remove duplicate URLs directly from your terminal. It works seamlessly with pipelines for quick and efficient URL filtering.

Basic Example

Use the following command to process URLs from a file:

```
cat urls.txt | rdu
```

Input File (urls.txt):

https://example.com
https://example.com
https://test.com/page=1
https://test.com/page=2
https://test.com/profile=1
https://example.com/page
https://sub.example.com

Output:

https://example.com
https://test.com/page=1
https://test.com/profile=1
https://example.com/page
https://sub.example.com

# Onliner Installation : 

```bash
wget https://raw.githubusercontent.com/D3fu1t/RDU/refs/heads/main/rdu;chmod +x rdu;mv rdu /usr/bin
```
## License  

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.


