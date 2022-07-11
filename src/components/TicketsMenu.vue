<template>
    <div class="menu-tickets">
        <div class="tema">
            <p>Buscador tickets</p>
        </div>
        <div class="filtros">
            <ul>
            <li>Ciudad Origen</li> 
            <li>Ciudad destino</li> 
            <li>Fecha salida</li> 
            <li>Fecha retorno</li> 
            </ul>
        </div>
    </div>
</template>

<script>
export default {
  name: 'TicketsMenu',
}
</script>

<style scoped>
    .menu-tickets {
        background-color: black;
        display: flex;
        flex-direction: row;
        justify-content: space-between;
        align-items: center;
    }
    .tema{
        display: flex;
        flex: 0.5;
    }
    .filtros{
        display: flex;
        flex:0.5
    }
    
</style>