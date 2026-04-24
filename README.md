# Website Repo for DataWave Project
Put together by Marshall Borrus + Niku Darafshi

## Website creation

The site was originally compiled locally on my computer (with Hugo), and was uploaded to Github as files were updated. The website is recompiled at Datawaveproject.github.io every time a file is pushed to the repisitory thanks to some handy internet guides which use a public workflow file to run Hugo online. 

## Website editing

To edit files on the website, you can clone the repository to your local drive, or edit the files using the online editing interface. Email Aditi_Sheshadri@stanford.edu for editing permisions. 

## To Post a Job
1. Navigate to DataWaveProject.github.io/content/Jobs/
2. Navigate to ./images/ 
a. Upload a square logo of the institution to the /images/ folder if none exists
b. Copy the file name if one already exists (ex: Rice_Square.png)
3. Navigate back to ./Jobs/ and 
a. upload any .pdf files you have
b. create a new file (top right of web page) with a name ending in .md
4. Use template: 
```
---
title: "## Position ## at ##University##"
date: 2021-03-15 ##Change to todays date for indexing## 
featured: true
draft: false
weight: 1
location: "##CITY/STATE##, ##COUNTRY##"
featured_image:: "/images/cover/<#Your image here#>.png"
---
{{< rawhtml >}}
<div>
<img src="/Jobs/images/<#Your image here#>.png" alt="University Logo" style="float:left;width:25%;height:25%;padding:0 25px 0 0;">
<h2> Advisor: <#Your Lead here#> </h2>                                           
<!-- ![logo](/images/cover/<#Your image here#>.png) -->
<a href="/pdfs/<#Your pdf here#>.png">PDF Here</a>

<p> summary of your job description to be shared as a blurb on other pages </p>
</div> 
{{< /rawhtml >}}
<!--more-->

More extensive description of job which can be written in markdown, as opposed to the lines above, which are in HTML
```
5. Commit changes (publish) and a github pages routine will finish in the background, recompling the site and uploading your new page within a few minutes. If you don't see your new page in 6-7 minutes, clear your cache and cookies and re-load the Datawave page. 
