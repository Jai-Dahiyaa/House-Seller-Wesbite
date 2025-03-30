<template>
    <div class="column2-div">
        <div class="column2-div-info">
            <div class="Faq-headline">
                <h1>FAQs</h1>
            </div>
            <div class="faqs-all-question-div">
                <div class="ques-div">
                    <h1>How do I find the perfect property?</h1>
                </div>
                <div class="ques-div">
                    <h1>Do you offer rental properties?</h1>
                </div>
                <div class="ques-div">
                    <h1>How can I schedule a property visit?</h1>
                </div>
                <div class="ques-div">
                    <h1>Can I schedule a virtual property tour?</h1>
                </div>
                <div class="ques-div">
                    <h1>How long does the buying process take? </h1>
                </div>
                <div class="ques-div">
                    <h1>Can I sell my property through you?</h1>
                </div>
                <div class="ques-div">
                    <h1>How do I find rental properties nearby?</h1>
                </div>
                <div class="ques-div">
                    <h1>How do I schedule a property visit?</h1>
                </div>
            </div>
        </div>
    </div>
</template>

<script setup></script>

<style scoped>
.column2-div {
    height: 100%;
    width: 50%;
    display: flex;
    justify-content: center;
    align-items: center;
}

.column2-div-info {
    height: 96%;
    width: 98%;
    padding: 1rem;
}

.Faq-headline {
    height: 10%;
    width: 100%;
    display: flex;
    justify-content: start;
    align-items: center;
}

.Faq-headline h1 {
    font-size: 3rem;
    font-weight: 400;
    border-bottom: 2px solid #6582AD;
}

.faqs-all-question-div {
    height: 90%;
    width: 100%;
    display: flex;
    flex-direction: column;
    gap: 1rem;
    padding: 0.5rem;
}

.ques-div {
    height: 15%;
    width: 100%;
    display: flex;
    justify-content: start;
    align-items: center;
    padding: 0.5rem;
    border-bottom: 1px solid #6582AD;
}

.ques-div h1 {
    font-size: 2rem;
    font-weight: 500;
}

.ques-div:hover {
    cursor: pointer;
}
</style>