pip install venn
import matplotlib.pyplot as plt
from venn import venn
a = [1,3,7,9,12]
b = [2,7,10,12]
c = [5, 6]
mn_a = set(a)
mn_b = set(b)
mn_c = set(c)
uni = set.union(mn_a, mn_b, mn_c)
#print(uni)
inter = set.intersection(mn_a, mn_b, mn_c)
print(inter)
print(mn_a - mn_b - mn_c)
print(mn_b - mn_a - mn_c)
diction = {'a':mn_a, 'b': mn_a, 'c': mn_a}
venn(diction)
plt.savefig('ven.png', dpi = 400)
