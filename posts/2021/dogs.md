---
title: dogs
description: This is a post on My Blog about agile frameworks.
date: 2021-01-06
tags:
  - animals
  - misc
layout: layouts/post.njk
---
[![Netlify Status](https://api.netlify.com/api/v1/badges/00c3f250-b036-416d-92c0-5ac806a4df46/deploy-status)](https://app.netlify.com/sites/mystifying-mestorf-c41a15/deploys)


## Section Header

Capitalize on low hanging fruit to identify a ballpark value added activity to beta test. Override the digital divide with additional clickthroughs from DevOps. Nanotechnology immersion along the information highway will close the loop on focusing solely on the bottom line.

``` text/2-3
var rows = prompt("How many rows for your multiplication table?");
    var cols = prompt("How many columns for your multiplication table?");
    if(rows == "" || rows == null)
   		 rows = 10;
    if(cols== "" || cols== null)
   		 cols = 10;
    createTable(rows, cols);
    function createTable(rows, cols)
    {
      var j=1;
      var output = "<table border='1' width='500' cellspacing='0'cellpadding='5'>";
      for(i=1;i<=rows;i++)
      {
    	output = output + "<tr>";
        while(j<=cols)
        {
  		  output = output + "<td>" + i*j + "</td>";
   		  j = j+1;
   		}
   		 output = output + "</tr>";
   		 j = 1;
    }
    output = output + "</table>";
    document.write(output);
    }
```
