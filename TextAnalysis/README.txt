Words statistic representation of any txt file. This example uses d3 tag cloud component and python matplotlib library.

TagCloud.txt - sample text for analysis (HAMLET, PRINCE OF DENMARK by William Shakespeare)


Important notes:

Analyzed text must be located at "C:\Users\beakertesting\.beaker\TagCloud.txt"(or you should modify this path manually in code)
If you want to hide some words in cloud, you should modify 'deletions' "C:\Users\beakertesting\.beaker\deletions.txt" file
If you want to hide some words in cloud, you should modify 'deletions' "C:\Users\beakertesting\.beaker\replaces.txt" file
tagCloudSize variable - the size of tag cloud
histSize variable - the count of words, which are displayed in histogram
textChunkSize variable - the count of words in one part of text, used for hist analysis