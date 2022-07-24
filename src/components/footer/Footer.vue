<template>
<div class="footer-basic ">
    <footer>
        <div class="socials container">
            <a href="#"><img class="icons"  alt=""></a>
            <a href="#"><img class="icons"  alt=""></a>
            <a href="#"><img class="icons"  alt=""></a>
        </div>
        <ul class="list-inline">
            <li class="list-inline-item"><router-link to="/">Home</router-link></li>
            <li class="list-inline-item"><router-link to="/">Services</router-link></li>
            <li class="list-inline-item"><router-link to="/">About</router-link></li>
            <li class="list-inline-item"><router-link to="/">Terms</router-link></li>
            <li class="list-inline-item"><router-link to="/">Privacy Policy</router-link></li>
        </ul>
        <p class="copyright">Pide & Lahmacun © 2008</p>
    </footer>
</div>
</template>

<script>
export default {
  name:"footer",
}
</script>


<style lang="scss" scoped>

footer {
   
   left: 0;
   bottom: 0;
   width: 100%;
   text-align: center;
}
.footer-basic {
    padding:40px 0;
    background-color:#ffffff;
    color:#4b4c4d;
    margin-top:auto; 
    
  }
  
  .footer-basic ul {
    display: flex;
    justify-content: center;
    padding:0;
    list-style:none;
    text-align:center;
    font-size:18px;
    line-height:1.6;
    margin-bottom:0;
  }
  
  .footer-basic li {
    padding:0 10px;
  }
  
  .footer-basic ul a {
    color:inherit;
    text-decoration:none;
    opacity:0.8;
  }
  
  .footer-basic ul a:hover {
    opacity:1;
  }
  
  .footer-basic .social {
    text-align:center;
    padding-bottom:25px;
  }
  
  .footer-basic .social > a {
    font-size:24px;
    width:40px;
    height:40px;
    line-height:40px;
    display:inline-block;
    text-align:center;
    border-radius:50%;
    border:1px solid #ccc;
    margin:0 8px;
    color:inherit;
    opacity:0.75;
  }
  
  .footer-basic .social > a:hover {
    opacity:0.9;
  }
  
  .footer-basic .copyright {
    margin-top:15px;
    text-align:center;
    font-size:13px;
    color:#aaa;
    margin-bottom:0;
  }

  .icons {
    width: 24px ;
    height: 24px;
    
  }

  .socials {
    text-align: end;
  }
@media only screen and (max-width: 992px) {
    .footer-basic {
      display: none;
    }
  }

</style>