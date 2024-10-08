# Datasheet Template

As far as you can, complete the model datasheet. If you have got the data from the internet, you may not have all the information you need, but make sure you include all the information you do have. 

## Motivation

- For what purpose was the dataset created? 

 The dataset is a commercial list of wines made available to Hedonism's customers.
 
- Who created the dataset (e.g., which team, research group) and on behalf of which entity (e.g., company, institution, organization)? Who funded the creation of the dataset?

hedonism wine store.
 
## Composition

- What do the instances that comprise the dataset represent (e.g., documents, photos, people, countries)? 

The instances in the dataset represent items sold by hedonism, typically wine and spirits but also glassware.

- How many instances of each type are there? 

The dataset contains a total of 7k+ instances.

- Is there any missing data?

No.


- Does the dataset contain data that might be considered confidential (e.g., data that is protected by legal privilege or by doctor–patient confidentiality, data that includes the content of individuals’ non-public communications)?

No.

## Collection process

- How was the data acquired? 

Each instance was frst physically acquired before being acquired in the file.

- If the data is a sample of a larger subset, what was the sampling strategy?

We'd have to ask the buyer, but the strategy must be to ofer an extensive set of rare and luxury drinks.
 
- Over what time frame was the data collected?

The shop opened years ago and updates the list periodicaly.


## Preprocessing/cleaning/labelling

- Was any preprocessing/cleaning/labeling of the data done (e.g., discretization or bucketing, tokenization, part-of-speech tagging, SIFT feature extraction, removal of instances, processing of missing values)? If so, please provide a description. If not, you may skip the remaining questions in this section. 

Since our focus is wine, we removed the data pertaining to Spirits and beer
or accessories (such as glasses and decanters). There were also a number of spurious commas in the csv which misaligned the columns, so we had to parse the original CSV and get rid of those.

- Was the “raw” data saved in addition to the preprocessed/cleaned/labeled data (e.g., to support unanticipated future uses)? 

 The raw data is what is available, with minimal processing.
 
 
## Uses

- What other tasks could the dataset be used for? 

 Buying a present for a friend.
 
- Is there anything about the composition of the dataset or the way it was collected and preprocessed/cleaned/labeled that might impact future uses? For example, is there anything that a dataset consumer might need to know to avoid uses that could result in unfair treatment of individuals or groups (e.g., stereotyping, quality of service issues) or other risks or harms (e.g., legal risks, financial harms)? If so, please provide a description. Is there anything a dataset consumer could do to mitigate these risks or harms? 

Some bottles can inflict serious financial harm, but no one forces you to buy.

- Are there tasks for which the dataset should not be used? If so, please provide a description.

The dataset should not be used too often for health-conscious individuals.

## Distribution

- How has the dataset already been distributed? 

hedonismc.co.uk

- Is it subject to any copyright or other intellectual property (IP) license, and/or under applicable terms of use (ToU)?  

No

## Maintenance

- Who maintains the dataset?

The shop.
