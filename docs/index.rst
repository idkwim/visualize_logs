.. Visualize_Logs documentation master file, created by
   sphinx-quickstart on Wed Oct 19 17:04:42 2016.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

==========================================
Welcome to Visualize_Logs's documentation!
==========================================

This is a Python library and command line tools package used to visualize log data.  Right now this 
package supports:

* ProcMon_ CSV data

More log types will be added as time allows.

.. toctree::
   :caption: API Documentation:
   :maxdepth: 2

   modules

Gallery
-------

Here are some links to example output from the command line tools:

plotprocmoncsv
^^^^^^^^^^^^^^

Kovter:

The next two samples were identified in the following blog post: https://blog.malwarebytes.com/threat-analysis/2016/07/untangling-kovter/

SHA256: 15c237f6b74af2588b07912bf18e2734594251787871c9638104e4bf5de46589_

* `Kovter 1 Example 1`_: Processes Only (Focused)
* `Kovter 1 Example 2`_: Processes Only (All)
* `Kovter 1 Example 3`_: File Writes/Renames/Deletes (All)
* `Kovter 1 Example 4`_: Registry Write/Deletes (All)
* `Kovter 1 Example 5`_: Network (All)

SHA256: bffe7ccbcf69e7c787ff10d1dc7dbf6044bffcb13b95d851f4a735917b3a6fdf_

* `Kovter 2 Example 1`_: Processes Only (Focused)
* `Kovter 2 Example 2`_: Processes Only (All)
* `Kovter 2 Example 3`_: File Writes/Renames/Deletes (All)
* `Kovter 2 Example 4`_: Registry Write/Deletes (All)
* `Kovter 2 Example 5`_: Network (All)

Ransomware: 

SHA256: 9b462800f1bef019d7ec00098682d3ea7fc60e6721555f616399228e4e3ad122_

* `Ransomware Example 1`_: Processes Only (Focused)
* `Ransomware Example 2`_: Processes Only (All)
* `Ransomware Example 3`_: Processes and Network (All)
* `Ransomware Example 4`_: File Writes/Renames/Deletes (Focused)
* `Ransomware Example 5`_: File Writes/Renames/Deletes (All)
* `Ransomware Example 6`_: Registry Writes and Deletes (Focused)

wwwlgoogle dot com Adware:

SHA256: e64910e3549a6c6e01be814b40e0f1fca02db45d5d19e2882a90914cef1c799e_

* `wwwlgoogle Example 1`_: Processes Only (Focused)
* `wwwlgoogle Example 2`_: Processes Only (All) 
* `wwwlgoogle Example 3`_: Processes and Network (Focused)
* `wwwlgoogle Example 4`_: Processes and Network (All)
* `wwwlgoogle Example 5`_: File Writes/Renames/Deletes (Focused)
* `wwwlgoogle Example 6`_: File Writes/Renames/Deletes (All)
* `wwwlgoogle Example 7`_: Registry Writes and Deletes (Focused)

.. _ProcMon: https://technet.microsoft.com/en-us/sysinternals/processmonitor.aspx
.. _15c237f6b74af2588b07912bf18e2734594251787871c9638104e4bf5de46589: https://www.virustotal.com/en/file/15c237f6b74af2588b07912bf18e2734594251787871c9638104e4bf5de46589/analysis/
.. _Kovter 1 Example 1: https://keithjjones.github.io/visualize_logs.github.io/gallery/procmoncsv/kovter1_example1.html
.. _Kovter 1 Example 2: https://keithjjones.github.io/visualize_logs.github.io/gallery/procmoncsv/kovter1_example2.html
.. _Kovter 1 Example 3: https://keithjjones.github.io/visualize_logs.github.io/gallery/procmoncsv/kovter1_example3.html
.. _Kovter 1 Example 4: https://keithjjones.github.io/visualize_logs.github.io/gallery/procmoncsv/kovter1_example4.html
.. _Kovter 1 Example 5: https://keithjjones.github.io/visualize_logs.github.io/gallery/procmoncsv/kovter1_example5.html
.. _bffe7ccbcf69e7c787ff10d1dc7dbf6044bffcb13b95d851f4a735917b3a6fdf: https://www.virustotal.com/en/file/bffe7ccbcf69e7c787ff10d1dc7dbf6044bffcb13b95d851f4a735917b3a6fdf/analysis/
.. _Kovter 2 Example 1: https://keithjjones.github.io/visualize_logs.github.io/gallery/procmoncsv/kovter2_example1.html
.. _Kovter 2 Example 2: https://keithjjones.github.io/visualize_logs.github.io/gallery/procmoncsv/kovter2_example2.html
.. _Kovter 2 Example 3: https://keithjjones.github.io/visualize_logs.github.io/gallery/procmoncsv/kovter2_example3.html
.. _Kovter 2 Example 4: https://keithjjones.github.io/visualize_logs.github.io/gallery/procmoncsv/kovter2_example4.html
.. _Kovter 2 Example 5: https://keithjjones.github.io/visualize_logs.github.io/gallery/procmoncsv/kovter2_example5.html
.. _9b462800f1bef019d7ec00098682d3ea7fc60e6721555f616399228e4e3ad122: https://www.virustotal.com/en/file/9b462800f1bef019d7ec00098682d3ea7fc60e6721555f616399228e4e3ad122/analysis/
.. _Ransomware Example 1: https://keithjjones.github.io/visualize_logs.github.io/gallery/procmoncsv/ransomware_example1.html
.. _Ransomware Example 2: https://keithjjones.github.io/visualize_logs.github.io/gallery/procmoncsv/ransomware_example2.html
.. _Ransomware Example 3: https://keithjjones.github.io/visualize_logs.github.io/gallery/procmoncsv/ransomware_example3.html
.. _Ransomware Example 4: https://keithjjones.github.io/visualize_logs.github.io/gallery/procmoncsv/ransomware_example4.html
.. _Ransomware Example 5: https://keithjjones.github.io/visualize_logs.github.io/gallery/procmoncsv/ransomware_example5.html
.. _Ransomware Example 6: https://keithjjones.github.io/visualize_logs.github.io/gallery/procmoncsv/ransomware_example5.html
.. _e64910e3549a6c6e01be814b40e0f1fca02db45d5d19e2882a90914cef1c799e: https://www.virustotal.com/en/file/e64910e3549a6c6e01be814b40e0f1fca02db45d5d19e2882a90914cef1c799e/analysis/
.. _wwwlgoogle Example 1: https://keithjjones.github.io/visualize_logs.github.io/gallery/procmoncsv/wwwlgoogle_example1.html
.. _wwwlgoogle Example 2: https://keithjjones.github.io/visualize_logs.github.io/gallery/procmoncsv/wwwlgoogle_example2.html
.. _wwwlgoogle Example 3: https://keithjjones.github.io/visualize_logs.github.io/gallery/procmoncsv/wwwlgoogle_example3.html
.. _wwwlgoogle Example 4: https://keithjjones.github.io/visualize_logs.github.io/gallery/procmoncsv/wwwlgoogle_example4.html
.. _wwwlgoogle Example 5: https://keithjjones.github.io/visualize_logs.github.io/gallery/procmoncsv/wwwlgoogle_example5.html
.. _wwwlgoogle Example 6: https://keithjjones.github.io/visualize_logs.github.io/gallery/procmoncsv/wwwlgoogle_example6.html
.. _wwwlgoogle Example 7: https://keithjjones.github.io/visualize_logs.github.io/gallery/procmoncsv/wwwlgoogle_example7.html

Index and Tables
----------------

* :ref:`genindex`
* :ref:`modindex`
* :ref:`search`

