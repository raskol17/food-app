<template>
  <div class="bigContainer">
    <div class="header">
      <div class="hero">
        <img src="" alt="" />
      </div>
      <div class="present-container">
        <div class="present-content">
          <div class="avatar"></div>
          <div class="present-text">
            <h1 class="name">cuervo negro</h1>
            <p class="subtitulo">Cerveza Osada y Comida Rica</p>
            <div class="direccion">
              <a
                target="_blank"
                href="https://www.google.com/maps/place/Av.+Col%C3%B3n+515,+Bah%C3%ADa+Blanca,+Provincia+de+Buenos+Aires/@-38.7235959,-62.2730119,15z/data=!4m13!1m7!3m6!1s0x95edbcb0b76f3c25:0x80de191e777b8c76!2sAv.+Col%C3%B3n+515,+Bah%C3%ADa+Blanca,+Provincia+de+Buenos+Aires!3b1!8m2!3d-38.7235662!4d-62.2731873!3m4!1s0x95edbcb0b76f3c25:0x80de191e777b8c76!8m2!3d-38.7235662!4d-62.2731873"
                ><box-icon type="solid" name="map" class="map-icon"></box-icon>
                Av Colon 515</a
              >
            </div>
          </div>
          <div class="redes-sociales">
            <a href="" class="iconos">
              <button
                type="button"
                aria-label="Enviar mensaje por whatsapp"
                class="btn"
              >
                <div>
                  <svg
                    xmlns="http://www.w3.org/2000/svg"
                    width="24"
                    height="24"
                    viewBox="0 0 24 24"
                    style="transform: ; -ms-filter: "
                  >
                    <path
                      fill-rule="evenodd"
                      clip-rule="evenodd"
                      d="M18.403,5.633C16.708,3.936,14.454,3.001,12.053,3 c-4.948,0-8.976,4.027-8.978,8.977c0,1.582,0.413,3.126,1.198,4.488L3,21.116l4.759-1.249c1.312,0.715,2.788,1.092,4.29,1.093h0.004 l0,0c4.947,0,8.975-4.027,8.977-8.977C21.03,9.585,20.098,7.33,18.403,5.633 M12.053,19.445H12.05 c-1.339-0.001-2.652-0.36-3.798-1.041l-0.272-0.162l-2.824,0.741l0.753-2.753l-0.177-0.282c-0.747-1.188-1.141-2.561-1.141-3.971 c0.002-4.114,3.349-7.461,7.465-7.461c1.993,0.001,3.866,0.778,5.275,2.188c1.408,1.411,2.184,3.285,2.183,5.279 C19.512,16.097,16.165,19.445,12.053,19.445 M16.146,13.856c-0.225-0.113-1.327-0.655-1.533-0.73 c-0.205-0.075-0.354-0.112-0.504,0.112s-0.58,0.729-0.711,0.879s-0.262,0.168-0.486,0.056s-0.947-0.349-1.804-1.113 c-0.667-0.595-1.117-1.329-1.248-1.554s-0.014-0.346,0.099-0.458c0.101-0.1,0.224-0.262,0.336-0.393 c0.112-0.131,0.149-0.224,0.224-0.374s0.038-0.281-0.019-0.393c-0.056-0.113-0.505-1.217-0.692-1.666 C9.627,7.787,9.442,7.845,9.304,7.839c-0.13-0.006-0.28-0.008-0.429-0.008c-0.15,0-0.393,0.056-0.599,0.28 C8.07,8.336,7.491,8.878,7.491,9.982c0,1.104,0.804,2.171,0.916,2.321c0.112,0.15,1.582,2.415,3.832,3.387 c0.536,0.231,0.954,0.369,1.279,0.473c0.537,0.171,1.026,0.146,1.413,0.089c0.431-0.064,1.327-0.542,1.514-1.066 c0.187-0.524,0.187-0.973,0.131-1.067C16.52,14.025,16.369,13.968,16.146,13.856"
                    ></path>
                  </svg>
                </div>
              </button>
            </a>
            <a href="" class="iconos">
              <button type="button" aria-label="Ir a Instagram" class="btn">
                <div>
                  <svg
                    xmlns="http://www.w3.org/2000/svg"
                    width="24"
                    height="24"
                    viewBox="0 0 24 24"
                  >
                    <path
                      d="M11.999,7.377c-2.554,0-4.623,2.07-4.623,4.623c0,2.554,2.069,4.624,4.623,4.624c2.552,0,4.623-2.07,4.623-4.624 C16.622,9.447,14.551,7.377,11.999,7.377L11.999,7.377z M11.999,15.004c-1.659,0-3.004-1.345-3.004-3.003 c0-1.659,1.345-3.003,3.004-3.003s3.002,1.344,3.002,3.003C15.001,13.659,13.658,15.004,11.999,15.004L11.999,15.004z"
                    ></path>
                    <circle cx="16.806" cy="7.207" r="1.078"></circle>
                    <path
                      d="M20.533,6.111c-0.469-1.209-1.424-2.165-2.633-2.632c-0.699-0.263-1.438-0.404-2.186-0.42 c-0.963-0.042-1.268-0.054-3.71-0.054s-2.755,0-3.71,0.054C7.548,3.074,6.809,3.215,6.11,3.479C4.9,3.946,3.945,4.902,3.477,6.111 c-0.263,0.7-0.404,1.438-0.419,2.186c-0.043,0.962-0.056,1.267-0.056,3.71c0,2.442,0,2.753,0.056,3.71 c0.015,0.748,0.156,1.486,0.419,2.187c0.469,1.208,1.424,2.164,2.634,2.632c0.696,0.272,1.435,0.426,2.185,0.45 c0.963,0.042,1.268,0.055,3.71,0.055s2.755,0,3.71-0.055c0.747-0.015,1.486-0.157,2.186-0.419c1.209-0.469,2.164-1.424,2.633-2.633 c0.263-0.7,0.404-1.438,0.419-2.186c0.043-0.962,0.056-1.267,0.056-3.71s0-2.753-0.056-3.71C20.941,7.57,20.801,6.819,20.533,6.111z M19.315,15.643c-0.007,0.576-0.111,1.147-0.311,1.688c-0.305,0.787-0.926,1.409-1.712,1.711c-0.535,0.199-1.099,0.303-1.67,0.311 c-0.95,0.044-1.218,0.055-3.654,0.055c-2.438,0-2.687,0-3.655-0.055c-0.569-0.007-1.135-0.112-1.669-0.311 c-0.789-0.301-1.414-0.923-1.719-1.711c-0.196-0.534-0.302-1.099-0.311-1.669c-0.043-0.95-0.053-1.218-0.053-3.654 c0-2.437,0-2.686,0.053-3.655c0.007-0.576,0.111-1.146,0.311-1.687c0.305-0.789,0.93-1.41,1.719-1.712 c0.534-0.198,1.1-0.303,1.669-0.311c0.951-0.043,1.218-0.055,3.655-0.055c2.437,0,2.687,0,3.654,0.055 c0.571,0.007,1.135,0.112,1.67,0.311c0.786,0.303,1.407,0.925,1.712,1.712c0.196,0.534,0.302,1.099,0.311,1.669 c0.043,0.951,0.054,1.218,0.054,3.655c0,2.436,0,2.698-0.043,3.654H19.315z"
                    ></path>
                  </svg>
                </div>
              </button>
            </a>
            <a href="" class="iconos">
              <button type="button" aria-label="Ir a facebook" class="btn">
                <div aria-hidden="true">
                  <svg
                    xmlns="http://www.w3.org/2000/svg"
                    width="24"
                    height="24"
                    viewBox="0 0 24 24"
                  >
                    <path
                      d="M13.397,20.997v-8.196h2.765l0.411-3.209h-3.176V7.548c0-0.926,0.258-1.56,1.587-1.56h1.684V3.127 C15.849,3.039,15.025,2.997,14.201,3c-2.444,0-4.122,1.492-4.122,4.231v2.355H7.332v3.209h2.753v8.202H13.397z"
                    ></path>
                  </svg>
                </div>
              </button>
            </a>
          </div>
        </div>
      </div>
    </div>
    <!-- end of header -->
    <div class="products-container">
      <div class="cartel-horarios">Enviamos desde las 19 hasta las 22hs</div>
      <div class="categorias-container">
        <div class="categorias-content">
          
            

            <Categorias />

            
          
        </div>
      </div>
      <!-- productos -->
      <div class="products1">
        <div class="products2">
          <div class="products3">
            <div class="section-container">
              <Productos />
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
import Categorias from "./components/Categorias.vue"
import Productos from "./components/Productos"


export default {
  components: { Categorias, Productos },
  data() {
    return {
      
    };
  },
};
</script>

<style>
* {
  margin: 0;
  padding: 0;
}
.bigContainer {
  padding-right: 1rem;
  padding-left: 1rem;
}
.hero {
  background-color: rgba(0, 0, 0, 1);
  background-image: url("./assets/hero.jpeg");
  background-position: center center;
  background-repeat: no-repeat;
  background-size: cover;
  height: 15rem; /* cambiar en responsive */
  width: 100%;
}
.avatar {
  background-color: rgba(250, 250, 250, 1);
  background-image: url("./assets/logoCN.png");
  background-position: center center;
  background-repeat: no-repeat;
  background-size: cover;
  border-radius: 50%;
  height: 250px;
  width: 250px;
  margin-top: -1.5rem;
  margin-right: 1rem;
  margin-left: 1rem;
}
.present-content {
  display: grid;
  padding-left: 1rem;
  padding-right: 1rem;
}
.present-text {
  display: flex;
  flex-direction: column;
  margin-top: 0.25rem;
  margin-left: 0.5rem;
}
.present-text h1 {
  font-size: 1.25rem;
  font-weight: 700;
  line-height: normal;
  margin-bottom: 0;
}
.present-text p {
  color: rgb(113, 128, 150);
  font-size: 0.875rem;
  line-height: 1.625rem;
  margin-bottom: 0;
}
.direccion {
  display: flex;
  flex-direction: row;
  --webkit-box-align: center;
  align-items: center;
  color: rgb(49, 151, 149);
  margin-top: 0.25rem;
}
.direccion a {
  cursor: pointer;
  text-decoration: none;
  outline: none;
  color: inherit;
  font-size: 0.875rem;
  line-height: 1.625rem;
}
.map-icon {
  color: rgb(49, 151, 149); /* No lo toma */
}
.redes-sociales {
  display: flex;
  flex-direction: row;
  justify-content: flex-end;
  height: 2.5rem;
  margin-top: 1rem;
  -webkit-box-pack: end;
}
.iconos {
  cursor: pointer;
  text-decoration: none;
  outline: none;
  margin-right: 0.5rem;
}
button {
  cursor: pointer;
}
.btn {
  -webkit-box-align: center;
  align-items: center;
  appearance: none;
  background-color: rgb(49, 151, 149);
  border-radius: 9999px;
  fill: rgb(255, 255, 255);
  display: inline-flex;
  font-size: 1rem;
  font-weight: 600;
  height: 34px;
  -webkit-box-pack: center;
  justify-content: center;
  line-height: 1.2;
  outline: none;
  position: relative;
  transition: all 250ms ease 0s;
  user-select: none;
  vertical-align: middle;
  white-space: nowrap;
  width: 34px;
  min-width: auto;
  min-height: auto;
  padding: 6px;
  border: none;
}
/* end of header */
.cartel-horarios {
  background-color: rgb(230, 255, 250);
  color: rgb(49, 151, 149);
  font-size: 0.875rem;
  font-weight: 500;
  margin-top: 1rem;
  padding: 0.75rem 1rem;
  text-align: left;
}
.categorias-container {
  background-color: rgb(247, 250, 252);
  border-radius: 0px 0px 0.5rem 0.5rem;
  margin-bottom: 1.25rem;
  padding: 1.5rem 1rem;
  position: sticky;
  top: 0px;
  z-index: 3;
}
.categorias-content {
  display: flex;
  -webkit-box-align: center;
  align-items: center;
}
.categorias-menu {
  flex-grow: 1;
  flex-shrink: 1;
  flex-basis: 0%;
  max-width: 100%;
  position: relative;
  width: auto;
}

.categoriasBtn {
  border: none;
}
.categorias-icons {
  width: 4rem;
  background-color: rgb(247, 250, 252);
  fill: rgb(49, 151, 149);
  border: none;
  border-width: 0px;
}
.section-container{
  display: flex;
  flex-direction: column;
  width: 100%;
}

/* end of categorias */

.products1{
  margin-bottom: 1rem;
  padding-left: 0px;
  padding-right: 0px;
}
.products2{
  display: flex;
  flex-direction: column;
  margin: auto;
  width: 100%;
}
.products3{
  display: flex;
  flex-direction: column;
  width: 100%;
}

@media screen and (min-width: 30em) {
  .present-content {
    grid-template-areas: "avatar information links";
    grid-template-columns: auto 1fr auto;
  }
  .avatar {
    height: 8rem;
    width: 8rem;
    min-height: 8rem;
    min-width: 8rem;
    margin-right: 1rem;
    margin-top: -2rem;
  }
  .present-text {
    margin-top: 1rem;
  }
  .present-text h1 {
    font-size: 1.875rem;
    margin-bottom: 0.25rem;
  }
  .present-text p {
    font-size: 1rem;
    margin-bottom: 0.25rem;
  }
  .btn {
    width: 36px;
    height: 36px;
  }
  .cartel-horarios {
    font-size: 1rem;
    border-top-left-radius: 0.5rem;
    border-top-right-radius: 0.5rem;
    text-align: center;
  }
  .categorias-container {
    margin-bottom: 2.5rem;
  }
  .categorias-menu {
    /* flex: inherit; */
    /* max-width: 140px; */
    justify-content: space-around;


  }
}
</style>
