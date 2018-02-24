# Syria_Tor_Usage_2013

**This is an experiment where I looked to see Tor users in Syria by their 'client': Relay or Bridges.**

I used pandas.df functions to slice rows I was interested in so that I can create a list of Syria 2013 Relays 
and Syria 2013 Bridges month to month

Finally I utilized matplotlib.pyplot to help visualize the data. 


**Functions I used:**

- pd.read_excel #to read the data
- df[:] #to slice the rows
- sum() #to add the integers or floats within my sliced rows of the dataframes created for each month
- list.append() #to add the sums of my called columns 'Tor Relay' and 'Tor Bridges'



