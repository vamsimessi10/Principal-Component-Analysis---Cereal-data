I will first clean the dataset and then create some visualizations to understand how the data is present. Then, I will
conduct a principal component analysis to reduce dimensionality. We use R to
answer the questions. The data were collected on the nutritional information and consumer rating of 77
breakfast cereals. 




For each cereal we have included 13 numerical variables and 2 categorical variables
(i.e. mfr and type).
Variable Name; Description


Name: Name of cereal
mfr: Manufacturer of cereal. {A=American Home Food Products, G=General Mills,
K=Kelloggs, N=Nabisco, P=Post, Q=Qauker Oats, R=Ralston Purina}
type: {cold, hot}
calories: Calories per serving
protein: Grams of protein
fat: Grams of fat
sodium: Milligrams of sodium
fiber: Grams of dietary fiber
carbo: Grams of complex carbohydrates
sugars: Grams of sugars
potassL Milligrams of potassium
vitaminsL Vitamins and minerals-0, 25, or 100, indicating the typical percentage of FDA
recommended
shelf Display shelf: 1, 2, or 3, counting from the floor
weight: Weight in ounces of one serving
cups: Number of cups in one serving
rating: A rating of the cereals calculated by Consumer Reports
