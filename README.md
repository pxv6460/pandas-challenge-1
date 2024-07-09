# pandas-challenge-1

the only thing I looked online for was that my drop method was not working so I used ChatGPT

df['Line_price'] = round((df['subtotal'] + df['shipping_price'])*1.0925,2)
df.drop('total_price', axis=1, inplace=True)
df.head()

I had forgot that i needed the inplace=True in the ()'s of the method

I then saw that the numbers in the prerunned kernels calculated the total weight first so I had to rerun most of part 2 and when I did that I had to then get rid of the drop line as total_price nolonger was part of the df dataframe


chatgpt helped me with the Iloc function as for the last task I was duplicating the columns so there could be 30 total profit columns so if I where to continue on this code i would find a way to make the dataframe only have 5 columns so it becomes better for memory 

