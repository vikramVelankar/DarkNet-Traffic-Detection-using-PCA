#DARK-NET TRAFFIC DETECTION USING PCA

This is a group Project done to classify the incoming dark-net traffic to malicious or not. We used PCA(principle component analysis) to shrink down the dataset for converting components to classify the traffic. Here we on purpose ARP poisoned the network to generate fake malicious traffic.

We first collected some raw data of browsing over dark-net and then we ARP poisoned the network to generate the fake traffic. Later the collected dataset was the stored as civ file and imported to .ipynb.

Once we received the dataset we shrunk down the dimensions of the dataset to x and y axis and later plotted them against each other to get a proper classification graph.

The accuracy that our model had was 87%.