---
title: 2022-01-01
date: 2022-01-01
menu:
  sidebar:
    name: 2022-01-01
    identifier: 2022-01-01
    parent: IBS
    weight: 21
tags: ["Series", "IBS"]
categories: ["Series-IBS"]

---


<span class="firstcharacter">T</span>his is in continuation with the previous post. We are going to look at how the data sample is done and what could cause variation in it.
</br>
</p>
</br>
</p>
 
### 1.2. Data, Sampling, and Variation in Data and Sampling

As mentioned earlier, it is generally not feasible to collect data from entire population. Data can be collected from "Sample" inside the population. But the statistician has to make sure that the sample covers all the variations in the population.

{{< img src="pop_sample.jpeg" width="50%" align="center" title="Data Table" >}}

##### 1.2.1. Types of Data

{{< img src="data_table.jpeg" width="50%" align="center" title="Data Table" >}}

Most data can be put into the following categories:
- **Qualitative:** Often called as Categorical data. The values generally are in Strings and show some sort of quality of the Variable. As shown in the second column "Color". The values are the names of the colours which define the color of that body part.
- **Quantitative:** This will always be a number. All the calculations are done on this category. It is further divided into two parts depending on whether you are counting or measuring-
    - **Discrete:** All data that are the result of counting are called Quantitative Discrete Data. It is always a whole number.
    - **Continuous:** Data that may include fractions, decimals or irrational numbers are called Quantitative Continuous Data. It is often due to the measurements like lengths, weights or times.


##### 1.2.2. Sampling

{{< alert type="warning" >}}
A <b><u>sample</b></u> should have the same characteristics as the <b>population</b> it is representing.
{{< /alert >}}

Statisticians use various methods of random sampling to achieve this. There are several different methods of **random sampling.** True random sampling is done with replacement. That is, once a member is picked, that member goes back into the population and thus may be chosen more than once. However for practical reasons, in most populations, simple random sampling is done without replacement. Surveys are typically done without replacement. That is, a member of the population may be chosen only once.

- <u>**Simple Random Sample:**</u> Any group of _n_ individuals is equally likely to be chosen as any other group of _n_ individuals.

- <u>**Stratified Sample:**</u> To choose a stratified sample, divide the population into groups called strata and then take a proportionate number from each stratum. For example, you could stratify (group) your college population by department and then choose a proportionate simple random sample from each stratum (each department) to get a stratified random sample. 
    {{< img src="strata.jpeg" width="50%" align="center" title="Strata" >}}

- <u>**Cluster Sample:**</u> Divide the population into clusters (groups) and then randomly select some of the clusters.
    {{< img src="cluster.jpeg" width="20%" align="center" title="Cluster" >}}

- <u>**Systematic Sample:**</u> Randomly select a starting point and take every nth piece of data from a listing of the population.


**Non Random Sampling:**
- <u>**Convenience Sampling:**</u> It is a non random sampling. This type of sampling involves using results that are readily available. Sampling data should be done very carefully with Convenience Sampling. Collecting data carelessly can have devastating results.


When you analyze data, it is important to be aware of sampling errors and non-sampling errors. The actual process of sampling causes sampling errors. A sampling bias is created when a sample is collected from a population and some members of the population are not as likely to be chosen as others.


##### 1.2.3. Variation in Data

Variation is always present in any real life data. If two or more samples from the same population are taken randomly and having almost same characteristics of the population will still be different from each other in real life. 


-------------------------------------------------------------------------------------
<style>
body {
text-align: justify
}
</style>

<style>
.firstcharacter {
  color: #903;
  float: left;
  font-family: Georgia;
  font-size: 75px;
  line-height: 60px;
  padding-top: 4px;
  padding-right: 8px;
  padding-left: 3px;
}
</style>

<style>
.comment {
  color: #999999;
  float: left;
  font-size: 12px;
  font-style: italic;
}
</style>
