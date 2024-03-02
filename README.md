# Csss
Create a website css 
*{
    margin: 0;
    font-family: Arial;
    border: border-box;
}

.nvabar {
    height: 60px;
    background-color: #0f1111;
    color: white;
    display: flex;
    align-items: center; 
    justify-content: space-evenly;
}

.nav-logo {
    height:50px;
    width: 100px;
}

.logo {
    background-image: url("amazon_logo.png");
    background-size: cover;
    height: 50px;
    width: 100px;
}

.border {
    border: 2px solid transparent;
}

.border:hover {
    border: 1.5px solid white;
}

/** box2 **/
.add-first {
    color: #cccccc ;
    font-size: 0.85rem;
    margin-left: 15px;
}

.add-sec {
    font-size: 1rem;
    margin-left: 3px;
}

.add-icon {
    display: flex;
    align-items: center;
}

/** box3 **/
.nav-search {
    display: flex;
    justify-content: space-evenly;
    background-color:#e7a652;
    width: 400px;
    height: 40px;
    border-radius: 4px;
    
}

.search-select {
    background-color: #fef3ff;
    width: 55px;
    text-align: center;
    border-top-left-radius: 4px;
    border-bottom-left-radius: 4px;
    border: none;
}

.search-input {
    width: 100%;
    font-size: 1rem;
    border: none;
}

.search-icon {
    width: 55px;
    display: flex;
    justify-content: center;
    align-items: center;
    font-size: 1.2rem;
    background-color: #febd68;
    border-top-right-radius: 4px;
    border-bottom-right-radius: 4px;
     
}

.nav-search:hover {
    border: 2px solid orange;

}

/**box4**/
span {
    font-size: 0.7rem;
}

.nav-second {
    font-size: 0.85rem;
    font-weight: 700;
}

/** box6 **/
.nav-cart i {
    font-size: 30px;

}

.nav-cart {
    font-size: 0.85rem;
    font-weight: 700;
}

/** pannel **/
.pannel {
    height: 40px;
    background-color: #222f3d;
    display: flex;
    color: white;
    align-items: center;
    justify-content: space-evenly;
}

.pannel-ops p {
    display: inline;
    margin-left: 10px;

}

.pannel-ops {
    width: 70%;
    font-size: 0.85rem;
}

.pannel-deals {
    font-size: 0.9rem;
    font-weight: 700;
}

/** hero section **/
.hero-section {
    background-image: url("hero_image.jpg");
    background-size: cover;
    height: 380px;
    display: flex;
    justify-content: center;
    align-items: flex-end;
    
}

.hero-msg {
    background-color: white;
    color: black;
    height: 40px;
    display: flex;
    justify-content: center;
    align-items: center;
    font-size: 0.85rem;
    width: 80%;
    margin-bottom: 25px;
}

.hero-msg a {
    color: #007100;
}

/** shop section **/
.shop-section {
    display: flex;
    flex-wrap: wrap;
    justify-content: space-evenly;
    background-color: #e2e7e6;
}

.box {
    /* border: 2px solid black; */
    height: 400px;
    width: 23%;
    background-color: white;
    padding: 20px 0px 15px;
    margin-top: 15px;
}

.box-img {
    height: 300px;
    background-size: cover;
    margin-top: 1rem;
    margin-bottom: 1rem;
}

.box-content {
    margin-left: 1rem;
    margin-right: 1rem;
}

.box-content p {
    color: #007185;
}

/** footer **/
footer {
    margin-top: 15px;
}
.foot-pannel1 {
    background-color: #37475a;
    color:white ;
    height: 50px;
    display: flex;
    justify-content: center;
    align-items: center;
    font-size: 0.85rem;
}

.foot-pannel2 {
    background-color: #222f3d;
    color: white;
    height: 300px;
    display: flex;
    justify-content: space-evenly;
    


}

ul {
    margin-top: 20px;
}

ul a {
    display: block;
    font-size: 0.85rem;
    margin-top: 10px;
    color: #dddddd;
}

.foot-pannel3 {
    background-color: #222f3d;
    color: white;
    border: 0.5px solid white;
    height: 70px;
    display: flex;
    justify-content: center;
    align-items: center;
}

.logo {
    background-image: url("amazon_logo.png");
    background-size: cover;
    height: 50px;
    width: 100px;
    
}

.foot-pannel4 {
    background-color: #0f1111;
    color: white;
    height: 80px;
    font-size: 0.7rem;
    text-align: center;
}

.pages {
    padding-top: 25px;
}

.copyright {  
    padding-top: 5px;
}
