# tienbilog.github.io# tienbilog.github.io
            mainText.textContent = "Yay! I love you babi! See you on Friday :3";
            yesButton.classList.add('hidden');
            noButton.classList.add('hidden');
        });

        noButton.addEventListener('click', () => {
            mainGif.src = "https://i.pinimg.com/originals/f0/61/c1/f061c18854fe28120ed76c9e03002937.gif";
            mainText.textContent = "u no love me na";
            yesButton.classList.add('hidden');
            noButton.classList.add('hidden');
            setTimeout(() => {
                mainGif.src = "https://media.tenor.com/TyrY0krJG3kAAAAj/milk-and-mocha.gif";
                mainText.textContent = "Hi babi! Will you be my Valentine?";
                yesButton.classList.remove('hidden');
                noButton.classList.remove('hidden');
            }, 3000); // Redirect back after 3 seconds
        });
    </script>
</body>
</html>