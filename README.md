## Crop Rotation Analysis in Uruguay: data analysis for the SABio research group

Project in which I performed an intense process of data cleaning and standardization. The data presented values of the crop rotation processes in Uruguay, however, it presented uneven values, with variation in the way the data was entered in more than 65,000 entries. The data have different values and dimensions, occupy different columns, and sometimes have significant NA between crops (*the empty value between crops is meaningful in the rotation process*, being considered one crop rotation strategy)- in one single string. It will allow us to clearly visualize the rotation as a sequence - even when they have different lengths.
For the data treatment I used the text analysis package `quanteda` and for the data analysis the `tidyverse`

After this, I analyzed the most common processes according to the most common rotation, tolerance level, localization, land-owning status, among others, performing different data analysis processes according to the interests of the research group.

![](https://github.com/rennnas/Crop-Analysis-Uruguay/blob/main/imagem%20uruguay%202.png)
