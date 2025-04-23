# Solution 
the solution is we need to find authors who viewed their article at least once in order to find id we need to filter the data where author_id needs to be equal to viewer_id, they maight viewed thier article more than once but we neet to fetch only distinct author_ids so there is a two way of that one is using distinct like select distinct author_id second is using group by.
