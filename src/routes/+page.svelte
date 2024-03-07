<section>
    <div class="img-text-container">
        <img src="/images/About me Pic.JPG" alt="This is Aidan Roig">
        <div class="text">
            <h2>Hello! I'm Aidan Roig</h2>
            <p>I am a software engineering major at the University of Arizona. 
            I currently live in Tucson, Arizona, but I originally grew up in Flagstaff, Arizona.
            </p>
            <p>Throughout this portfolio I hope to express my strong drive to gain experience and make an
            impact working in the tech industry. I am a great leader, but most importantly I have a
            great work ethic which allows me to overcome any obstacles in order to reach my goals.
            </p>
        </div>
    </div>
</section>

<style>
    * {
        margin: 0;
        padding: 0;
    }

    section {
        background-image: linear-gradient(#292526, black, #292526);
        padding: 2% 5%;
    }

    .img-text-container {
        display: flex;
        align-items: center;
        margin: 30px;
        flex-wrap: wrap;
    }

    h2 {
        color: #de9e48;
        font-size: 30px;
        margin: 10px 0;
    }

    img {
        flex-basis: 250px;
        flex-grow: 1;
        margin: 2% 5%;
        max-height: 500px;
        width: 50%;
        max-width: 500px;
        object-fit: cover;
        border-radius: 50%;
    }

    .img-text-container .text {
        flex-basis: 250px;
        flex-grow: 1;
        margin: 2% 5%;
    }

    p {
        color: white;
        margin: 10px 0;
    }

</style>