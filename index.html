<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>imágenes.Fabio.GeminiAi</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Inter:wght@400;500;700&display=swap');
        body {
            font-family: 'Inter', sans-serif;
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: space-between;
            min-height: 100vh;
            margin: 0;
            background: linear-gradient(135deg, #6B73FF 0%, #000DFF 100%);
            color: #333;
            padding: 1rem;
            box-sizing: border-box;
        }
        .content-card {
            background-color: rgba(255, 255, 255, 0.95); /* Slightly more opaque */
            padding: 2rem;
            border-radius: 1rem;
            box-shadow: 0 10px 25px rgba(0, 0, 0, 0.2);
            text-align: center;
            width: 100%;
            max-width: 700px; /* Increased max width */
            margin-top: 2rem;
        }
        .title-text {
            font-size: 2.5rem;
            font-weight: 700;
            color: #1a202c;
            margin-bottom: 1rem; /* Adjusted margin */
            background: -webkit-linear-gradient(45deg, #f92b7a, #2b57f9);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
        }
        .subtitle-text {
            margin-bottom: 1.5rem;
            color: #4a5568; /* Slightly darker subtitle */
            font-size: 1.1rem;
        }
        .button-group {
            display: flex;
            flex-direction: column; /* Stack buttons on small screens */
            gap: 0.75rem; /* Space between buttons */
            margin-bottom: 1.5rem;
            align-items: center; /* Center buttons */
        }
        @media (min-width: 640px) { /* sm breakpoint in Tailwind */
            .button-group {
                flex-direction: row; /* Buttons side-by-side on larger screens */
                justify-content: center;
            }
        }
        .fabio-button, .gemini-button {
            color: white;
            font-weight: bold;
            padding: 0.75rem 1.5rem;
            border-radius: 0.5rem;
            border: none;
            cursor: pointer;
            transition: all 0.3s ease;
            width: auto; /* Adjust width automatically */
            min-width: 220px; /* Minimum width for buttons */
        }
        .fabio-button {
            background: linear-gradient(90deg, #FF2B7A 0%, #FF8C42 100%);
            box-shadow: 0 4px 15px rgba(255, 43, 122, 0.4);
        }
        .fabio-button:hover {
            transform: translateY(-2px) scale(1.05);
            box-shadow: 0 6px 20px rgba(255, 43, 122, 0.5);
        }
        .gemini-button {
            background: linear-gradient(90deg, #4A90E2 0%, #50E3C2 100%); /* Gemini button gradient */
            box-shadow: 0 4px 15px rgba(74, 144, 226, 0.4);
        }
        .gemini-button:hover {
            transform: translateY(-2px) scale(1.05);
            box-shadow: 0 6px 20px rgba(74, 144, 226, 0.5);
        }
        .fabio-button:active, .gemini-button:active {
            transform: translateY(0px) scale(1);
        }
        .fabio-button:disabled, .gemini-button:disabled {
            background: #ccc;
            cursor: not-allowed;
            box-shadow: none;
            transform: none;
        }
        #promptInput {
            width: 100%;
            padding: 0.75rem;
            margin-bottom: 1.5rem;
            border: 1px solid #cbd5e0; /* Tailwind gray-300 */
            border-radius: 0.5rem;
            font-size: 1rem;
            box-sizing: border-box;
            background-color: #f7fafc; /* Tailwind gray-100 */
        }
        #imageContainer img {
            margin-top: 1.5rem;
            border-radius: 0.75rem;
            max-width: 100%;
            height: auto;
            border: 3px solid #eee;
            box-shadow: 0 4px 10px rgba(0,0,0,0.1);
        }
        #loadingIndicator, #promptLoadingIndicator {
            margin-top: 1rem;
            color: #555;
            display: flex; /* Use flex for centering spinner and text */
            flex-direction: column;
            align-items: center;
        }
        .spinner {
            border: 4px solid rgba(0, 0, 0, 0.1);
            width: 36px;
            height: 36px;
            border-radius: 50%;
            animation: spin 1s ease infinite;
            margin-bottom: 0.5rem; /* Space between spinner and text */
        }
        .fabio-spinner { border-left-color: #FF2B7A; }
        .gemini-spinner { border-left-color: #4A90E2; }
        @keyframes spin {
            0% { transform: rotate(0deg); }
            100% { transform: rotate(360deg); }
        }
        #errorMessage {
            color: #D32F2F;
            background-color: #FFCDD2;
            border: 1px solid #EF9A9A;
            padding: 0.75rem;
            border-radius: 0.5rem;
            margin-top: 1rem;
            display: none;
        }
        footer {
            margin-top: auto;
            padding: 1rem;
            text-align: center;
            color: rgba(255, 255, 255, 0.8);
            font-size: 0.9rem;
        }
    </style>
</head>
<body>
    <div class="content-card">
        <h1 class="title-text">imágenes.Fabio.GeminiAi</h1>
        <p class="subtitle-text">Crea imágenes únicas con el poder de la IA. ¡Prueba a generar un prompt creativo con Gemini!</p>
        
        <div class="mb-4">
            <label for="promptInput" class="block text-sm font-medium text-gray-700 mb-1 text-left">Prompt para la imagen:</label>
            <textarea id="promptInput" rows="3" placeholder="Escribe tu prompt aquí o deja que Gemini sugiera uno..."></textarea>
        </div>

        <div class="button-group">
            <button id="suggestPromptButton" class="gemini-button">
                ✨ Sugerir Prompt Creativo
            </button>
            <button id="generateImageButton" class="fabio-button">
                Crear imagen hecha por FabioAI
            </button>
        </div>
         <div class="button-group">
             <button id="describeImageButton" class="gemini-button" disabled title="Próximamente">
                ✨ Describir Imagen (Próximamente)
            </button>
        </div>


        <div id="promptLoadingIndicator" style="display: none;">
            <div class="spinner gemini-spinner"></div>
            <p>✨ Gemini está pensando un prompt creativo...</p>
        </div>
        
        <div id="loadingIndicator" style="display: none;">
            <div class="spinner fabio-spinner"></div>
            <p>Generando imagen, por favor espera...</p>
        </div>
        
        <div id="imageContainer" class="mt-6">
            </div>

        <div id="errorMessage">
            </div>
    </div>

    <footer>
        <p>&copy; 2024 imágenes.Fabio.GeminiAi - Una creación con IA y Gemini</p>
    </footer>

    <script>
        // Get references to DOM elements
        const suggestPromptButton = document.getElementById('suggestPromptButton');
        const generateImageButton = document.getElementById('generateImageButton');
        const describeImageButton = document.getElementById('describeImageButton'); // Placeholder
        
        const promptInput = document.getElementById('promptInput');
        const imageContainer = document.getElementById('imageContainer');
        
        const loadingIndicator = document.getElementById('loadingIndicator');
        const promptLoadingIndicator = document.getElementById('promptLoadingIndicator');
        const errorMessageContainer = document.getElementById('errorMessage');

        // API configuration
        const apiKey = ""; // API key will be injected by the environment if necessary
        const imageGenApiUrl = `https://generativelanguage.googleapis.com/v1beta/models/imagen-3.0-generate-002:predict?key=${apiKey}`;
        const geminiApiUrl = `https://generativelanguage.googleapis.com/v1beta/models/gemini-2.0-flash:generateContent?key=${apiKey}`;

        // --- Event Listener for Suggest Prompt Button ---
        suggestPromptButton.addEventListener('click', async () => {
            suggestPromptButton.disabled = true;
            generateImageButton.disabled = true; // Also disable image gen during prompt suggestion
            promptLoadingIndicator.style.display = 'flex';
            errorMessageContainer.style.display = 'none';
            errorMessageContainer.textContent = '';
            promptInput.value = ''; // Clear previous prompt

            const userPromptForGemini = "Genera un prompt corto y creativo para un modelo de generación de imágenes de IA. El prompt debe ser inspirador y detallado, adecuado para crear arte digital único y visualmente impactante. Piensa en escenarios fantásticos, combinaciones inusuales de objetos o estilos artísticos sorprendentes. Por ejemplo: 'Un bosque bioluminiscente de cristal donde los árboles susurran secretos antiguos, pintado en un estilo que fusiona el art nouveau con el cyberpunk.' o 'Un astronauta solitario descubriendo una biblioteca cósmica flotando en una nebulosa de colores pastel, con libros hechos de luz estelar.'";
            let chatHistory = [{ role: "user", parts: [{ text: userPromptForGemini }] }];
            const payload = { contents: chatHistory };

            try {
                const response = await fetch(geminiApiUrl, {
                    method: 'POST',
                    headers: { 'Content-Type': 'application/json' },
                    body: JSON.stringify(payload)
                });

                if (!response.ok) {
                    const errorData = await response.json();
                    console.error('Gemini API Error Response:', errorData);
                    throw new Error(`Error de Gemini: ${errorData?.error?.message || response.statusText}`);
                }

                const result = await response.json();
                console.log("Gemini API Success Response:", result);

                if (result.candidates && result.candidates.length > 0 &&
                    result.candidates[0].content && result.candidates[0].content.parts &&
                    result.candidates[0].content.parts.length > 0) {
                    const suggestedPrompt = result.candidates[0].content.parts[0].text;
                    promptInput.value = suggestedPrompt.trim();
                } else {
                    throw new Error('No se pudo obtener una sugerencia de prompt de Gemini.');
                }

            } catch (error) {
                console.error('Error suggesting prompt:', error);
                displayError(`No se pudo sugerir un prompt: ${error.message}`);
                promptInput.value = "No se pudo generar un prompt. Inténtalo de nuevo o escribe el tuyo.";
            } finally {
                suggestPromptButton.disabled = false;
                generateImageButton.disabled = false;
                promptLoadingIndicator.style.display = 'none';
            }
        });


        // --- Event Listener for Generate Image Button ---
        generateImageButton.addEventListener('click', async () => {
            generateImageButton.disabled = true;
            suggestPromptButton.disabled = true; // Also disable suggest prompt during image gen
            loadingIndicator.style.display = 'flex';
            imageContainer.innerHTML = ''; 
            errorMessageContainer.style.display = 'none';
            errorMessageContainer.textContent = '';

            let finalPrompt = promptInput.value.trim();

            if (!finalPrompt) {
                // Fallback to random prompts if input is empty
                const fallbackPrompts = [
                    "A hyperrealistic digital painting of a mythical creature designed by FabioAI, blending organic and technological elements, set in a surreal landscape.",
                    "FabioAI's vision of a futuristic city, with flying vehicles, holographic advertisements, and lush vertical gardens, bathed in neon light.",
                    "An abstract artwork representing the concept of artificial creativity by FabioAI, with swirling colors, geometric patterns, and light particles.",
                    "A whimsical illustration of a friendly robot, 'FabioBot', exploring a vibrant alien planet full of strange flora and fauna.",
                    "A photorealistic image of a fantastical machine that generates dreams, designed by FabioAI, with intricate gears and glowing orbs."
                ];
                finalPrompt = fallbackPrompts[Math.floor(Math.random() * fallbackPrompts.length)];
                promptInput.value = `(Prompt aleatorio usado) ${finalPrompt}`; // Show which prompt was used
            }
            
            console.log("Selected Prompt for Image Generation:", finalPrompt);

            const payload = {
                instances: [{ prompt: finalPrompt }],
                parameters: { sampleCount: 1 }
            };

            try {
                const response = await fetch(imageGenApiUrl, {
                    method: 'POST',
                    headers: { 'Content-Type': 'application/json' },
                    body: JSON.stringify(payload)
                });

                if (!response.ok) {
                    const errorData = await response.json();
                    console.error('Image Gen API Error Response:', errorData);
                    let errorMsg = `Error ${response.status}: ${response.statusText}`;
                    if (errorData && errorData.error && errorData.error.message) {
                        errorMsg = `Error: ${errorData.error.message}`;
                    }
                    throw new Error(errorMsg);
                }

                const result = await response.json();
                console.log("Image Gen API Success Response:", result);

                if (result.predictions && result.predictions.length > 0 && result.predictions[0].bytesBase64Encoded) {
                    const imageData = result.predictions[0].bytesBase64Encoded;
                    const imageUrl = `data:image/png;base64,${imageData}`;
                    
                    const imgElement = document.createElement('img');
                    imgElement.src = imageUrl;
                    imgElement.alt = 'Imagen generada por FabioAI con el prompt: ' + finalPrompt;
                    imgElement.onerror = () => {
                        displayError('No se pudo cargar la imagen generada.');
                    };
                    imageContainer.appendChild(imgElement);
                } else {
                    console.error('Unexpected Image Gen API response structure:', result);
                    throw new Error('La respuesta de la API de imágenes no contiene datos válidos.');
                }

            } catch (error) {
                console.error('Error generating image:', error);
                displayError(`No se pudo generar la imagen. ${error.message}`);
            } finally {
                generateImageButton.disabled = false;
                suggestPromptButton.disabled = false;
                loadingIndicator.style.display = 'none';
            }
        });

        function displayError(message) {
            errorMessageContainer.textContent = message;
            errorMessageContainer.style.display = 'block';
        }
    </script>
</body>
</html>
