# Update one 
## Este método se utiliza comúnmente para realizar actualizaciones específicas en un solo documento en una colección.

### Sintaxis de update one
db.collection.updateOne( <filtro>, <actualización>, <opciones>)

### Ejemplo
db.libros.updateOne({titulo:"Json para todos"})

db.libros.updateOne({ _id: 11 },{ $set: { titulo: "nuevo titulo" } })