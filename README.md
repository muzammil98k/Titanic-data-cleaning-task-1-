# Titanic Data Preprocessing

This is a simple project where I cleaned and prepared the Titanic dataset for Machine Learning.

---

## Steps I Did
1. **Handled Nulls**
   - Filled missing `Age` with median.
   - Dropped `Cabin` because too many values were missing.
   - Filled missing `Embarked` with the most common value.

2. **Encoding**
   - Converted `Sex` into numbers (male = 1, female = 0).
   - Converted `Embarked` into numbers using label encoding.

3. **Dropped Extra Columns**
   - Removed `PassengerId`, `Name`, and `Ticket` since they don’t help prediction.

4. **Feature Scaling**
   - Scaled numerical features so that all values are on a similar range.

---

## Final Dataset
Columns used:  
`Pclass, Sex, Age, SibSp, Parch, Fare, Embarked, Survived`

Now the dataset is clean and ready for training ML models 🚀
