# STD_Deviation_exercise
# I use "escribe" to look at my parameters : "mean" , "std" itd.
# Import "seaborn" and use it to get "histplot" and look at my "Height" column
# Then i get the hight mean and save it into "mean" """mean = df.Height.mean()"""
# Also i get std_deviation and save it into "std_deviation" """std_deviation = df.Height.std()"""
# I can use formula to remove outliers, i need to use +3 "std." and -3 "std."
# So i calculate it using pattern """mean - 3*std_deviation""" and """mean + 3*std_deviation"
# And i get my df. without outliers """df_no_outlier = df[(df.Height < 73.69) & (df.Height > 62.28)]"""
# I can look at shape of my new data """df_no_outlier.shape""" 
