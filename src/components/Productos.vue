<template>

<section class="big-section" >
  <div class="section-content">
            <div class="section-title">
                <h2 class="title">  </h2>
                <p class="cant-productos"></p>
            </div>
  <div
    class="big-product-container"
    
  >
    <div class="product-container" v-for="producto in productos[0].burgers"
    v-bind:key="producto">
      <div class="product-content">
        <div class="product-text">
          <p class="product-title">{{ producto.nombre }}</p>
          <p class="product-description">{{ producto.descripcion }}</p>
        <div class="product-price">
          <p class="price-number">${{ producto.precio }}</p>
        </div>
        </div>
      <div class="product-image" :style="{backgroundImage: `url( ${producto.img})`}"></div>
      </div>
    </div>
  </div>
  </div>
    </section>
</template>

<script>


export default {
  data() {
    return {
      productos: [
        {
          burgers: [
            {
              nombre: "cheeseburger",
              descripcion: "pan, hamburguesa y doble cheddar.",
              precio: 300,
              img:
                "https://images.unsplash.com/photo-1572802419224-296b0aeee0d9?ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&ixlib=rb-1.2.1&auto=format&fit=crop&w=1303&q=80",
            },
            {
              nombre: "Onions",
              descripcion: "pan, doble hamburguesa, doble cheddar, cebolla",
              precio: 450,
              img: "https://images.unsplash.com/photo-1572802419224-296b0aeee0d9?ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&ixlib=rb-1.2.1&auto=format&fit=crop&w=1303&q=80",
            },
            { nombre: "American",
              descripcion: "pan, doble hamburguesa, doble cheddar y panceta",
              precio: 600,
              img: 'https://images.unsplash.com/photo-1572802419224-296b0aeee0d9?ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&ixlib=rb-1.2.1&auto=format&fit=crop&w=1303&q=80',
               }
          ]
        },

        { pizzas: [{titulo: 'pizzas'},
        { nombre: "mozzarela", descripcion: "masa, salsa de tomate, mozzarela, aceitunas", precio: "450", img: "https://images.unsplash.com/photo-1605478371310-a9f1e96b4ff4?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=1050&q=80" }] },
      ],
    };
  },
};
</script>

<style>
.big-section{
  margin-bottom: 2rem;
}
.section-content{
  display: flex;
  flex-direction: column;
}
.section-title{
  display: flex;
  flex-direction: row;
  font-size: 1.125rem;
  font-weight: 500;
  margin-bottom: 0px;
  padding-left: 1rem;
  padding-right: 1rem;
  text-transform: capitalize;
}
.title{
  margin-right: 0.25rem;
}
.cant-productos{
  color: rgb(160, 174, 192);
}
.big-product-container {
  display: grid;
  grid-auto-rows: auto;
  gap: 0px;
  grid-template-columns: repeat(auto-fill, minmax(320px, 1fr));
  padding-bottom: 1rem;
  padding-top: 1rem;
  
}
.product-container {
  background-color: rgb(255, 255, 255);
  border-bottom-width: 1px;
  border-radius: 0px;
  box-shadow: none;
  cursor: pointer;
  padding: 1rem;
  transition: all 0.2s ease 0s;
  border-width: 1px;
  border-style: solid;
  border-color: rgb(226, 232, 240);
  
}
.product-content {
  display: flex;
  flex: 1 1 0%;
  flex-direction: row;
  height: 100%;
  -webkit-box-pack: justify;
  justify-content: space-between;
  margin-right: 1rem;
  min-height: 6rem;
  padding: 0px;
  width: 100%;
}
.product-text {
  display: flex;
  flex-direction: column;
  margin-bottom: 0.5rem;
  padding: 1rem;
}
.product-title {
  font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Oxygen,
    Ubuntu, Cantarell, "Open Sans", "Helvetica Neue", sans-serif;
  text-transform: capitalize;
  overflow: hidden;
  font-weight: 500;
  line-height: normal;
  margin-bottom: 0.25rem;
}
.product-description {
  font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Oxygen,
    Ubuntu, Cantarell, "Open Sans", "Helvetica Neue", sans-serif;
  overflow: hidden;
  color: rgb(113, 128, 150);
  text-transform: capitalize;
  font-size: 0.875rem;
}
.product-image{
  background-color: rgb(237, 242, 247);
  background-position: center center;
  background-repeat: no-repeat;
  background-size: cover;
  border: 0px;
  border-radius: 0.25rem;
  flex-shrink: 0;
  height: 6rem;
  min-height: 6rem;
  opacity: 1;
  transition: opacity 500ms ease-in 0s;
  width: 6rem;
}
.product-price{
  display: flex;
  flex-direction: row;
  -webkit-box-align: center;
  align-items: center ;
}

@media screen and (min-width: 30rem) {
  .big-section{
    margin-bottom: 3rem;
  }
  .section-title{
    font-size: 1.5rem;
    padding-left: 0px;
    padding-right: 0px;
    margin-bottom: 1rem;
  }
  .big-product-container {
    gap: 2rem;
    grid-template-columns: repeat(auto-fill, minmax(400px, 1fr));
    padding-top: 0px;
    padding-bottom: 0px;
  }
  .product-container {
    
    border-width: 1px ;
    padding: 10px;
    border-radius: 0.25rem;
    
  }
  .product-conten {
    min-height: 9rem;
    padding: 1rem;
  }
  .product-image{
    height: auto;
    width: 9rem;
    min-height: 9rem;
    border-top-left-radius: 0px;
    border-bottom-left-radius: 0px;
  }

}
</style>