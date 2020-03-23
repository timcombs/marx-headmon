notes to workflow and actions - brainstorming - scratchpad

have png of marx headmon
have quotations to appear as text on screen
pick random index number
check if number has been used
  if it has been used then pick new number
  if not used then select quotation by index number
add number to doNotUse array(?)
make png from words from quotation and original png
  determine maximum width of line - based on font size
  determine where to place on png
  grab each word
    split string into array of strings, delimiter a space
    if word contains a dash split on dash, but add dash back to end of 1st word
  place word in row in sentence order
  add space after word unless last character a dash
  once word overlayed on png save png to folder
  continue with next word
  when row filled jump to next row & continue
take pngs and turn them into a gif
  each layer lasts for 150ms
  last layer persists for 400ms
upload gif to wherever.....

maybe just create the original png as the persistent beginning layer
each placed word is a new transparent png layer