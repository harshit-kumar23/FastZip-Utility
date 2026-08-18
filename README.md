# FastZip Utility

**FastZip Utility** is a lightweight, web-based text file compression and decompression tool built with pure JavaScript, HTML5, and CSS3. It utilizes the **Huffman Coding Algorithm** to achieve lossless compression directly in the browser without sending data to external servers.

---

## Key Features

* **Lossless Compression:** Encodes text files into binary streams using frequency-based prefix codes.
* **In-Browser Processing:** Fast execution with zero server-side processing or external network requests.
* **Intuitive Web Interface:** Clean UI to upload, compress, decompress, and download files seamlessly.
* **Real-time Metrics:** Displays original file size, compressed file size, and space savings percentage.

---

## Technical Stack

* **Frontend:** HTML5, CSS3, JavaScript (ES6+)
* **Core Algorithms:** Huffman Coding Algorithm, Min-Heap / Priority Queue Data Structure

---

## Algorithmic Workflow

1. **Frequency Analysis:** Scans the input text to calculate character frequency distribution.
2. **Priority Queue Construction:** Builds a Min-Heap of nodes corresponding to character frequencies.
3. **Tree Generation:** Repeatedly merges the two lowest-frequency nodes to construct the optimal Huffman Tree.
4. **Binary Encoding:** Traverses the tree to assign prefix codes and serializes the bitstream for download.

---

## Getting Started

1. **Clone the Repository:**
   ```bash
   git clone [https://github.com/harshit-kumar23/FastZip-Utility.git](https://github.com/harshit-kumar23/FastZip-Utility.git)
   cd FastZip-Utility
