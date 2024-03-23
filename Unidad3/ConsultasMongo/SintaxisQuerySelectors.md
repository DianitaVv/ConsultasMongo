# sintaxis de query selectors

## $eq equals
db.Coleccion.find({campo:{$eq:valor}})
## $gt grater than
db.Coleccion.find({campo:{$gt:valor}})
## $gte greater than or equals
db.Coleccion.find({campo:{$gte:valor}})
## $in in
db.Coleccion.find({campo:{$in:[condicion,condicion]}})
## $lt less then
db.Coleccion.find({campo:{$lt:valor}})
## $lte less then or eqls
db.Coleccion.find({campo:{$lte:valor}})
## $ne not equal
db.Coleccion.find({campo:{$ne:valor}})
## $nin != not in
db.Coleccion.find({campo:{$nin:[valor,valor]}})
