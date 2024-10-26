- 👋 Hi, I’m @MARIA9833
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...

<!---
MARIA9833/MARIA9833 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
/*6.Mostrar la lista de productos descontinuados
(nombre y precio) cuyo precio es menor al precio promedio.*/

/*Descontinuado = 1*/

seleccione p.ProductID,p.ProductName,p.UnitPrice
de Productos p
donde p.Discontinued=1 y p.UnitPrice> (seleccione AVG(p.UnitPrice)
										 de Productos p)

seleccione AVG(p.PrecioUnitario)
de Productos p

