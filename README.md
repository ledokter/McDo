🚀 Utilisation rapide


JavaScript

import data from './data/mcdonalds-complet.json' assert { type: 'json' };

const bigMac = data.find(p => p.produit === 'Big Mac');
console.log(`${bigMac.calories_kcal} kcal – Nutri-Score ${bigMac.nutri_score}`);




Python

import pandas as pd
df = pd.read_csv('data/mcdonalds-complet.csv')
print(df[['produit','calories_kcal','nutri_score']].head())
