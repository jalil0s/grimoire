  Return a new string, using cmap to escape each character ch
   from s as follows:
   
   If (cmap ch) is nil, append ch to the new string.
   If (cmap ch) is non-nil, append (str (cmap ch)) instead.