# portifolio-dio-Marina
Desafio-Dio-Portifólio-Marina


/*------Body things-------------*/

body
{
    display: flex;
    flex-direction: column;
    background-color: var(--background-color);
    color:var(--font-color);
    font-family: "Roboto", sans-serif;
    transition: 1s;
}

/*-------Body Header Things-------*/
header
{
    position: sticky;
    top: 0;
/* background-color:var(--background-color) ;*/
    z-index: 999;
    width: 100%;
    height: 12%;
    display: flex;
    justify-content: space-between;
    border-bottom: 3.5px solid var(--line-color); 
    border-top: 0;
}
.top
{
    background-color: #6d41b5;
    margin-left: 1rem;
    padding: 1rem;
    display: flex;
    flex-direction: row;
    width: 100%;
    height: 30%;
}
.menu-top ul
{
    display: flex;
    flex-direction: row;
    gap: 5rem;
    font-family: "Oswald", sans-serif;
    justify-content: space-between;
    list-style: none;
    font-size: 1rem;
   font-weight: 900;
}
ul li
{
    transition: 0.6s;
}  
#Home:hover,
#Projects:hover,
#About:hover,
#Contact:hover
{
    cursor: pointer;
    font-weight: 800;
    /* font-size: 1.4rem;*/
    transform: scale(1.1);
    color: var(--constrast-color);
}
#logo-top
{
    transition: 1s;
    cursor: pointer;
    margin-left: 16.5rem;
}
#logo-top:hover
{
    transform: scale(1.1);
}
.icon-top
{
    color: var(--icon-color);
    font-size: 2rem;
    transition: 500ms;
    padding-left:34rem;
    cursor: pointer;
}
.icon-top:hover
{
    color: #581cfd;
    transition: 500ms;
}

/*-------Body Main Things---------*/

#icon-main 
{
    margin: 0;
    padding: 0;
    color:  #400cd1;
    font-size: 5.5rem;
    rotate: calc(+40deg);
    z-index:-1;
    position: absolute;
    margin-left: 800px;
    margin-top:180px;
    width: 20%;
    height: 10%;
}
.inital-phase
{
    font-weight: 600;
    width: 100%;
    padding: 5rem 20rem;
    display: flex;
    flex-direction: column;
    align-items: center;
    padding-bottom: 80px;
}
.inital-phase p
{
    display: flex;
    align-items: center;
    justify-content: center;
    transition: 2.4;
    margin-left: 30px;
    color:#ffffff;
    font-family: "Roboto";
    font-size: 20;
    font-weight: 800;
}
#part-one
{
    backface-visibility: visible;
    font-size:5rem;
    font-family: "Oswald", sans-serif;
    font-weight: 700;
}
#part-two
{
    font-family:Georgia, 'Times New Roman', Times, serif;
    font-size: 4rem;
    font-weight: 800;
    
}
#part-two:hover
{
    cursor: pointer;
    transition: 1s;
    transform:scale(1.1);
    color: var(--primary-color);
}


/*-------Description about me-----------*/

.details-about-me 
{
    gap: 2rem; 
    margin: 4rem;
    display: flex;
    justify-content: space-between;
    align-items: center;
    border-radius: 5rem;
    width: 90vw;
    height: 20vh;
    background-color:#303031e7;
    border: 3px solid black;
}
.descrition-about-me 
{
    display: flex;
}
.descrition-about-me p 
{
    width: 100%;
    padding:2.7rem;
    cursor: pointer;
    font-size: 1.4rem;
    font-family:'Times New Roman', Times, serif;
    background-color: var(--constrast-color);
    border-radius: 4rem;
    border: 2px solid #000000;
}
.descrition-about-me:hover
{
    color: #000000;
    transform: scale(1);
    transition: 1.4s;
    transform: perspective(solid);
}


.descrition-about-me-connect 
{
    gap: 4rem;
    display: flex;
    flex-direction: row;
    margin-left:1rem;
    margin-right: 0.70rem;
    margin-top: 3.5rem;
}
#gitHub-top-description,
#linkedin-top-description,
#email-top-description 
{
    font-size: 2rem;
    color: #ffffff75;
}
#gitHub-top-description:hover,
#linkedin-top-description:hover,
#email-top-description:hover,
#icon-arrow:hover
{
    color: #ffffff;
}

#ver-projetos
{
    margin-left: 5px;
    margin-bottom: 50px;
    cursor: pointer;
    width: 100%;
    padding: 10px;
    border-radius: 40px;
    font-family:"Roboto", sans-serif;
    font-weight: 600;
    background: linear-gradient(145deg, #bfa8ffc0, #9674f4d1);
    border: 2px solid black;
}
#ver-projetos:hover
{
    color: #000000;
    background-color: #630fff;
}

/*Body Main Video*/

.video-content iframe
{
    cursor: pointer;
    margin: 4rem;
    padding: 2%;
    margin-left:20rem;
    transition: 0.8s;
}
.video-content iframe:hover
{
    transform: scale(1.09);
}

 /*KNOWLEDGE  =====*/


.main-knowledge
{
   
    width: 100%;
}   
#word-knowledge
{
    display: flex;
    justify-content: center;
    margin-bottom: 2rem;
    margin-top: 2rem;
    width: 100%;
    font-size: 2.5rem;
    font-weight: 600;
    padding: 12px;
    color:#d3d3d3;
    border-radius: 100rem;
    border: 2px solid white;
    transition:  1s;
    font-family:Cambria, Cochin, Georgia, Times, 'Times New Roman', serif;
}
#word-knowledge:hover,
#knowledge-img:hover
{
    transform: scale(1.02);
    color: #ffffff;
    background-color: var(--background-color2); 
}
#knowledge-img
{
    cursor: pointer;
    transition: scale(1.1) 3s;
    margin-left: 10rem;
    margin-bottom: 2rem;
    margin-top: 2rem;
    transition: 1s;
    border: 4px solid #ffffff;
}











/*Projects*/

details
{
    display: flex;
    flex-direction: column;
    align-items: center;
    font-size: 4rem;
    justify-content: center;
    transition: 2s ease-in-out;
    padding: 2rem;
}
.main-projects
{
    margin-top: 2rem;
    margin-bottom:2rem;
    width: 100%;
    display: flex;
    flex-direction: column;
}
.main-projects h2
{
    font-size: 2.5rem;
    font-weight: 900;
    font-family: 'Elms Sans';
    display: flex;
    justify-content: center;
    color: #ffffff;
    margin-top: 8rem;
}
.main-projects summary
{
    border: 1px solid black;
    color: #cb71ff;
}
#laptop
{
    display: flex;
    justify-content: center;
    color: #5a6aa4;
    margin-bottom: 8rem;
    margin-left: 1rem;
    margin-top: 1.4rem;
    font-size: 5rem;
}
#laptop:hover
{
    cursor: pointer;
    color: #617ad6;
    transition: 1ms;
    transform: scale(1.1);
}


/*piano things*/

.piano-project
{
    display: flex;
    flex-direction: row;
    width: 100%;
    font-weight: 400;
    margin-bottom: 1rem;
    margin-bottom: 10rem;
    /*background-color: #617ad6;*/

}
#piano-project
{
    margin-bottom: 10rem;
}
.piano-project p
{
    margin: 1.1rem;
    margin-top: 0.20rem;
    font-size: 2rem;
    font-family:'Times New Roman', Times, serif;
}
#piano
{
    margin-left:1rem ;
    width: 25%;
    height: 10%;
    border: 2px solid white;
}



#landing-page
{
    width:20%;
}


























/*footer Things*/
footer
{
    font-family: "Roboto"; 
    font-weight: 400;
    padding-bottom: 0;
    width: 100vw;
    height: 20vh;
    transition: 1s;
    color: #ffffff;
    /*background-image: url('../images/header-image.png'); 
    border-image: 4px solid var(--line-color);*/
}
footer p
{
    color: var(--color);
    margin-bottom: 0;
    display: flex;
    justify-content: center;
}
footer:hover
{
    
    font-family: "Roboto"; 
    transform: scale(1.1);
}


