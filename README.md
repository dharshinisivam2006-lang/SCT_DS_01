# SCT_DS_01
Create a bar chart  or histogram to visualize the distribution of a categorical or continuous variable, such as the distribution of ages or  genders in a population 
## Output

![Bar Chart](download.png)

## Python Code (Google Colab)

```python
import matplotlib.pyplot as plt

gender = ['Male', 'Female']
count = [60, 40]

plt.bar(gender, count)
plt.xlabel('Gender')
plt.ylabel('Count')
plt.title('Gender Distribution of Population')
plt.show()


The bar chart was created using Python in Google Colab.
The complete implementation is available in the uploaded notebook file.
