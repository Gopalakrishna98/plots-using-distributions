# plots on poisson ditribution

import seaborn as sns

sns.distplot(np.random.poisson(5,1000),bins=40,kde=True,rug=True)

plt.text(0.2,0.4,'poisson 5\n distribution function')
    

# plots on normal distribution

plt.figure(figsize=(30,30),facecolor='red')

import seaborn as sns

sns.distplot(np.random.poisson(10,10000),bins=80,kde=True,rug=True);

plt.text(2,0.4,'poisson 5\n distribution function');

sns.distplot(np.random.poisson(20,10000),bins=80,kde=True,rug=True);

sns.distplot(np.random.poisson(5,1000),bins=80,kde=True,rug=True);

plt.text(2,0.4,'poisson 5\n distribution function');
   
   
# Binomial distribution
import seaborn as sns
sns.distplot(np.random.binomial(20,0.5,10000),bins=80,kde=True,rug=True);
plt.text(2,0.4,'binomial 5\n distribution function');
    
