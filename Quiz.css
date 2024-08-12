function submitQuiz() {
    const quizForm = document.getElementById('quizForm');
    const resultDiv = document.getElementById('result');
    let score = 0;

    const correctAnswers = {
        q1: 'b',
        q2: 'b',
        q3: 'a',
        q4: 'b',
        q5: 'b',
        q6: 'a',
        q7: 'b',
        q8: 'a',
        q9: 'c',
        q10: 'b'
    };

    const formData = new FormData(quizForm);

    for (let [question, answer] of formData.entries()) {
        if (correctAnswers[question] === answer) {
            score++;
        }
    }

    resultDiv.innerHTML = `Você acertou ${score} de 10 perguntas.`;

    if (score === 10) {
        resultDiv.innerHTML += "<br>Parabéns! Você é um mestre em ética digital!";
    } else if (score >= 7) {
        resultDiv.innerHTML += "<br>Ótimo trabalho! Você tem um bom entendimento sobre ética digital.";
    } else if (score >= 4) {
        resultDiv.innerHTML += "<br>Você tem um conhecimento razoável sobre ética digital, mas pode melhorar.";
    } else {
        resultDiv.innerHTML += "<br>Você precisa estudar mais sobre ética digital.";
    }
}
