
<template>
    <div>
        <header>
            <h4>Question 1/3</h4>
            <div class="bar">
                <div class="completion"></div>
            </div>
        </header>
        <div>
            <question-text class="question-container">
                <h1 class="question">
                    What is the chemical value of table salt?
                </h1>
            </question-text>
            <answers-list class="options-container">
                <div class="option">
                    <p class="option-label">A</p>
                    <div class="option-value">
                        <p>NaCl</p>
                    </div>
                </div>
            </answers-list>

            <div class="results">
                <p>Your Results...</p>
                <h1>
                    4/8
                </h1>
            </div>

        </div>
    </div>
</template>

<style scoped>
header {
    margin-top: 20px;
}

header h4 {
    font-size: 30px;
}

.bar {
    width: 300px;
    height: 50px;
    border: 3px solid bisque;
}

.completion {
    height: 100%;
    width: 0%;
    background-color: bisque;
}

/* QUESTION */

.question-container {
    margin-top: 20px;
}

.question {
    font-size: 40px;
    margin-bottom: 20px;
}

.option {
    display: flex;
    margin-bottom: 20px;
    cursor: pointer;
}

.option-label {
    background-color: bisque;
    width: 50px;
    height: 50px;
    font-size: 30px;
    justify-content: center;
    align-items: center;
}

.option-value {
    background-color: rgb(244, 239, 239);
    width: 100%;
    font-size: 30px;
    padding: 0 20px;
}

/* RESULT */

.results {
    text-align: center;
    padding: 100px 0;
}

p {
    font-size: 25px;
}

h1 {
    font-size: 80px;
}
</style>