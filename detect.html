// Handle File Upload and Preview
const imageInput = document.getElementById('imageInput');
const previewArea = document.getElementById('previewArea');
const imagePreview = document.getElementById('imagePreview');
const loading = document.getElementById('loading');
const resultBox = document.getElementById('result');
const diseaseName = document.getElementById('diseaseName');
const confidenceValue = document.getElementById('confidenceValue');
const remedyText = document.getElementById('remedy');

let uploadedFileName = "";

imageInput.addEventListener('change', function(event) {
    const file = event.target.files[0];
    if (file) {
        uploadedFileName = file.name.toLowerCase(); // Store filename for "smart" prediction
        const reader = new FileReader();
        reader.onload = function(e) {
            imagePreview.src = e.target.result;
            previewArea.style.display = 'block';
            resultBox.style.display = 'none'; // Hide previous results
        }
        reader.readAsDataURL(file);
    }
});

// Simulate AI Prediction based on Filename
function predictDisease() {
    // Show loading
    loading.style.display = 'block';
    resultBox.style.display = 'none';

    // Simulate a delay for "processing" (2 seconds)
    setTimeout(() => {
        loading.style.display = 'none';
        resultBox.style.display = 'block';

        let result;

        // SMART SIMULATION LOGIC
        // If the filename contains "health", show Healthy result.
        if (uploadedFileName.includes("health")) {
            result = { 
                name: "Healthy Plant", 
                conf: "98%", 
                color: "green",
                remedy: "Your plant looks great! Keep up the regular watering and sunlight." 
            };
        } 
        // If filename contains "blight", show Blight.
        else if (uploadedFileName.includes("blight")) {
            result = { 
                name: "Early Blight (Fungal)", 
                conf: "87%", 
                color: "orange",
                remedy: "Remedy: Remove affected leaves. Apply a copper-based fungicide. Improve air circulation." 
            };
        }
        // If filename contains "spot", show Bacterial Spot.
        else if (uploadedFileName.includes("spot")) {
            result = { 
                name: "Bacterial Spot", 
                conf: "92%", 
                color: "red",
                remedy: "Remedy: Avoid overhead watering. Use copper sprays. Remove infected plant debris immediately." 
            };
        }
        // Fallback: If name is generic (e.g., "image.jpg"), pick random
        else {
            const outcomes = [
                { 
                    name: "Healthy Plant", 
                    conf: "95%", 
                    color: "green",
                    remedy: "Your plant looks healthy." 
                },
                { 
                    name: "Leaf Rust", 
                    conf: "89%", 
                    color: "brown",
                    remedy: "Remedy: Prune infected leaves and apply sulfur-based fungicides." 
                }
            ];
            result = outcomes[Math.floor(Math.random() * outcomes.length)];
        }

        // Update UI
        diseaseName.innerText = result.name;
        diseaseName.style.color = result.color;
        confidenceValue.innerText = result.conf;
        remedyText.innerText = result.remedy;

    }, 2000);
}
