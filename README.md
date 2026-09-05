# Ex02 Commercial Website
## Date:

## AIM
To create a commercial website using CSS Flexbox.

## ALGORITHM
### STEP 1
Create an HTML file (index.html)

### STEP 2
Create a CSS file (style.css)

### STEP 3
Include a navigation bar with links to different sections.

### STEP 4
Add structured sections for Homepage, Products / Services, About Us, Contact Details and User Account.

### STEP 5
Include social media links at the footer with copyright information.

### STEP 6
Define global styles for fonts, colors, and layout.

### STEP 7
Style the header, navigation bar, and sections.

### STEP 8
Use Flexbox for layout design.

### STEP 9
Add hover effects and transitions for interactivity.

### STEP 10
Add Images and Media.

### STEP 11
Use optimized images for a professional look.

### STEP 12
Open the HTML file in a browser to check layout and functionality.

### STEP 13
Fix styling issues and refine content placement.

### STEP 14
Deploy the website.

### STEP 15
Upload to GitHub Pages for free hosting.

## PROGRAM
```
<!DOCTYPE html>
<html>
<head>
    <title>Jaan Car Enterprises</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>

<nav>
    <div class="logo">Jaan Car Enterprises</div>
    <div>
        <a href="#home">Home</a>
        <a href="#buy">Buy</a>
        <a href="#services">Services</a>
        <a href="#payment">Payment</a>
    </div>
</nav>

<section id="home" class="section hero">
    <div class="hero-content">
        <p class="eyebrow">Trusted automotive enterprise</p>
        <h1>Drive Your Dream Car With Confidence</h1>
        <p>Jaan Car Enterprises brings premium vehicles, transparent pricing, and dependable service for a smooth, trustworthy purchase experience.</p>
        <div class="hero-actions">
            <a href="#buy" class="btn">Explore Cars</a>
            <a href="#services" class="btn secondary">Our Services</a>
        </div>
    </div>
</section>

<section id="services" class="section services-section">
    <div class="section-heading">
        <h2>Our Services</h2>
        <p>Everything needed to make your next vehicle purchase smooth and premium.</p>
    </div>

    <div class="services-grid">
        <article class="service-card">
            <h3>Certified Vehicles</h3>
            <p>Every car is inspected for quality, safety, and performance before delivery.</p>
        </article>
        <article class="service-card">
            <h3>Easy Financing</h3>
            <p>Transparent payment support with flexible plans designed around your budget.</p>
        </article>
        <article class="service-card">
            <h3>Home Delivery</h3>
            <p>Fast arrangements and doorstep delivery for a hassle-free buying experience.</p>
        </article>
        <article class="service-card">
            <h3>After-Sales Support</h3>
            <p>Dedicated assistance for service, maintenance, and vehicle care after purchase.</p>
        </article>
    </div>
</section>

<section id="buy" class="section">
    <div class="section-heading">
        <h2>Featured Collection</h2>
        <p>Jaan Car Enterprises offers 10 premium choices with fixed prices, trusted quality, and easy purchase support.</p>
    </div>

    <div class="buy-layout">
        <div class="card-container">

            <article class="card" data-name="Hyundai Creta" data-price="1275000">
                <img src="https://images.unsplash.com/photo-1552519507-da3b142c6e3d?auto=format&fit=crop&w=1200&q=80" alt="Hyundai Creta">
                <div class="card-body">
                    <span class="tag">Compact SUV</span>
                    <h3>Hyundai Creta</h3>
                    <p class="car-price">₹12,75,000</p>
                    <ul>
                        <li>2023 Model</li>
                        <li>1.5L Petrol</li>
                        <li>Automatic</li>
                    </ul>
                    <button type="button" class="btn add-cart-btn">Add to Cart</button>
                </div>
            </article>

            <article class="card" data-name="Kia Seltos" data-price="1320000">
                <img src="https://images.unsplash.com/photo-1492144534655-ae79c964c9d7?auto=format&fit=crop&w=1200&q=80" alt="Kia Seltos">
                <div class="card-body">
                    <span class="tag">Urban SUV</span>
                    <h3>Kia Seltos</h3>
                    <p class="car-price">₹13,20,000</p>
                    <ul>
                        <li>2024 Model</li>
                        <li>1.5L Turbo</li>
                        <li>Smart Drive</li>
                    </ul>
                    <button type="button" class="btn add-cart-btn">Add to Cart</button>
                </div>
            </article>

            <article class="card" data-name="Tata Nexon" data-price="1190000">
                <img src="https://images.unsplash.com/photo-1503376780353-7e6692767b70?auto=format&fit=crop&w=1200&q=80" alt="Tata Nexon">
                <div class="card-body">
                    <span class="tag">City SUV</span>
                    <h3>Tata Nexon</h3>
                    <p class="car-price">₹11,90,000</p>
                    <ul>
                        <li>2023 Model</li>
                        <li>1.2L Turbo</li>
                        <li>Manual</li>
                    </ul>
                    <button type="button" class="btn add-cart-btn">Add to Cart</button>
                </div>
            </article>

            <article class="card" data-name="MG Hector" data-price="1840000">
                <img src="https://images.unsplash.com/photo-1544636331-e26879cd4d9b?auto=format&fit=crop&w=1200&q=80" alt="MG Hector">
                <div class="card-body">
                    <span class="tag">Premium SUV</span>
                    <h3>MG Hector</h3>
                    <p class="car-price">₹18,40,000</p>
                    <ul>
                        <li>2024 Model</li>
                        <li>2.0L Diesel</li>
                        <li>Automatic</li>
                    </ul>
                    <button type="button" class="btn add-cart-btn">Add to Cart</button>
                </div>
            </article>

            <article class="card" data-name="Maruti Brezza" data-price="980000">
                <img src="https://images.unsplash.com/photo-1511919884226-fd3cad34687c?auto=format&fit=crop&w=1200&q=80" alt="Maruti Brezza">
                <div class="card-body">
                    <span class="tag">Family SUV</span>
                    <h3>Maruti Brezza</h3>
                    <p class="car-price">₹9,80,000</p>
                    <ul>
                        <li>2023 Model</li>
                        <li>1.5L Petrol</li>
                        <li>Manual</li>
                    </ul>
                    <button type="button" class="btn add-cart-btn">Add to Cart</button>
                </div>
            </article>

            <article class="card" data-name="Honda City" data-price="1460000">
                <img src="https://images.unsplash.com/photo-1553440569-bcc63803a83d?auto=format&fit=crop&w=1200&q=80" alt="Honda City">
                <div class="card-body">
                    <span class="tag">Executive Sedan</span>
                    <h3>Honda City</h3>
                    <p class="car-price">₹14,60,000</p>
                    <ul>
                        <li>2024 Model</li>
                        <li>1.5L Petrol</li>
                        <li>CVT</li>
                    </ul>
                    <button type="button" class="btn add-cart-btn">Add to Cart</button>
                </div>
            </article>

            <article class="card" data-name="Toyota Corolla" data-price="2275000">
                <img src="https://images.unsplash.com/photo-1552519507-da3b142c6e3d?auto=format&fit=crop&w=1200&q=80" alt="Toyota Corolla">
                <div class="card-body">
                    <span class="tag">Luxury Sedan</span>
                    <h3>Toyota Corolla</h3>
                    <p class="car-price">₹22,75,000</p>
                    <ul>
                        <li>2024 Model</li>
                        <li>1.8L Hybrid</li>
                        <li>Automatic</li>
                    </ul>
                    <button type="button" class="btn add-cart-btn">Add to Cart</button>
                </div>
            </article>

            <article class="card" data-name="Mahindra Scorpio" data-price="1785000">
                <img src="https://images.unsplash.com/photo-1503736334956-4c8f8e92946d?auto=format&fit=crop&w=1200&q=80" alt="Mahindra Scorpio">
                <div class="card-body">
                    <span class="tag">Adventure SUV</span>
                    <h3>Mahindra Scorpio</h3>
                    <p class="car-price">₹17,85,000</p>
                    <ul>
                        <li>2023 Model</li>
                        <li>2.2L Diesel</li>
                        <li>Automatic</li>
                    </ul>
                    <button type="button" class="btn add-cart-btn">Add to Cart</button>
                </div>
            </article>

            <article class="card" data-name="Kia Carnival" data-price="3250000">
                <img src="https://images.unsplash.com/photo-1544636331-e26879cd4d9b?auto=format&fit=crop&w=1200&q=80" alt="Kia Carnival">
                <div class="card-body">
                    <span class="tag">Luxury MPV</span>
                    <h3>Kia Carnival</h3>
                    <p class="car-price">₹32,50,000</p>
                    <ul>
                        <li>2024 Model</li>
                        <li>3.5L Petrol</li>
                        <li>Luxury Trim</li>
                    </ul>
                    <button type="button" class="btn add-cart-btn">Add to Cart</button>
                </div>
            </article>

            <article class="card" data-name="Renault Kiger" data-price="845000">
                <img src="https://images.unsplash.com/photo-1493238792000-8113da705763?auto=format&fit=crop&w=1200&q=80" alt="Renault Kiger">
                <div class="card-body">
                    <span class="tag">Compact SUV</span>
                    <h3>Renault Kiger</h3>
                    <p class="car-price">₹8,45,000</p>
                    <ul>
                        <li>2024 Model</li>
                        <li>1.0L Turbo</li>
                        <li>Manual</li>
                    </ul>
                    <button type="button" class="btn add-cart-btn">Add to Cart</button>
                </div>
            </article>

        </div>

        <aside id="payment" class="checkout-panel buy-checkout">
            <h3>Cart & Payment</h3>
            <div class="selected-car">
                <span>Selected Vehicle</span>
                <strong id="selectedCarName">None</strong>
            </div>
            <div class="summary-row">
                <span>Car Value</span>
                <strong id="cartValue">₹0</strong>
            </div>
            <div class="summary-row">
                <span>Processing Fee</span>
                <strong id="feeValue">₹0</strong>
            </div>
            <div class="summary-row total-row">
                <span>Total to Pay</span>
                <strong id="totalValue">₹0</strong>
            </div>

            <div class="payment-options">
                <button class="payment-option active" type="button" data-method="UPI">UPI</button>
                <button class="payment-option" type="button" data-method="Card">Card</button>
                <button class="payment-option" type="button" data-method="Net Banking">Net Banking</button>
            </div>

            <button type="button" class="btn pay-btn">Pay Now</button>
            <p id="orderStatus" class="order-status">Select a car to continue.</p>
        </aside>
    </div>
</section>

<script>
    const cartValueEl = document.getElementById('cartValue');
    const feeValueEl = document.getElementById('feeValue');
    const totalValueEl = document.getElementById('totalValue');
    const selectedCarNameEl = document.getElementById('selectedCarName');
    const orderStatusEl = document.getElementById('orderStatus');
    const GPayUPI = 'jaan.carenterprises@upi';

    const formatCurrency = (value) => new Intl.NumberFormat('en-IN', {
        style: 'currency',
        currency: 'INR',
        maximumFractionDigits: 0
    }).format(value);

    let selectedPaymentMethod = 'UPI';
    let selectedCarPrice = 0;

    function updateCheckout(total) {
        const fee = Math.round(total * 0.02);
        cartValueEl.textContent = formatCurrency(total);
        feeValueEl.textContent = formatCurrency(fee);
        totalValueEl.textContent = formatCurrency(total + fee);
    }

    function selectCar(name, price) {
        selectedCarNameEl.textContent = name;
        selectedCarPrice = price;
        updateCheckout(price);
        orderStatusEl.textContent = `${name} added to cart. Payment ready using ${selectedPaymentMethod}.`;
    }

    document.querySelectorAll('.add-cart-btn').forEach((button) => {
        button.addEventListener('click', () => {
            const card = button.closest('.card');
            const name = card.dataset.name;
            const price = Number(card.dataset.price);
            selectCar(name, price);
            document.getElementById('payment').scrollIntoView({ behavior: 'smooth' });
        });
    });

    document.querySelectorAll('.payment-option').forEach((button) => {
        button.addEventListener('click', () => {
            document.querySelectorAll('.payment-option').forEach((item) => item.classList.remove('active'));
            button.classList.add('active');
            selectedPaymentMethod = button.dataset.method;

            if (selectedCarNameEl.textContent !== 'None') {
                orderStatusEl.textContent = `${selectedCarNameEl.textContent} ready for payment via ${selectedPaymentMethod}.`;
            }
        });
    });

    document.querySelector('.pay-btn').addEventListener('click', () => {
        if (selectedCarNameEl.textContent === 'None') {
            orderStatusEl.textContent = 'Select a vehicle first before paying.';
            return;
        }

        const fee = Math.round(selectedCarPrice * 0.02);
        const totalAmount = selectedCarPrice + fee;
        const upiUrl = `upi://pay?pa=${encodeURIComponent(GPayUPI)}&pn=${encodeURIComponent('Jaan Car Enterprises')}&am=${totalAmount}&cu=INR&tn=${encodeURIComponent('Vehicle Purchase - ' + selectedCarNameEl.textContent)}`;

        const paymentData = {
            carName: selectedCarNameEl.textContent,
            amount: totalAmount,
            method: selectedPaymentMethod,
            time: new Date().toISOString()
        };

        localStorage.setItem('lastPayment', JSON.stringify(paymentData));
        orderStatusEl.textContent = `Redirecting to GPay for ${selectedCarNameEl.textContent}...`;

        try {
            window.location.href = upiUrl;
        } catch (error) {
            console.warn('UPI redirect failed:', error);
        }

        setTimeout(() => {
            if (document.visibilityState === 'visible') {
                window.location.href = 'success.html';
            }
        }, 2200);
    });

    updateCheckout(0);
</script>

</body>
</html>
```
```
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family: Arial, sans-serif;
    scroll-behavior: smooth;
}

body {
    background: #0b1020;
    color: #f5f7fb;
}

nav {
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 18px 60px;
    background: rgba(10, 15, 25, 0.92);
    color: white;
    position: fixed;
    width: 100%;
    z-index: 1000;
    backdrop-filter: blur(8px);
    border-bottom: 1px solid rgba(255,255,255,0.08);
}

.logo {
    font-size: 1.8rem;
    font-weight: 700;
    letter-spacing: 1px;
}

nav a {
    color: #eaf0ff;
    text-decoration: none;
    margin-left: 20px;
    font-weight: 600;
    transition: opacity 0.2s ease;
}

nav a:hover {
    opacity: 0.8;
}

.section {
    min-height: 100vh;
    padding: 120px 50px 80px;
    text-align: center;
    color: white;
}

.section-heading {
    margin-bottom: 30px;
}

.section-heading h2 {
    font-size: 2.4rem;
    margin-bottom: 8px;
}

.section-heading p {
    color: #dfe9ff;
    font-size: 1rem;
}

#payment {
    scroll-margin-top: 120px;
}

.hero {
    display: flex;
    align-items: center;
    justify-content: center;
    background: linear-gradient(rgba(6, 10, 18, 0.7), rgba(6, 10, 18, 0.7)),
                url("https://images.unsplash.com/photo-1503376780353-7e6692767b70");
    background-size: cover;
    background-position: center;
}

.hero-content {
    max-width: 760px;
    text-align: center;
}

.eyebrow {
    color: #d0dcff;
    text-transform: uppercase;
    letter-spacing: 2px;
    font-size: 0.8rem;
    font-weight: 700;
    margin-bottom: 18px;
}

.hero h1 {
    font-size: 3.2rem;
    margin-bottom: 18px;
    line-height: 1.1;
}

.hero p {
    font-size: 1.08rem;
    margin-bottom: 22px;
    color: #edf3ff;
}

.hero-actions {
    display: flex;
    justify-content: center;
    gap: 14px;
    flex-wrap: wrap;
}

.services-section {
    background: linear-gradient(rgba(12, 20, 34, 0.95), rgba(12, 20, 34, 0.95));
}

.services-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(210px, 1fr));
    gap: 20px;
    max-width: 1100px;
    margin: 0 auto;
}

.service-card {
    background: rgba(255,255,255,0.06);
    border: 1px solid rgba(255,255,255,0.12);
    border-radius: 18px;
    padding: 24px 22px;
    text-align: left;
}

.service-card h3 {
    font-size: 1.25rem;
    margin-bottom: 12px;
}

.service-card p {
    color: #dfe9ff;
    line-height: 1.6;
}

#buy {
    background: linear-gradient(rgba(10, 18, 30, 0.82), rgba(10, 18, 30, 0.82)),
                url("https://images.unsplash.com/photo-1493238792000-8113da705763");
    background-size: cover;
    background-position: center;
}

.buy-layout {
    display: grid;
    grid-template-columns: 1.9fr 0.9fr;
    gap: 30px;
    align-items: start;
    max-width: 1200px;
    margin: 0 auto;
}

.card-container {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
    gap: 20px;
}

.card {
    background: rgba(255,255,255,0.96);
    color: #111827;
    border-radius: 18px;
    overflow: hidden;
    box-shadow: 0 16px 35px rgba(0,0,0,0.18);
    transition: transform 0.25s ease, box-shadow 0.25s ease;
    text-align: left;
}

.card:hover {
    transform: translateY(-4px);
    box-shadow: 0 20px 40px rgba(0,0,0,0.23);
}

.card img {
    width: 100%;
    height: 180px;
    object-fit: cover;
    display: block;
}

.card-body {
    padding: 18px 18px 20px;
}

.tag {
    display: inline-block;
    background: #e7f0ff;
    color: #1c4aa8;
    font-size: 0.72rem;
    font-weight: 700;
    padding: 6px 10px;
    border-radius: 999px;
    margin-bottom: 10px;
}

.card h3 {
    font-size: 1.35rem;
    margin-bottom: 8px;
}

.car-price {
    font-size: 1.3rem;
    color: #111827;
    font-weight: 700;
    margin-bottom: 12px;
}

.card ul {
    list-style: none;
    margin: 0 0 16px;
    padding: 0;
    color: #475569;
    display: grid;
    gap: 6px;
    font-size: 0.92rem;
}

.checkout-panel {
    background: rgba(255,255,255,0.95);
    color: #111827;
    width: min(350px, 100%);
    padding: 25px;
    border-radius: 18px;
    box-shadow: 0 20px 40px rgba(0,0,0,0.18);
    text-align: left;
}

.checkout-panel h3 {
    margin-bottom: 20px;
    text-align: center;
    font-size: 1.6rem;
}

.success-page {
    min-height: 100vh;
    background: linear-gradient(135deg, #0b1020 0%, #101d35 100%);
    display: flex;
    align-items: center;
    justify-content: center;
    padding: 40px 20px;
}

.success-card {
    background: rgba(255, 255, 255, 0.96);
    color: #0f172a;
    width: min(540px, 100%);
    border-radius: 24px;
    padding: 32px 28px;
    box-shadow: 0 20px 40px rgba(0,0,0,0.2);
    text-align: center;
}

.success-badge {
    display: inline-flex;
    align-items: center;
    justify-content: center;
    width: 82px;
    height: 82px;
    border-radius: 50%;
    background: #e7f9ee;
    color: #1f9d61;
    font-size: 2.4rem;
    margin-bottom: 18px;
}

.success-card h1 {
    font-size: 2.2rem;
    margin-bottom: 12px;
}

.success-card p {
    color: #475569;
    margin-bottom: 18px;
    line-height: 1.6;
}

.success-meta {
    background: #f8fafc;
    border: 1px solid #e2e8f0;
    border-radius: 16px;
    padding: 18px;
    margin: 20px 0;
    text-align: left;
}

.success-meta div {
    display: flex;
    justify-content: space-between;
    gap: 12px;
    padding: 8px 0;
    border-bottom: 1px solid #e2e8f0;
}

.success-meta div:last-child {
    border-bottom: none;
}

.success-actions {
    display: flex;
    justify-content: center;
    gap: 12px;
    flex-wrap: wrap;
    margin-top: 24px;
}

.success-btn {
    display: inline-block;
    padding: 12px 22px;
    border-radius: 10px;
    text-decoration: none;
    font-weight: 700;
    transition: transform 0.2s ease;
}

.success-btn.primary {
    background: #0f172a;
    color: #fff;
}

.success-btn.secondary {
    background: #e7f0ff;
    color: #1d4ed8;
}

.success-btn:hover {
    transform: translateY(-1px);
}

.selected-car {
    display: flex;
    justify-content: space-between;
    gap: 15px;
    margin-bottom: 16px;
    font-size: 0.95rem;
}

.summary-row {
    display: flex;
    justify-content: space-between;
    gap: 15px;
    margin: 12px 0;
    font-size: 1rem;
}

.total-row {
    margin-top: 20px;
    padding-top: 12px;
    border-top: 1px solid #dbe3f0;
    font-weight: bold;
}

.payment-options {
    display: flex;
    gap: 8px;
    flex-wrap: wrap;
    margin: 18px 0 12px;
}

.payment-option {
    flex: 1;
    min-width: 80px;
    border: none;
    background: #edf2ff;
    color: #1f2937;
    border-radius: 10px;
    padding: 10px 8px;
    font-weight: 700;
    cursor: pointer;
    transition: all 0.2s ease;
}

.payment-option.active {
    background: #111827;
    color: white;
}

.order-status {
    margin-top: 14px;
    color: #374151;
    font-size: 0.9rem;
    line-height: 1.5;
}

.pay-btn {
    width: 100%;
    border: none;
    cursor: pointer;
    margin-top: 15px;
}

.btn {
    display: inline-block;
    margin-top: 10px;
    padding: 10px 16px;
    background: #111827;
    color: white;
    text-decoration: none;
    border-radius: 10px;
    border: none;
    cursor: pointer;
    font-weight: 700;
    transition: opacity 0.2s ease, transform 0.2s ease;
}

.btn:hover {
    opacity: 0.95;
    transform: translateY(-1px);
}

.btn.secondary {
    background: #edf2ff;
    color: #111827;
}

@media (max-width: 900px) {
    .buy-layout {
        grid-template-columns: 1fr;
    }
}

@media (max-width: 640px) {
    nav {
        padding: 16px 20px;
        flex-direction: column;
        gap: 10px;
    }

    .section {
        padding-left: 20px;
        padding-right: 20px;
    }

    .hero h1 {
        font-size: 2.3rem;
    }
}
```


## OUTPUT
<img width="1897" height="982" alt="image" src="https://github.com/user-attachments/assets/255e6e2e-24fb-49c9-8066-83046def922f" />
<img width="1917" height="1022" alt="image" src="https://github.com/user-attachments/assets/5f3d3298-5556-4522-aeb8-8b68023ad323" />


## RESULT
The program for creating commercial website using CSS Flexbox is executed successfully.
