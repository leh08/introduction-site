<template>
    <div>
        <div class="row" id="section1">
            <div class="col-12">
                <div class="card text-center">
                    <div class="card-img">
                        <video playsinline muted loop id="myVideo" src="@/assests/videos/video.mp4" poster>          
                        </video>
                    </div>
                    <div class="card-img-overlay" id="textIntrodutionVideo">
                        <div class="text-light"><h1>There is no other platforms</h1>
                        <h1>for you as like</h1></div>
                        
                        <div class="btn btn-secondary mb-3" id="playButtonIntroduction" @click="playIntrodution">Play</div>
                        <br>
                        <NuxtLink class="btn px-3" id="tryNowButton" to="#">TRY NOW</NuxtLink>
                        
                    </div>
                </div>
            </div>  
        </div>
        <div class="row" id="section2">
            <div class="col-12 col-md-8 bg-white">
                <div id="textCard">
                    <h5 style="color: #ef3265">NEW DESIGN</h5>
                    <h1>There is no other platforms for you as like <span style="color:#ef3265">....</span></h1>
                    <p>Lorem ipsum, dolor sit amet consectetur adipisicing elit. Odio quas qui, recusandae deserunt ullam autem possimus quae dolores nisi dicta corrupti maiores dolor, neque magni accusantium. Ex voluptatem soluta esse!</p>
                    <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Consequatur quae odit labore sequi quasi atque maiores nisi doloremque modi in.</p>    
                </div>
                
            </div>
            <div class="col-12 col-md-4">
                <div id="section2Image">
                    <img id="myImage" src="@/assests/images/unsplash-image-RdKtv4gvDJ8.jpeg" alt="Snow in Switzerland" width="100%">
                    <div class="image-overlay"></div>
                </div>
                
            </div>
        </div>
        <div class="row" id="section3">
            <div class="col-12">
                <div class="text-center mt-5 text-white">
                    <h5 style="color: #ef3265">NEW FEATURES</h5>
                    <h2>Some awesome features</h2>
                </div>
            </div>
            <div class="row text-center text-white my-5" id="featureCards">
                <div class="col-12 col-md-4">
                    <i class="fa-light fa-images"></i>
                    <h4>Some awesome features</h4>
                    <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Non voluptas nisi, eius magnam dolor quia molestiae quod quaerat ea est?</p>
                </div> 
                <div class="col-12 col-md-4">
                    <i class="fa-duotone fa-images"></i>
                    <h4>Some awesome features</h4>
                    <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Non voluptas nisi, eius magnam dolor quia molestiae quod quaerat ea est?</p>
                </div>  
                <div class="col-12 col-md-4">
                    <i class="fa-duotone fa-images"></i>
                    <h4>Some awesome features</h4>
                    <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Non voluptas nisi, eius magnam dolor quia molestiae quod quaerat ea est?</p>
                </div>  
            </div>
        </div>
        <div class="row align-items-center" id="section4">
            <div class="col-12 col-md-6">
                <img src="@/assests/images/pr-m1x-2110211228.png" style="width:100%;">
            </div>
            <div class="col-12 col-md-6" id="section4TextCard">
                <div>
                    <h5 style="color: #ef3265">NEW DESIGN</h5>
                    <h2>Responsive design, just need your tap <span style="color:#ef3265">....</span></h2>
                    <p>Lorem ipsum dolor, sit amet consectetur adipisicing elit. Rem minus voluptates sint velit libero vero non distinctio culpa. Perspiciatis, impedit?</p>
                </div>
                
            </div>
            <div id="clipPath"></div>
        </div>
        <div class="row align-items-center" id="section5">
            <div class="col-12 col-md-4 text-center my-5 text-light">
                <img class="rounded-circle" src="@/assests/images/20210220_131445.jpg" width="80px" height="80px" alt="Avatar">
                <h5 class="mt-3">Giang Le</h5>
                <h6 style="color:#ef3265">Frontend Developer</h6>
                <p class="m-4">"Lorem ipsum dolor sit amet consectetur, adipisicing elit. Neque eveniet consequatur possimus dolor ipsam, quae labore illo excepturi aliquam sequi."</p>
            </div>
            <div class="col-12 col-md-4 text-center my-5 text-light">
                <img class="rounded-circle" src="@/assests/images/20210220_131445.jpg" width="80px" height="80px" alt="Avatar">
                <h5 class="mt-3">Giang Le</h5>
                <h6 style="color:#ef3265">Frontend Developer</h6>
                <p class="m-4">"Lorem ipsum dolor sit amet consectetur, adipisicing elit. Neque eveniet consequatur possimus dolor ipsam, quae labore illo excepturi aliquam sequi."</p>
            </div>
            <div class="col-12 col-md-4 text-center my-5 text-light">
                <img class="rounded-circle" src="@/assests/images/20210220_131445.jpg" width="80px" height="80px" alt="Avatar">
                <h5 class="mt-3">Giang Le</h5>
                <h6 style="color:#ef3265">Frontend Developer</h6>
                <p class="m-4">"Lorem ipsum dolor sit amet consectetur, adipisicing elit. Neque eveniet consequatur possimus dolor ipsam, quae labore illo excepturi aliquam sequi."</p>
            </div>
            <div class="col-12 mb-5">
                <div class="d-flex flex-wrap justify-content-around" >
                    <img class="logo-img" src="@/assests/images/logos/New_Balance_logo.svg" width="100px" height="100px">
                    <img class="logo-img" src="@/assests/images/logos/Allbirds_logo.svg" width="100px" height="100px">
                    <img class="logo-img" src="@/assests/images/logos/Adidas_Logo.svg" width="100px" height="100px">
                    <img class="logo-img" src="@/assests/images/logos/puma-logo-logo.svg" width="100px" height="100px">
                    <img class="logo-img" src="@/assests/images/logos/Reebok_2019_logo.svg" width="100px" height="100px">
                </div>
            </div>
        </div>
        <div class="row text-center" id="section6">
            <div class="col-12 mt-5">
                <h6 style="color:#ef3265">NEW FEATURES</h6>
                <h4>Some awesome features</h4>
                <div class="section6CenterText mx-auto my-4 text-secondary">
                    <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Quasi laboriosam exercitationem consequuntur laudantium illo cumque placeat similique tempore nesciunt ut amet tempora sint nobis, atque id qui odit obcaecati rerum ad. Laboriosam commodi tenetur provident, ratione, molestias a inventore quos autem, culpa dolorum labore ipsa enim accusamus vero velit voluptatem.</p>
                </div>
            </div>
            <div class="col-12">
                <img id="myBrowserImage" src="@/assests/images/istockphoto-537827790-612x612.jpeg" width="612px">
            </div>
        </div>
        <div class="row text-center text-light" id="section7">
            <div class="col-12 my-5">
                <h6 style="color:#ef3265">NEW FEATURES</h6>
                <h4>Over 1000 designers are using ...</h4>
            </div>
            <div class="col-12">
                <form class="form-inline mx-5">
                    <label class="sr-only" for="inlineFormInputName2">Name</label>
                    <input type="text" class="form-control mb-2 mr-sm-2" id="inlineFormInputName2" placeholder="Jane Doe">
                    <label class="sr-only" for="inlineFormInputGroupUsername2">Username</label>
                    <div class="input-group mb-2 mr-sm-2">
                        <div class="input-group-prepend">
                        <div class="input-group-text">@</div>
                        </div>
                        <input type="text" class="form-control" id="inlineFormInputGroupUsername2" placeholder="Username">
                    </div>

                    <div class="form-check mb-2 mr-sm-2">
                        <input class="form-check-input" type="checkbox" id="inlineFormCheck">
                        <label class="form-check-label" for="inlineFormCheck">
                        Remember me
                        </label>
                    </div>

                    <button type="submit" class="btn mb-2" style="width: 200px; background-color: #ef3265" >Submit</button>
                </form>
            </div>
            
        </div>
    </div>
</template>
<style >
#textIntrodutionVideo {
    top: 250px;
    
}
#myVideo {
    object-fit: cover;
}
#tryNowButton {
    background-color: #ef3265;
    color: white;
}
#textCard {
    position: relative;
    top: 100px;
    left: 20px;
    margin-bottom: 50px;
}
#section2Image {
    position: relative;
    width: 100%;
}

.image-overlay {
    position: absolute;
    bottom: 0;
    right: 0;
    margin: 0;
    background-color: #ef3265;
    opacity: 0.5;
    width: 100px;
    height: 200px;

}
#section3 {
    background-image: url("@/assests/images/top-view-arrangement-natural-material-stationery_23-2148898233.jpeg");
}
#featureCards {
    justify-content: center;
}
#section4 {
    position: relative;
    height: 500px;
}
#clipPath {
    position: absolute;
    background-color:#ef3265;
    height: 100%;
    opacity: 0.5;
    clip-path: polygon(100% 40%, 20% 100%, 100% 100%);
    z-index: 1;
}
#profileImage {
    border-radius: 100%
}
#section5 {
    background-image: url("@/assests/images/360_F_116219403_MMOSh3qN2Tns8wnc3S8PSmXEmsXp50DH.jpeg");
    background-repeat: no-repeat;
    background-size: cover;
    background-position: center;
}
.logo-img path {
    fill: rgb(118, 117, 117);
    
}
#section6 {
    height: 500px;
}
.section6CenterText {
    width: 600px;
}
#myBrowserImage {
    position: absolute;
    margin-left: auto;
    margin-right: auto;
    left: 0;
    right: 0;
    text-align: center;
    transform: translateY(-20%);
    z-index: -1;
}
#section7 {
    background-color: #3e37c7;
    height: 400px;
}
</style>
<script>
export default {
    methods: {
        playIntrodution() {
            const myVideo = document.getElementById("myVideo")
            myVideo.play()
        }
    },
    async asyncData(context) {

    },
};
</script>

