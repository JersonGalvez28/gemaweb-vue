<template>
  <div>
    <Menu />
      <div class="main-content">
        <MenuSuperior />
        <Estadisticas />
        <div class="container-fluid mt--7">
          <div class="row">
            <div class="col">
              <div class="card shadow border-0">
                <!-- ACA VA EL CONTENIDO  -->
              </div>
            </div>
          </div>
        </div>
        <div class="container-fluid">
          <Footer />
        </div>
      </div>
  </div>
</template>
<script>
import Footer from '@/components/gemaweb/Footer';
import Estadisticas from '@/components/gemaweb/Estadisticas';
import NoEstadisticas from '@/components/gemaweb/NoEstadisticas';
import MenuSuperior from '@/components/gemaweb/MenuSuperior';
import Menu from '@/components/gemaweb/Menu';

export default {
  name: 'Inicio',
  components: {
    Estadisticas,
    NoEstadisticas,
    MenuSuperior,
    Menu,
    Footer
  }
}
</script>
