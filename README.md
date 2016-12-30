# Website Performance Optimization portfolio project

## Step to run the project
1. Fork the project. 
2. Host it locally and use python or NodeJS to start the server.
3. Use ngrok to make it accessible to the Internet.
4. Use Google PageSpeed to rank the index-src.html (the un-uglified version)

## Optimizations made to main.js
1. Dynamically calculate number of sliding pizza should be shown based on Windows size (Height). 
2. Refactor the slider function: Get randomPizzas element before looping.
3. Refactor the slider function: Use width percentage instead of fixed pixel.
4. Avoid to get pizzasDiv for each iteration.