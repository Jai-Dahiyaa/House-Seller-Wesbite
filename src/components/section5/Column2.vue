<template>
    <div class="column2-main-div">
        <div class="sec5-data-div">
            <div class="sec5-img-div"></div>
            <div class="sec5-column-data-div">
                <h1>Modern Suburban Retreat</h1>
                <p>
                    This elegant suburban home offers a perfect<br />
                    blend of style and comfort. With a spacious<br />
                    lawn, contemporary interiors, and a serene<br />
                    neighborhood, it's an ideal choice for families<br />
                    looking for a peaceful yet luxurious lifestyle.
                </p>
            </div>
        </div>
        <div class="sec5-data-div">
            <div class="sec5-img2-div"></div>
            <div class="sec5-column-data-div">
                <h1>Luxury Family Haven</h1>
                <p>
                    A stunning two-story house with a charming<br />
                    exterior and warm interiors. Located in a prime<br />
                    neighborhood, this home features modern<br />
                    architecture, a spacious driveway, and cozy<br />
                    lighting that welcomes you after a long day.
                </p>
            </div>
        </div>
        <div class="sec5-data-div">
            <div class="sec5-img3-div"></div>
            <div class="sec5-column-data-div">
                <h1>Seaside Villa Escape</h1>
                <p>
                    Experience breathtaking views and luxury living in<br/>
                    this modern seaside villa. Featuring sleek stone<br/>
                    architecture, large windows, and an open terrace<br/>
                    overlooking the ocean, this property is perfect for<br/>
                    those who crave tranquility and elegance.
                </p>
            </div>
        </div>
    </div>
</template>

<script setup></script>

<style scoped>
.column2-main-div {
    height: 100%;
    width: 79%;
    padding: 1rem;
    display: grid;
    grid-template-columns: repeat(3, 1fr);
    grid-template-rows: repeat(1, 1fr);
    gap: 1rem;
}

.sec5-data-div {
    height: 100%;
    width: 100%;
    border-radius: 1rem;
    box-shadow: 10px 10px 20px rgba(0, 0, 0, 0.233);
}

.sec5-img-div {
    height: 50%;
    width: 100%;
    border-radius: 1rem 1rem 0rem 0rem;
    background-image: url("../../assets/section5/img1.jpeg");
    background-position: center;
    background-repeat: no-repeat;
    background-size: cover;
}

.sec5-img2-div {
    height: 50%;
    width: 100%;
    border-radius: 1rem 1rem 0rem 0rem;
    background-image: url("../../assets/section5/img2.jpeg");
    background-position: center;
    background-repeat: no-repeat;
    background-size: cover;
}

.sec5-img3-div {
    height: 50%;
    width: 100%;
    border-radius: 1rem 1rem 0rem 0rem;
    background-image: url("../../assets/section5/img3.jpeg");
    background-position: center;
    background-repeat: no-repeat;
    background-size: cover;
}

.sec5-column-data-div {
    height: 50%;
    width: 100%;
    background-color: white;
    border-radius: 0rem 0rem 1rem 1rem;
    padding: 0.7rem;
}

.sec5-column-data-div h1 {
    font-size: 1.5rem;
    font-weight: 500;
}

.sec5-column-data-div p {
    margin-top: 1rem;
    font-size: 1rem;
}
</style>