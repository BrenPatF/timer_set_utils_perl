# timer_set_utils_perl

Author:         Brendan Furey
Date:           31 July 2016 (github)

This project contains two Perl utility packages that I wrote in 2010, a timer set class that I wrote in several languages, and published as a word document on scribd, and a general utility package (mainly pretty printing).

See 'Code Timing and Object Orientation and Zombies', Created: 22 November 2010, Updated: 25 September 2012
    https://www.scribd.com/document/43588788/Code-Timing-and-Object-Orientation-and-Zombies

The usage of the packages can be seen from a program in a separate github project, dir_tree_perl, that traverses a file system directory (MS Windows, in this version), and lists the file hierarchy with various details such as file sizes and dates.

Here is an extract from its output - full file is available in the dir_tree_perl root directory.
<pre>
Timer Set: Tree - C:/Users/Brend_000/Documents/Home - HP/Music SD/4 Classical/Beethoven, constructed at 31/07/16 13:42:54, written at 13:42:55
==============================================================================================================================================
[Timer timed: Elapsed (per call): 0.02 (0.000002), CPU (per call): 0.03 (0.000003), calls: 10000, '***' denotes corrected line below]

Timer                         Elapsed          CPU       = User     + System        Calls        Ela/Call        CPU/Call
------------------------   ----------   ----------   ----------   ----------   ----------   -------------   -------------
Contructor                       0.90         0.22         0.05         0.17            1         0.90366         0.21900
Pre Tree (All)                   0.00         0.00         0.00         0.00            1         0.00105         0.00000
Headings (All)                   0.00         0.00         0.00         0.00            1         0.00013         0.00000
Directory Printing (All)         0.00         0.00         0.00         0.00          108         0.00002         0.00000
File Sort (All)                  0.00         0.00         0.00         0.00          108         0.00004         0.00000
File Printing (All)              0.00         0.00         0.00         0.00          108         0.00003         0.00000
Directory Sort (All)             0.00         0.00         0.00         0.00          107         0.00000         0.00000
(Other)                          0.03         0.03         0.03         0.00            1         0.02757         0.03100
------------------------   ----------   ----------   ----------   ----------   ----------   -------------   -------------
Totals                           0.94         0.25         0.08         0.17          435         0.00217         0.00057
------------------------   ----------   ----------   ----------   ----------   ----------   -------------   -------------
</pre>

Pre-requisites
==============

Perl 5