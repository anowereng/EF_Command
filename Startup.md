
## Migration basic command 

- multiple context 
``` Add-Migration AddCategoryTypeColumnToDmoCategoryTable -context DemoContext ```
- migrate file override
``` add-migration addcategoriestable -force ```
- when add a new column 
``` AddCategoryColumnToCoursesTable ```
- when rename a column
```RenameTitleToNameCoursesTable```

## Query 
- Query has two type 
1. Linq 
2. Extension 

## Func 
 ``` 
 Func<int, int> GetMultiplySingle = num => num * 5;

        Func<int, int, int> GetMultiplyDouble = (a, b) => a * b;

        Func<int, int> multiplyByFive = num =>
        {
            int product = num * 5;
            return product;
        };
