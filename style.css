:root {
    --primary-color: #003366; /* Dark Blue - Qatar/Lufthansa inspired */
    --secondary-color: #c40c31; /* Red - Lufthansa inspired */
    --tertiary-color: #a4a4a4; /* Gray for subtle elements */
    --background-color: #f0f4f8; /* Light gray-blue for a clean feel */
    --text-color: #333;
    --border-radius: 12px;
    --padding-base: 1.5rem;
    --gap-base: 2rem;
}

body {
    font-family: Arial, sans-serif;
    line-height: 1.6;
    margin: 0;
    padding: 0;
    background-color: var(--background-color);
    color: var(--text-color);
}

.container {
    max-width: 1100px;
    margin: 0 auto;
    padding: var(--padding-base);
    box-sizing: border-box;
}

h1, h2, h3 {
    color: var(--primary-color);
}

/* Header & Logo */
.header {
    text-align: center;
    padding: var(--padding-base) 0;
}

.logo-container {
    display: flex;
    justify-content: center;
    gap: 1rem;
    margin-bottom: 1rem;
}

.logo {
    max-height: 50px;
}

/* Z-reading Pattern & Sections */
.hero-section, .program-section {
    display: grid;
    grid-template-columns: 1fr;
    gap: var(--gap-base);
    align-items: center;
    margin-bottom: var(--gap-base);
    background: white;
    padding: var(--padding-base);
    border-radius: var(--border-radius);
    box-shadow: 0 4px 8px rgba(0,0,0,0.1);
}

@media (min-width: 768px) {
    .hero-section {
        grid-template-columns: 1fr 1fr;
    }
    .program-section {
        grid-template-columns: 1fr 1fr;
        direction: rtl; /* Flip for Z-pattern */
    }
    .program-content {
        direction: ltr; /* Reset text direction */
    }
}

.hero-image, .program-image {
    text-align: center;
}

.hero-image img, .program-image img {
    max-width: 100%;
    height: auto;
    border-radius: var(--border-radius);
}

/* Buttons */
.button {
    display: inline-block;
    padding: 0.75rem 1.5rem;
    text-decoration: none;
    font-weight: bold;
    border-radius: 50px; /* More round than normal elements */
    transition: background-color 0.3s ease, transform 0.2s ease;
    text-align: center;
}

.button:hover {
    transform: translateY(-2px);
}

.primary {
    background-color: var(--primary-color);
    color: white;
}

.primary:hover {
    background-color: #004d99;
}

.secondary {
    background-color: white;
    color: var(--primary-color);
    border: 2px solid var(--primary-color);
}

.secondary:hover {
    background-color: var(--background-color);
}

.tertiary {
    background-color: var(--tertiary-color);
    color: white;
}

.tertiary:hover {
    background-color: #8c8c8c;
}

.button-group {
    display: flex;
    flex-direction: column;
    gap: 1rem;
    margin-top: 1.5rem;
}

@media (min-width: 500px) {
    .button-group {
        flex-direction: row;
        justify-content: center;
    }
}

/* Footer */
.footer {
    text-align: center;
    padding: var(--padding-base) 0;
    margin-top: var(--gap-base);
}

.contact-info {
    margin-bottom: 1rem;
}

.contact-info .button {
    margin-top: 0.5rem;
}
