# Update Operators


## $inc
{$inc:{<field>:<amount>,<field2>:<amount2>}}
## $mul
{$inc:{<field>:<number1>}}
## $set y $update

## Ejemplo 
db.products.updateOne(
   { _id: 100 },
   { 
       $set: {
           quantity: 500,
           details: { model: "14Q3", make: "xyz" },
           tags: ["coats", "outwear", "clothing"]
       } 
   } 
)