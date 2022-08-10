<template>
    <div>
        <div class="rightOverlay ">
            <img src="https://picsum.photos/1024/250/?image=55" alt="Avatar" class="rightOverlay__Image">
            <div class="rightOverlay__content"><span class="rightOverlay__content__title">Lorem, ipsum.</span> Lorem ipsum dolor sit amet consectetur adipisicing elit. Natus, assumenda.</div>
        </div>
        <div class="leftOverlay ">
            <img src="https://picsum.photos/1024/250/?image=55" alt="Avatar" class="leftOverlay__Image">
            <div class="leftOverlay__content"><span class="leftOverlay__content__title">Lorem, ipsum.</span> Lorem ipsum dolor sit amet consectetur adipisicing elit. Natus, assumenda.</div>
        </div>
    </div>
</template>

<style scoped lang="scss">
.rightOverlay {
    position: relative; 
    text-align: end;
    display: flex;
    justify-content: flex-end;
    margin-bottom: 50px;

        .rightOverlay__Image {
        width: 100%;
        height: auto;
        }

        .rightOverlay__content {
        position: absolute; 
        display: flex;
        flex-direction: column;
        bottom: 20%; 
        color: #f1f1f1; 
        width: 100%;
        transition: .5s ease;
        opacity:1;
        color: white;
        font-size: 19px;
        padding: 20px;
        margin-right: 100px;
    

            .rightOverlay__content__title {
                color: #FF1E00;
                font-size: 38px;

                @media (max-width: 768px){
                    font-size: 32px;
                }
                @media (max-width: 520px){
                    font-size: 16px;
                }
            }

            @media (max-width: 768px){
                    font-size: 16px;

                }

            @media (max-width: 520px){
                    bottom: 5px;
                    
                }
            @media (max-width: 420px){
                    padding: 0;
                    font-size: 16px;
                }
            @media (max-width: 320px){
                    padding: 0;
                    font-size: 12px;
                }

            @media (max-width: 1281px){
                    margin-right: 0;
                }
        }
}
.leftOverlay {
    position: relative; 
    text-align: start;
    display: flex;
    justify-content: flex-start;
    margin-bottom: 50px;

        .leftOverlay__Image {
        width: 100%;
        height: auto;
        // transform: scaleX(-1);
        }

        .leftOverlay__content {
        position: absolute; 
        display: flex;
        flex-direction: column;
        bottom: 20%; 
        color: #f1f1f1; 
        width: 100%;
        transition: .5s ease;
        opacity:1;
        color: white;
        font-size: 19px;
        padding: 20px;
        margin-right: 100px;
    

            .leftOverlay__content__title {
                color: #FF1E00;
                font-size: 38px;

                @media (max-width: 768px){
                    font-size: 32px;
                }
                @media (max-width: 520px){
                    font-size: 16px;
                }
            }

            @media (max-width: 768px){
                    font-size: 16px;

                }

            @media (max-width: 520px){
                    bottom: 5px;
                    
                }
            @media (max-width: 420px){
                    padding: 0;
                    font-size: 16px;
                }
            @media (max-width: 320px){
                    padding: 0;
                    font-size: 12px;
                }

            @media (max-width: 1281px){
                    margin-right: 0;
                }
        }
}
// .leftOverlay {
//     position: relative; 
//     text-align: start;
//     display: flex;
//     justify-content: flex-start;
//     margin-bottom: 50px;

//         .leftOverlay__Image {
//         width: 100%;
//         height: auto;
//         }

//         .leftOverlay__content {
//         position: absolute; 
//         display: flex;
//         flex-direction: column;
//         bottom: 20%; 
//         color: #f1f1f1; 
//         width: 100%;
//         transition: .5s ease;
//         opacity:1;
//         color: white;
//         font-size: 19px;
//         padding: 20px;
//         margin-left: 100px;
    

//             .leftOverlay__content__title {
//                 color: #FF1E00;
//                 font-size: 38px;

//                 @media (max-width: 768px){
//                     font-size: 32px;
//                 }
//                 @media (max-width: 520px){
//                     font-size: 16px;
//                 }
//             }

//             @media (max-width: 768px){
//                     font-size: 16px;

//                 }

//             @media (max-width: 520px){
//                     bottom: 5px;
                    
//                 }
//             @media (max-width: 420px){
//                     padding: 0;
//                     font-size: 16px;
//                 }
//             @media (max-width: 320px){
//                     padding: 0;
//                     font-size: 12px;
//                 }

//             @media (max-width: 1281px){
//                     margin-left: 0;
//                 }
//         }
// }


</style>