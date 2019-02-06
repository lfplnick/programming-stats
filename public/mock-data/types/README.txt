The types mock data set contains a sample set of program types. The root file
has the primary program types, i.e. those without parent types. Each of the
numbered files contain subtypes of the type which corresponds to the filename.

For example, inside root.json you can see that type "Child" has an ID of 2. You
can then read the contents of 2.json to find subtypes of "Child" programs.
Inside 2.json is another subtype of "Storytime" with an ID of 6. Reading 6.json
reveals another set of subtypes to the Storytime subtype.

Leaf nodes do not have any subtypes and their json files only contain an empty
array. For example, if you select "Teen" (ID 3) and then "Homework Help" (ID 10)
you will then navigate to an empty file, 10.json. This indicates that a final
type (ID 10: Homework Help) has been selected.