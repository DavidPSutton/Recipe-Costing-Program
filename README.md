# Recipe Costing Program
Recipe Template Instructions




Contents

I. Entering Recipes

II.	Scaling Recipes III. Costing Recipes
IV. Adding/Editing Ingredients

----------------------------------------------------------------------------------------------------------------

--------------------------

I. Entering Recipes

To create new recipes, first select the "Recipe" Tab. Enter a name for your recipe where it says "(Recipe Name Here)". In order to input a yield, you must select a unit of measure from the drop down box that appears when selected.





















To add ingredients to the recipe, select a cell in the “Ingredients” column, and begin typing the name of the ingredient. Select the ingredient from the drop down list. The list will contain all available ingredients with that combination of letters (i.e. typing “FLO” will give the options of “FLOur AP”, “CauliFLOwer”, “Broccoli FLOrets”, etc.).
 






















Continue by entering in a quantity and unit of measure. If the unit of measure chosen for the ingredient does not have a cost associated to it, the costing sheet of the workbook (See Section III) will not be able to calculate. You will have to choose a different unit, or enter a cost in the “Ingredient List” tab of the workbook (See Section IV).

If there is a preparation note (i.e. “Chopped”, “Rinsed”, “Chilled”, etc.), select it from the dropdown in the notes column.

Continue for each ingredient in the recipe.

Finally, enter in the procedure instructions for the recipe. Note that when scaling a recipe (see section II), if there are any measurements in the procedure, they will not scale. It is best to leave out specific measurements in the procedure to prevent confusion.

Save the recipe to a recipe folder with the name of the recipe.



----------------------------------------------------------------------------------------------------------------

II. Scaling Recipes



To scale your recipe, select the “Scaling Sheet” tab. This sheet automatically populates with the original recipe yield and ingredients with quantities. You may only select and change the “Amount Required” and “Units” cells on this sheet. Everything else will change as needed once you change these parameters. You can only change units of the ingredients on this sheet to ones compatible with the original units (i.e. cups can convert to gallons, but not to lbs.). If you do, the “Qty” cell will blank out.

You will also have to copy and paste the procedure from the “Recipe” tab to the procedure box on this sheet.
 
-----------------------------------------------------------------------------------------------------------------

III. Costing Recipes

To cost the recipe, select the “Recipe Costing” tab. This sheet auto populates with the original recipe, and its associated costs. If the chosen unit of measure does not have cost associated to it, the “Cost per Unit” and “Ingredient Cost” column will show “#N/A”. You will have to choose a different unit, or enter a cost in the “Ingredient List” tab of the workbook (See Section IV).






















Also, the G/L associated with the ingredient, and its percentage of total cost will be calculated on this sheet. At the bottom of the sheet there is a breakdown of G/L cost percentages to better track transferring to other units.


-----------------------------------------------------------------------------------------------------------------

IV. Adding/Editing Ingredients

To add ingredients available in the recipe template, go to the “Ingredient List” tab. Scroll to the bottom of the existing list and begin by naming the vendor and the G/L associated to the ingredient. Enter the ingredient name, the pack size/unit of measure by which you order it, and the cost per pack size.
 


























Next, you will need to figure out the best unit to cost based on the pack size. In the above image, “LENTILS DRIED” comes in 20lb cases, so you would cost the ingredient in lbs.


Select the cell in the ingredient row under the unit of measure’s column. Create a formula starting with an “=” followed by the math needed to break the cost down to the unit. The “LENTILS DRIED’ cost $ 20.95 for a 20lb case, so in the cell “lbs” column we will enter “=F606/20”. F606 is the cell under cost per pack, and is divided by 20 because it comes in a 20lb case. If you enter a value into the “lbs” column, the “oz” and “gram” columns will populate automatically. The same is true for most of volume measurements.

 


In order to organize the ingredients by type, color fill the ingredient with the corresponding color in the key located at cell W2.






























Right click the cell, and choose “Sort -> Custom Sort”.
 































Then select “OK”.




























To change the cost for an ingredient, you will only need to change the “cost/pack” cell, and the rest of the costing will change automatically. If the pack size changes, you will need to change the pack size, and the original unit cost formula.
