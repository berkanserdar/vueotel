<template>
    <div>
        <div class="overlayImage">
            <img src="https://picsum.photos/1024/250/?image=55" alt="Avatar" class="image">
            <div class="overlay"><span class="overlay__title">Lorem, ipsum.</span> <br>Lorem ipsum dolor sit amet consectetur adipisicing elit. Natus, assumenda.</div>
        </div>
    </div>
</template>

<style scoped lang="scss">
.overlayImage {
    position: relative; 
    text-align: end;
}
.image {
    width: 100%;
    height: auto;
}
.overlay {

    position: absolute; 
    bottom: 20%; 
    color: #f1f1f1; 
    width: 100%;
    transition: .5s ease;
    opacity:1;
    color: white;
    font-size: 19px;
    padding: 20px;
  

    .overlay__title {
        color: #FF1E00;
        font-size: 38px;
        @media (max-width: 720px){
            font-size: 32px;
        }
        @media (max-width: 500px){
            
        }
    }
    @media (max-width: 720px){
            font-size: 16px;

        }
    @media (max-width: 500px){
            bottom: -18px;
        }
}
</style>