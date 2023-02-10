# minecraftBlockSpeeds
Something to help me optimize an old hobby I'm revisiting. 

If I continue to develop this in the future, I'll add:
 - [x] Calculating the time taken from minecraft's formula instead of this table
 - [ ] Separate the javascript, html, and css into their own files and import it
 - [ ] Way to remove a single entry
 - [ ] Button to remove all entries
 - [ ] Storing the results to a file to eventually come up with the overall best ores for each mine
      - Using a CRUD form to add these results?
 - [ ] Replace the table with one that updates based on the efficiency level selected
 - [ ] Be able to click a table value to select it and give a sell price

Heads up, I decided it was more important to know the 
average block mining speed, and a little known fact is 
that minecraft adds an extra 0.3 seconds after mining 
each block, unless you can mine it within a single frame.

These speeds are for the general profit you can make from
mining each ore, given the price they sell at. If you want
the exact time to break a single block, subtract 0.3 if your
time is greater than 0.05.

If I ever finish that list, then maybe I'll make a guide of the best way to progress through each mine.
