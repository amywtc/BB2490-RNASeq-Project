Amy's Diary

17/2/2016

Today we had the first meeting for our project. Hugi suggested us to use Github and PyCharm as the programming tool for this project.
We all agreed to him. Using Github, all group members can share and edit the codes without messing them. Sometimes, we do not know 
which one is most updated version and Github can help us solve this problem. We scheduled several meetings afterhand so that we can 
discuss and exchange ideas. This is the first time for both Tobias and me to deal with Github, Hugi was really nice that he gave us 
a small tutorial about Github (pull and push request). This is also my first time dealing with programming, hopefully, I can make it
and I believe I can learn many programming skills in this project.

18/2/2016

We had the project instuction from Olof, and the following is the brief summary of our project.

Title:The effect of subsampling of large RNA-seq data sets on gene expression analysis

Objective: 
1. To find differentially expressed (DE) genes between inflammatory and noninflammatory human blood
2. Investigate the allelic bias for the individual samples
           
Data: Blood samples from 8 individuals, 2 samples per individual. For each individual, one part of each sample was treated by LPS and
one part was left untreated, thus resulting in 16 samples. 8 samples treated with lipopolysaccharides (LPS) and 8 untreated in order to get an inflammatory response.
      
Hypothesis: Deep sequencing impairs the finding of the DE genes.

Random sub samplings will be performed where only ~30-75% of the total data will be used in order to see how it affects the results.

19/2/2016

We had meeting with Olof. TO reduce the memory and computational time required for mapping, we will only deal with three individuals but not 8. What we have to do before mapping to reference genome is to remove the adaptor from reads and check the quality of the reads so that we can remove the one with poor quality. We have little discussion about how to do subsampling and the idea is the sampling should be carried out after processing but before mapping.

23/2/2016

We had the data from Olof and started to look into and get familiar with them. Hugi and Sailendra came up with an idea how to do subsampling. We use the lane 1 from both flow cells, followed by lane 1 and 2, then 1,2,3 and finally all lanes. This allows us to perform and compare the result of using 25%, 50%, 75% and 100% of data.

25/2/2016

We ran TrimGalore with our data to autodetect and remove the adapters from the reads. It seems that it could remove some overrepresented kmer sequence at the end of the reads.

4/3/2016

We ran the remaining files today. After discussion, we came up the subsampling idea, that is 



