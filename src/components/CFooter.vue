<template>
<div class="footer">
 <p>Siga-nos nas Redes Sociais!</p>
        
        <ul class="linkssoc">
     
            <li>
                <a href="https://www.facebook.com" target="_blank" >
                    <i class="fa fa-facebook" aria-hidden="true">Facebook</i>
                    <i class="fa-brands fa-facebook"></i>
                </a>
            </li>
            <li>
                <a href="https://pt.linkedin.com/" target="_blank" aria-label="LinkedIn">
                    <i class="fa-linkedin-in">LinkedIn</i>
                </a>
            </li>
            <li>
                <a href="https://x.com/" target="_blank" aria-label="X (Twitter)">
                    <i class="fa-x-twitter">Twitter</i>
                </a>
            </li>
            <li>
                <a href="https://www.youtube.com/" target="_blank" aria-label="YouTube">
                    <i class="fa-youtube">YouTube</i>
                </a>
            </li>
        </ul>

        <p class="copyright">
            &copy; 2025 Mestrado EITW. Todos os direitos reservados.
        </p>
</div>
</template>    


<style scoped>

 .footer {
            background-color: #3b2cc1ff; 
            color: #ccccccff; 
            padding: 30px 20px;
            text-align: center;

             height: 60px; 
             position: relative; 
             margin-top: 5%;

        }

        .linkssoc {
            list-style: none;
            padding: 0;
            margin: 20px 0 10px 0;
            display: flex; 
            justify-content: center; 
            gap: 20px; 
        }

        .linkssoc li {
            display: inline-block;
        }

        .linkssoc a {
            color: #ccc; 
            font-size: 20px; 
            text-decoration: none;
            transition: color 0.3s;
        }

       
        .linkssoc a:hover {
            color: #0077b5; 
        }

        .copyright {
            font-size: 14px;
            margin-top: 20px;
            color: #0077b5; 
        }

</style>