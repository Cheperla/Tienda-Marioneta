https://gconst carrito = [];

function agregarAlCarrito(producto) {
  carrito.push(producto);
  mostrarCarrito();
}

function mostrarCarrito() {
  const lista = document.getElementById("lista-carrito");
  lista.innerHTML = "";
  carrito.forEach((item, index) => {
    const li = document.createElement("li");
    li.textContent = item;
    lista.appendChild(li);
  });
}ithub.com/Cheperla/Tienda-Marioneta.git
body {
  font-family: sans-serif;
  margin: 0;
  background: #fff9f1;
  color: #333;
}

header {
  background: #ff8c42;
  color: white;
  text-align: center;
  padding: 1rem;
}

.productos {
  padding: 2rem;
}

.grid {
  display: flex;
  gap: 2rem;
  flex-wrap: wrap;
}

.producto {
  background: white;
  border-radius: 8px;
  padding: 1rem;
  box-shadow: 0 2px 5px rgba(0,0,0,0.1);
  text-align: center;
  width: 200px;
}

button {
  background: #ff8c42;
  color: white;
  border: none;
  padding: 0.5rem 1rem;
  border-radius: 5px;
  cursor: pointer;
}

.carrito {
  padding: 2rem;
  background: #ffe7d6;
}

footer {
  text-align: center;
  padding: 1rem;
  background: #ff8c42;
  color: white;
}
