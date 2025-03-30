<template>
    <div id="column1">
        <div id="div-1">
            <h1>Explore Stunning Properties Near You!</h1>
        </div>
        <div id="div-2">
            <h1>
                Discover Homes That Match Your Lifestyle!
            </h1>
        </div>
        <div id="div-3">
            <h3>
                Explore the finest properties tailored to your
                needs. Whether <br />buying, selling, or investing,
                we make real estate simple, secure,<br /> and
                stress-free. Start your journey today!
            </h3>
        </div>
        <div id="div-4">
            <button>
                <a href="#">Explore More</a>
            </button>
        </div>
        <div id="div-5">
            <div id="section-1-info1">
                <div>
                    <h1>
                        128
                    </h1>
                    <h1>
                        K
                    </h1>
                </div>
                <div>
                    <h3>
                        Renters
                    </h3>
                </div>
            </div>
            <div id="section-1-info2">
                <div>
                    <h1>
                        300
                    </h1>
                    <h1>
                        +
                    </h1>
                </div>
                <div>
                    <h3>
                        Specislists
                    </h3>
                </div>
            </div>
            <div id="section-1-info3">
                <div>
                    <h1>
                        78
                    </h1>
                    <h1>
                        %
                    </h1>
                </div>
                <div>
                    <h3>
                        Yearly Growth
                    </h3>
                </div>
            </div>
            <div id="section-1-info4">
                <div>
                    <h1>
                        10
                    </h1>
                    <h1>
                        K+
                    </h1>
                </div>
                <div>
                    <h3>
                        Properties
                    </h3>
                </div>
            </div>
        </div>
    </div>
</template>

<script setup></script>

<style scoped>
#column1 {
    height: 100%;
    width: 48%;
    display: flex;
    justify-content: end;
    align-items: start;
    flex-direction: column;
    gap: 0.2rem;
}

#div-1 {
    height: 4%;
    width: 32%;
    display: flex;
    justify-content: start;
    align-items: center;
    border-bottom: 1px solid #6582AD;
    margin-bottom: 1rem;
}

#div-1 h1 {
    font-size: 0.8rem;
    font-weight: 400;
    color: #6582AD;
}

#div-2 {
    height: 48%;
    width: 100%;
    display: flex;
    justify-content: start;
    align-items: center;
}

#div-2 h1 {
    font-size: 5.7rem;
    font-weight: 400;
    margin-bottom: 1rem;
}

#div-3 {
    height: 7rem;
    width: 100%;
    display: flex;
    justify-content: start;
    align-items: end;
}

#div-3 h3 {
    font-size: 1.5rem;
    font-weight: 400;
    margin-bottom: 1rem;
}

#div-4 {
    height: 5rem;
    width: 100%;
    display: flex;
    justify-content: start;
    align-items: center;
}

#div-4 button {
    height: 3.5rem;
    width: 12rem;
    background-color: #6582AD;
    margin-left: 0.5rem;
    border: none;
    border-radius: 0.5rem;
}

#div-4 button a {
    text-decoration: none;
    color: white;
    font-size: 1.3rem;
    font-weight: 300;
    font-family: "Orbitron";
}

#div-4 button:hover {
    cursor: pointer;
}

#div-5 {
    height: 6rem;
    width: 100%;
    display: flex;
    justify-content: start;
    align-items: center;
    gap: 1rem;
    padding-left: 1rem;
}

#section-1-info1 {
    height: 90%;
    width: 23%;
}

#section-1-info1 div:nth-child(1) {
    height: 60%;
    width: 100%;
    display: flex;
    align-items: end;
}

#section-1-info1 div:nth-child(1) h1 {
    font-size: 2.5rem;
    font-weight: 400;
}

#section-1-info1 div:nth-child(1) h1:nth-child(2) {
    color: #6582AD;
}

#section-1-info1 div:nth-child(2) h3 {
    font-weight: 400;
    font-size: 1.3rem;
}

#section-1-info2 {
    height: 90%;
    width: 23%;
}

#section-1-info2 div:nth-child(1) {
    height: 60%;
    width: 100%;
    display: flex;
    align-items: end;
}

#section-1-info2 div:nth-child(1) h1 {
    font-size: 2.5rem;
    font-weight: 400;
}

#section-1-info2 div:nth-child(1) h1:nth-child(2) {
    color: #6582AD;
}

#section-1-info2 div:nth-child(2) h3 {
    font-weight: 400;
    font-size: 1.3rem;
}

#section-1-info3 {
    height: 90%;
    width: 23%;
}

#section-1-info3 div:nth-child(1) {
    height: 60%;
    width: 100%;
    display: flex;
    align-items: end;
}

#section-1-info3 div:nth-child(1) h1 {
    font-size: 2.5rem;
    font-weight: 400;
}

#section-1-info3 div:nth-child(1) h1:nth-child(2) {
    color: #6582AD;
}

#section-1-info3 div:nth-child(2) h3 {
    font-weight: 400;
    font-size: 1.3rem;
}

#section-1-info4 {
    height: 90%;
    width: 23%;
    padding-left: 1rem;
}

#section-1-info4 div:nth-child(1) {
    height: 60%;
    width: 100%;
    display: flex;
    align-items: end;
}

#section-1-info4 div:nth-child(1) h1 {
    font-size: 2.5rem;
    font-weight: 400;
}

#section-1-info4 div:nth-child(1) h1:nth-child(2) {
    color: #6582AD;
}

#section-1-info4 div:nth-child(2) h3 {
    font-weight: 400;
    font-size: 1.3rem;
}

</style>