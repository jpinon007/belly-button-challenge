# belly-button-challenge

# Background : In this assignment, I was asked to build an interactive dashboard to explore the Belly Button Biodiversity dataset.

# Solution: To complete this challenge, I used the D3 library to read in the samples.json from the URL. I also used my instructor's repo solution as reference to check my code and work  https://git.bootcampcontent.com/Northwestern-University/NU-VIRT-DATA-PT-06-2024-U-LOLC.git

# Bar chart: I created a horizontal bar chart with a dropdown menu to display the top 10 OTUs in the respective individual. The values used for the bar chart were sample-value. Labels used were otu_ids, and the hovertext for the chart were the otu_labels. 

# Bubble chart: I created a bubble chart that displayed each sample; otu_ids as x-values, sample_values as y-values, sample values for the marker size, out_ids as marker colors, and otu_labels for the text values.

# Metadata sample display: I was asked to display an individual's demographic information. To display the info needed, it loops through each key-value pair from the metadata JSON object and creates a text string. I appended an html tag with that text to the sample metadata panel. 

# Update plots: All plots are updated when a new sample is selected. The app was then deployed to a static page hosting service. 