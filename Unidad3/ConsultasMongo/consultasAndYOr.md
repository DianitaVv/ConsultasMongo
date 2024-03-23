## seleccionar los libros con editorial bibblio con precio mayor a 40 libros de la editorial planeta con precio mayor a 30

db.libros.find({
  $or: [
    { editorial: "Bibblio", precio: { $gt: 40 } },
    { editorial: "Planeta", precio: { $gt: 30 } }
  ]
})


## como ver ciertas columnas

db.libros.find({},{titulo:1})
db.libros.find({ titulo: "Don quijote" }, { id: 0, titulo: 1 })

## uso de exists
({titulo:{$exists:True}})



