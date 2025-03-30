<template>
    <div class="Column1-div">
        <div class="aboutUs-data-div">
            <div class="mini-headline-div">
                <h1>About Us</h1>
            </div>
            <div class="sec4-headline-div">
                <h1>Your Trusted Real Estate Partner</h1>
            </div>
            <div class="sec4-para-div">
                <p>
                    We are committed to making your real estate journey<br />
                    smooth and stress-free. With years of experience and<br />
                    a client-first approach, we help buyers, sellers, and<br />
                    investors find the best opportunities in the market.<br />
                    Whether you're searching for your dream home or a<br />
                    profitable investment, we are here to guide you every<br />
                    step of the way
                </p>
            </div>
            <div class="sec4-list-data">
                <ul>
                    <li>
                        <h1>Expert Guidance:</h1>
                        <p>Our team provides professional advice <br />
                            to help you make informed decisions.</p>
                    </li>
                    <li>
                        <h1>Premium Listings:</h1>
                        <p>We offer handpicked properties in prime <br/>
                            locations.</p>
                    </li>
                    <li>
                        <h1>Seamless Transactions:</h1>
                        <p>Smooth and hassle-free buying, <br/>
                            selling, and renting process.</p>
                    </li>
                    <li>
                        <h1>Customer-Centric Approach:</h1>
                        <p>Your satisfaction is our top <br/>
                            priority.</p>
                    </li>
                    <li>
                        <h1>Market Insights:</h1>
                        <p>Get the latest real estate trends and <br/>
                            investment opportunities.</p>
                    </li>
                </ul>
            </div>
            <div class="bottom-headline-div">
                <h1>
                    Building Dreams, One 
                </h1>
                <h1>
                    Home at a Time
                </h1>
            </div>
            <div class="aboutUs-btn-div">
                <button><a href="#">Find Out More</a></button>
            </div>
        </div>
    </div>
</template>

<script setup></script>

<style scoped>
.Column1-div {
    height: 100%;
    width: 100%;
    background-color: #F3F8FA;
    border-radius: 1rem;
    padding: 0.8rem;
}

.aboutUs-data-div {
    height: 100%;
    width: 100%;
}

.mini-headline-div {
    height: 2.5rem;
    width: 100%;
    display: flex;
    justify-content: start;
    align-items: center;
}

.mini-headline-div h1 {
    font-size: 1.5rem;
    font-weight: 400;
    color: #6582AD;
    padding-bottom: 0.2rem;
    border-bottom: 1px solid #6582AD;
}

.sec4-headline-div {
    height: 8rem;
    width: 100%;
    display: flex;
    justify-content: start;
    align-items: center;
}

.sec4-headline-div h1 {
    font-size: 2.7rem;
    font-weight: 400;
}

.sec4-para-div {
    height: 11rem;
    width: 100%;
    display: flex;
    justify-content: start;
    align-items: center;
}

.sec4-para-div p {
    font-size: 1.1rem;
}

.sec4-list-data {
    height: 22rem;
    width: 100%;
    display: flex;
    justify-content: start;
    align-items: center;
    padding-left: 0.5rem;
    padding-bottom: 1rem;
}

.sec4-list-data ul li {
    display: flex;
    gap: 0.5rem;
    margin-top: 1.5rem;
}

.sec4-list-data ul li h1 {
    font-size: 1rem;
    font-weight: 500;
}

.sec4-list-data ul li p {
    margin-top: 0.1rem;
}

.bottom-headline-div {
    height: 7rem;
    width: 100%;
    display: flex;
    justify-content: center;
    align-items: start;
    flex-direction: column;
}

.bottom-headline-div h1:nth-child(1) {
    font-size: 2rem;
    font-weight: 500;
}

.bottom-headline-div h1:nth-child(2) {
    font-size: 2rem;
    font-weight: 400;
}

.aboutUs-btn-div {
    height: 3.8rem;
    width: 100%;
    display: flex;
    justify-content: start;
    align-items: center;
}

.aboutUs-btn-div button {
    height: 95%;
    width: 40%;
    background-color: #7696BB;
    border-radius: 0.5rem;
    border: none;
}

.aboutUs-btn-div button a {
    text-decoration: none;
    color: white;
    font-size: 1.5rem;
    font-family: "Orbitron";
}
</style>