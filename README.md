<div align="center">
   <img width=100% src=https://capsule-render.vercel.app/api?type=waving&height=100&color=gradient&reversal=true />
</div>

## Hello, welcome <img height="40" src="https://emoji.gg/assets/emoji/7333-parrotdance.gif">

<style>
   .profile{
    container-type: inline-size ;
    container-name: profile;
}

.profile-wrapper{
    display: flex;
    flex-direction: column;
    justify-content: center;
    margin: auto;
    background-color: white;
    max-width: 1400px;
}
.profile_data-container{
    max-width: 600px;
    padding: 30px;
}

.profile_img-container{
    max-height: 700px;
    overflow: hidden;
}

.profile_img{
    max-width: 100%;
    width: 600px;
}

h1{
    color: #6e5016;
}

.profile_skills-container h2{
    color: #6e5016;
}
.profile_skill{
    list-style: none;
    display: flex;
    margin: 10px ;
    max-width: 600px;
    margin-left: 0;
    align-items: center;
}

.load_bar{
    border: 2px solid  #d49c2c ;
    border-radius: 8px;
    color: #ffffff;
    padding: 2px;
    font-size: 12px;
    width: 80%;
    margin: 4px;
    margin-left: 0;
}

.load_bar--bar{
    background-color:#d49c2c ;
    border-radius: 5px;
    padding: 4px 7px;

}

.bar--80{
    width: 80%;
}

.bar--60{
    width: 60%;
}

.bar--50{
    width: 50%;
}

.bar--90{
    width: 90%;
}

/*------------PROFILE QUERIS------------*/

@container profile (min-width:720px){
    .profile-wrapper{
        flex-direction: row;
        padding: 20px;
        background-color: transparent;
        height: 90vh;
        margin: auto;
    }

    h1{
        margin: 0;
        font-size: 4rem;
        text-wrap: balance;
    }
    
    .profile_data-container{
        border-radius: 0 25px 25px 0;
        display: flex;
        align-items: center;
        background-color: white;
        box-shadow: 0 0 9px 0 #0004;
    }
    .profile-data{
        max-width: 520px;
    }

    .profile_img{
        height: 100%;
        object-fit:cover;
        width: 600px;
    }
    .profile_img-container{
        max-height:initial   ;
        
        border-radius: 25px 0 0 25px;
    }
}
</style>
<div class="profile_data-container">
                <div class="profile-data">
                    <div class="profile-description">
                        <h1>¿Quien es ado?</h1>
                        <p>Lorem, ipsum dolor sit amet consectetur adipisicing elit. Repellat voluptates officiis minus unde, nesciunt adipisci illo amet laborum alias, accusamus quaerat numquam assumenda obcaecati itaque delectus dolorem nam consequuntur! Aliquid.</p>
                    </div>
                    <div class="profile_skills-container">
                        <h2>Skills</h2>
                        <ul>
                            <li class="profile_skill">
                                <div class="load_bar">
                                    <div class="load_bar--bar bar--80">
                                        80%
                                    </div>
                                </div>
                                <span class="profile_skill-name">HTML</span>
                            </li>
                            <li class="profile_skill">
                                <div class="load_bar">
                                    <div class="load_bar--bar bar--60">
                                        60%
                                    </div>
                                </div>
                                <span class="profile_skill-name">CSS</span>
                            </li>
                            <li class="profile_skill">
                                <div class="load_bar">
                                    <div class="load_bar--bar bar--50">
                                        50%
                                    </div>
                                </div>
                                <span class="profile_skill-name">Python</span>
                            </li>
                            <li class="profile_skill">
                                <div class="load_bar">
                                    <div class="load_bar--bar bar--90">
                                        90%
                                    </div>
                                </div>
                                <span class="profile_skill-name">SQl</span>
                            </li>
                        </ul>
                    </div>
                </div>
            </div>
        </div>
