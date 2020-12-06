<template>
    <div>
        <footer class="footer">
        <div class="flex-container">
            <div class="footer-container">
                <h4>Motivación</h4>
                <p>Este es el proyecto de el sprint numero 1 de la fase de desarrollo de software del grupo 182, el objetivo es dearrollar una pagina web estatica. </p>
                <h4>enlace Github</h4>
                <p><a class="white" href="https://github.com/andresromero222/semana-1-182">https://github.com/andresromero222/semana-1-182</a></p>
            </div>
            <div class="footer-container">
                <h4>Contacto</h4>
                <p>David Mateo Vega Triana: davidvegat17@gmail.com</p>
                <p>Andrés Felipe Romero Silva: fiorenttos227@gmail.com</p>
                <p>Santiago Puentes Ninco: sntiagopuentes@gmail.com</p>
                <p>Laura Juliana Bohorquez Vergara: laujuliana14@gmail.com</p>
                <p>Cristian Revelo Sanabria: cristianrevelo@hotmail.com</p>
            </div>
        </div>
        <div class= "footer-form-container">
            <form>
                <div class="row">
                  <div class="col">
                    <input type="text" class="form-control" placeholder="Nombre">
                  </div>
                  <div class="col">
                    <input type="text" class="form-control" placeholder="Correo">
                  </div>
    
                  <div class="col">
                    <input type="text" class="form-control" placeholder="Mensaje">
                  </div>
                  <button type="submit" class="btn btn-primary">Enviar</button>                                   
                </div>
                
                </form>
                
        </div>
        <div class="footer-copyright text-center py-1 bg-dark">© 2020 Copyright: DAD
                 </div>
    </footer>
    </div>
</template>

<script>
export default {
    name: "PageFooter",
}
</script>

<style scoped>

.footer{
        background-color: grey;
        
    }
    .footer-container{
        padding: 20px;
        color:gainsboro;
        max-width: 600px;
    }

    .footer-form-container{
        padding: 20px;
        color:gainsboro;
    }

    .flex-container{
        display: flex;
    }

    .white{
        color:white;
    }
    .footer-copyright{
        color: beige;
    }

</style>
