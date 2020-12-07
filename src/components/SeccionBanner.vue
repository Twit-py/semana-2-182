<template>
    <div>

    <seccion-menu></seccion-menu>
    
        <div id="carouselExampleCaptions" class="carousel slide" data-ride="carousel">
            <ol class="carousel-indicators"> 
                <li data-target="#carouselExampleCaptions" data-slide-to="0" class="active"></li>
                <li data-target="#carouselExampleCaptions" data-slide-to="1" class=""></li> 
                <li data-target="#carouselExampleCaptions" data-slide-to="2" class=""></li> 
            </ol>
            <div class="carousel-inner">
                <div class="carousel-item active">
                    <img src="https://images.pexels.com/photos/546819/pexels-photo-546819.jpeg?auto=compress&cs=tinysrgb&h=750&w=1260.jpg" alt="web design" class="bd-placeholder-img bd-placeholder-img-lg d-block w-100"  height="550">
    
                        <div class="carousel-caption d-none d-md-block"> 
                            <h3>Backend</h3>
                    
                        </div>
                </div>
                <div class="carousel-item">
                    <img src="https://images.pexels.com/photos/669613/pexels-photo-669613.jpeg?auto=compress&cs=tinysrgb&h=750&w=1260.jpg" alt="Big data" class="bd-placeholder-img bd-placeholder-img-lg d-block w-100"  height="550">
                    
                        <div class="carousel-caption d-none d-md-block"> 
                            <h3>Frontend</h3> 
                            
                        </div> 
                </div>
                <div class="carousel-item"> 
                    <img src="https://images.pexels.com/photos/373543/pexels-photo-373543.jpeg?auto=compress&cs=tinysrgb&h=750&w=1260.jpg" alt="Big data" class="bd-placeholder-img bd-placeholder-img-lg d-block w-100"  height="550">
                        
                        <div class="carousel-caption d-none d-md-block"> 
                            <h3>Big Data</h3> 
                                
                        </div> 
                </div>  
            </div>
    
            <a class="carousel-control-prev" href="#carouselExampleCaptions" role="button" data-slide="prev"> 
                <span class="carousel-control-prev-icon" aria-hidden="true"></span> 
                <span class="sr-only">Previous</span> 
            </a> 
            <a class="carousel-control-next" href="#carouselExampleCaptions" role="button"
            data-slide="next"> 
                <span class="carousel-control-next-icon" aria-hidden="true"></span> 
                <span class="sr-only">Next</span> 
            </a> 
        </div>
       
        </div>  
</template>

<script>
import SeccionMenu from './SeccionMenu.vue';
export default {
    name: "SeccionBanner",
    components: {
        SeccionMenu,
    }
        
    }
</script>

<style scoped>

</style>