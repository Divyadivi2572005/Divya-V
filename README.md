val1 = (1 - (2.5 * 1 + (-2)))**2
val2 = (2 - (2.5 * 2 + (-2)))**2
val3 = (3 - (2.5 * 2 + (-2)))**2
val4 = (6 - (2.5 * 3 + (-2)))**2
rss = val1 + val2 + val3 + val4
print("Reg No: 111622201118")
print("\n")
print("RSS", val1, val2, val3, val4)
y = [1, 2, 3, 6]
y_mean = sum(y) / len(y)
y_var = sum((yi - y_mean)**2 for yi in y)
tss = y_var

r_squared = 1 - (rss / tss)
print("Error", r_squared)