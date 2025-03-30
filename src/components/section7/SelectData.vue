<template>
    <div class="property-select-option-div">
        <div class="select-option-div">
            <div id="icon-name">
                <IconBuilding stroke={2} id="build-icon"/>
                <h1>Property</h1>
            </div>
            <div id="icon">
                <IconChevronCompactDown stroke={2} id="icon2nd"/>
            </div>
        </div>
        <div class="select-option-div">
            <div id="icon-name">
                <IconMapPin stroke={2} id="build-icon"/>
                <h1>Location</h1>
            </div>
            <div id="icon">
                <IconChevronCompactDown stroke={2} id="icon2nd"/>
            </div>
        </div>
        <div class="select-option-div">
            <div id="icon-name">
                <IconCalendarWeek stroke={2} id="build-icon"/>
                <h1>Date</h1>
            </div>
            <div id="icon">
                <IconChevronCompactDown stroke={2} id="icon2nd"/>
            </div>
        </div>
        <div class="select-option-div">
            <div id="icon-name">
                <IconWallet stroke={2} id="build-icon"/>
                <h1>Price</h1>
            </div>
            <div id="icon">
                <IconChevronCompactDown stroke={2} id="icon2nd"/>
            </div>
        </div>
    </div>
</template>

<script setup>
import { IconBuilding } from '@tabler/icons-vue';
import { IconChevronCompactDown } from '@tabler/icons-vue';
import { IconMapPin } from '@tabler/icons-vue';
import { IconCalendarWeek } from '@tabler/icons-vue';
import { IconWallet } from '@tabler/icons-vue';
</script>

<style scoped>
.property-select-option-div {
    height: 20%;
    width: 100%;
    display: grid;
    grid-template-columns: repeat(4, 1fr);
    grid-template-rows: repeat(1, 1fr);
    padding: 1rem;
    gap: 1rem;
    justify-content: center;
    align-items: center;
}

.select-option-div {
    height: 80%;
    width: 100%;
    background-color: white;
    border-radius: 50rem;
    padding: 0rem 1.5rem;
    display: flex;
}

#icon-name {
    height: 100%;
    width: 75%;
    display: flex;
    justify-content: start;
    align-items: center;
    gap: 0.5rem;
}

#build-icon {
    height: 1.7rem;
    width: 1.7rem;
    color: black;
}

#icon-name h1 {
    font-size: 1.3rem;
    font-weight: 400;
}

#icon {
    height: 100%;
    width: 25%;
    display: flex;
    justify-content: end;
    align-items: center;
}

#icon2nd {
    height: 1.8rem;
    width: 1.8rem;
    color: black;
}
</style>