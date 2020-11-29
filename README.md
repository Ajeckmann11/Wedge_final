# Wedge_final

Finished the wedge. Talked about it in the "recap" in submission md, but I downgraded to a B here because I could not figure out how to do the part for A for Part 1. I will be downgrading to a B in the class as long as that's okay with you. I know I made a lot of this way harder on you by completing this so late and I am very sorry for that. Hopefully the A&A that I did (that would not be required for a B), will help make up for this hassle caused by the tardiness on my part.

## Feedback

Nice work getting to the finish line. I felt for you with the "re-upload" files thing. I've run into that too many times to count. That's 
why you'll see me do things like write some "helper" code that cleans out my destination table before writing (if that's appropriate to the 
application). Ultimately the results look quite close. 

In part 2, you write your query like this: 
`query_card_nos = "Select Distinct card_no," "From `wedgeproject-290522.wedge.transArchive*`" "Where card_no !=3"`

Consider doing something more like this: 
```
query_card_nos = """ SELECT DISTINCT card_no
                     FROM `wedgeproject-290522.wedge.transArchive*`
                     WHERE card_no != 3
                 """
```
That's considered much easier to read and maintain. (The way you write it in Part 3, as a series
of strings with single quotes on each line, is totally fine too. For some reason I find 
that one a smidge more difficult to work with in my own code, perhaps because of those
niggling spaces at the end of the line.) All the rest of that section looks good. 

Everything in Part 3 looks good. You might consider _slightly_ terser names for your 
tables, `prod_year_month` instead of `sales_by_product_description_by_year_by_month`, for instance. 

Nice job getting to the finish line!

