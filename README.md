<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>4-Tier Pricing Strategy | Holistic Medical Supply - Complete Pricing Guide</title>
    <meta name="description" content="Comprehensive 4-tier pricing strategy: Economy, Value, US-Made Premium, and Luxury. Complete guide with sales scripts, competitive positioning, and implementation.">
    <style>
        :root {
            --primary-blue: #1e3c72;
            --secondary-blue: #2a5298;
            --accent-purple: #667eea;
            --accent-violet: #764ba2;
            --success-green: #27ae60;
            --warning-orange: #f39c12;
            --danger-red: #e74c3c;
            --light-bg: #f8f9fa;
            --white: #ffffff;
            --text-dark: #333333;
            --text-light: #666666;
            --gold: #f1c40f;
            --silver: #95a5a6;
            --bronze: #cd7f32;
        }

        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            line-height: 1.6;
            color: var(--text-dark);
            background: linear-gradient(135deg, var(--accent-purple) 0%, var(--accent-violet) 100%);
            padding: 20px;
        }

        .container {
            max-width: 1600px;
            margin: 0 auto;
            background: var(--white);
            border-radius: 20px;
            box-shadow: 0 20px 80px rgba(0, 0, 0, 0.3);
            overflow: hidden;
        }

        /* Language Toggle */
        .language-toggle {
            position: sticky;
            top: 0;
            z-index: 1000;
            background: rgba(255, 255, 255, 0.98);
            backdrop-filter: blur(10px);
            padding: 20px 40px;
            display: flex;
            justify-content: space-between;
            align-items: center;
            border-bottom: 3px solid var(--accent-purple);
            box-shadow: 0 4px 20px rgba(0, 0, 0, 0.1);
        }

        .nav-links {
            display: flex;
            gap: 15px;
            align-items: center;
        }

        .back-link {
            padding: 10px 25px;
            background: var(--light-bg);
            color: var(--primary-blue);
            text-decoration: none;
            border-radius: 8px;
            font-weight: 600;
            transition: all 0.3s ease;
            display: flex;
            align-items: center;
            gap: 8px;
        }

        .back-link:hover {
            background: var(--accent-purple);
            color: var(--white);
            transform: translateX(-3px);
        }

        .lang-buttons {
            display: flex;
            gap: 10px;
        }

        .lang-btn {
            padding: 10px 25px;
            border: 2px solid var(--accent-purple);
            background: var(--white);
            color: var(--accent-purple);
            border-radius: 8px;
            cursor: pointer;
            font-size: 0.95em;
            font-weight: bold;
            transition: all 0.3s ease;
        }

        .lang-btn:hover {
            background: #f0f0ff;
            transform: translateY(-2px);
        }

        .lang-btn.active {
            background: linear-gradient(135deg, var(--accent-purple), var(--accent-violet));
            color: var(--white);
        }

        .lang-content {
            display: none;
        }

        .lang-content.active {
            display: block;
            animation: fadeIn 0.5s ease-in;
        }

        @keyframes fadeIn {
            from { opacity: 0; transform: translateY(10px); }
            to { opacity: 1; transform: translateY(0); }
        }

        /* Header */
        .header {
            background: linear-gradient(135deg, var(--primary-blue) 0%, var(--secondary-blue) 100%);
            color: var(--white);
            padding: 60px 60px 40px;
            position: relative;
            overflow: hidden;
        }

        .doc-badge {
            display: inline-block;
            padding: 8px 20px;
            background: var(--gold);
            color: var(--text-dark);
            border-radius: 20px;
            font-size: 0.9em;
            font-weight: bold;
            margin-bottom: 15px;
            text-transform: uppercase;
            letter-spacing: 1px;
        }

        .header h1 {
            font-size: 3.5em;
            margin-bottom: 15px;
            font-weight: 800;
            position: relative;
            z-index: 1;
        }

        .header .subtitle {
            font-size: 1.5em;
            opacity: 0.95;
            margin-bottom: 30px;
        }

        .header-stats {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
            gap: 20px;
            margin-top: 40px;
        }

        .header-stat {
            background: rgba(255, 255, 255, 0.15);
            backdrop-filter: blur(10px);
            padding: 20px;
            border-radius: 12px;
            text-align: center;
        }

        .header-stat .number {
            font-size: 2.5em;
            font-weight: bold;
            display: block;
            margin-bottom: 5px;
        }

        .header-stat .label {
            font-size: 1em;
            opacity: 0.9;
        }

        /* Section Styling */
        .section {
            padding: 60px;
        }

        .section:nth-child(even) {
            background: var(--light-bg);
        }

        .section-header {
            text-align: center;
            margin-bottom: 50px;
        }

        .section-title {
            font-size: 2.8em;
            color: var(--primary-blue);
            margin-bottom: 15px;
            font-weight: 800;
            position: relative;
            display: inline-block;
            padding-bottom: 15px;
        }

        .section-title::after {
            content: '';
            position: absolute;
            bottom: 0;
            left: 50%;
            transform: translateX(-50%);
            width: 100px;
            height: 4px;
            background: linear-gradient(90deg, var(--accent-purple), var(--accent-violet));
            border-radius: 2px;
        }

        .section-subtitle {
            font-size: 1.2em;
            color: var(--text-light);
            max-width: 800px;
            margin: 15px auto 0;
        }

        /* Tier Cards */
        .tier-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(320px, 1fr));
            gap: 30px;
            margin-top: 40px;
        }

        .tier-card {
            background: var(--white);
            border-radius: 20px;
            padding: 40px;
            box-shadow: 0 10px 40px rgba(0, 0, 0, 0.1);
            transition: all 0.3s ease;
            position: relative;
            overflow: hidden;
        }

        .tier-card::before {
            content: '';
            position: absolute;
            top: 0;
            left: 0;
            right: 0;
            height: 8px;
        }

        .tier-card.economy::before {
            background: linear-gradient(90deg, var(--bronze), #cd7f32);
        }

        .tier-card.value::before {
            background: linear-gradient(90deg, var(--success-green), #229954);
        }

        .tier-card.usmade::before {
            background: linear-gradient(90deg, var(--secondary-blue), var(--primary-blue));
        }

        .tier-card.luxury::before {
            background: linear-gradient(90deg, var(--gold), #f39c12);
        }

        .tier-card:hover {
            transform: translateY(-10px);
            box-shadow: 0 20px 60px rgba(0, 0, 0, 0.15);
        }

        .tier-badge {
            display: inline-block;
            padding: 8px 20px;
            border-radius: 20px;
            font-size: 0.9em;
            font-weight: bold;
            margin-bottom: 20px;
            text-transform: uppercase;
        }

        .tier-card.economy .tier-badge {
            background: #fff3cd;
            color: var(--bronze);
            border: 2px solid var(--bronze);
        }

        .tier-card.value .tier-badge {
            background: #d1f2eb;
            color: var(--success-green);
            border: 2px solid var(--success-green);
        }

        .tier-card.usmade .tier-badge {
            background: #e8f4f8;
            color: var(--secondary-blue);
            border: 2px solid var(--secondary-blue);
        }

        .tier-card.luxury .tier-badge {
            background: #fef5e7;
            color: var(--gold);
            border: 2px solid var(--gold);
        }

        .tier-icon {
            font-size: 3em;
            display: block;
            margin-bottom: 15px;
        }

        .tier-card h3 {
            font-size: 2em;
            color: var(--primary-blue);
            margin-bottom: 15px;
        }

        .tier-description {
            color: var(--text-light);
            margin-bottom: 25px;
            font-size: 1.05em;
            line-height: 1.7;
        }

        .tier-specs {
            background: var(--light-bg);
            padding: 20px;
            border-radius: 12px;
            margin: 20px 0;
        }

        .tier-specs h4 {
            color: var(--primary-blue);
            margin-bottom: 12px;
            font-size: 1.2em;
        }

        .spec-item {
            display: flex;
            justify-content: space-between;
            padding: 10px 0;
            border-bottom: 1px solid rgba(0,0,0,0.1);
        }

        .spec-item:last-child {
            border-bottom: none;
        }

        .spec-label {
            font-weight: 600;
            color: var(--text-dark);
        }

        .spec-value {
            font-weight: 700;
        }

        .tier-card.economy .spec-value {
            color: var(--bronze);
        }

        .tier-card.value .spec-value {
            color: var(--success-green);
        }

        .tier-card.usmade .spec-value {
            color: var(--secondary-blue);
        }

        .tier-card.luxury .spec-value {
            color: var(--gold);
        }

        .tier-benefits {
            margin-top: 20px;
        }

        .tier-benefits h4 {
            color: var(--primary-blue);
            margin-bottom: 12px;
            font-size: 1.2em;
        }

        .tier-benefits ul {
            list-style: none;
            padding: 0;
        }

        .tier-benefits li {
            padding: 8px 0;
            padding-left: 25px;
            position: relative;
            color: var(--text-dark);
        }

        .tier-benefits li::before {
            content: '✓';
            position: absolute;
            left: 0;
            font-weight: bold;
            font-size: 1.2em;
        }

        .tier-card.economy .tier-benefits li::before {
            color: var(--bronze);
        }

        .tier-card.value .tier-benefits li::before {
            color: var(--success-green);
        }

        .tier-card.usmade .tier-benefits li::before {
            color: var(--secondary-blue);
        }

        .tier-card.luxury .tier-benefits li::before {
            color: var(--gold);
        }

        /* Info Boxes */
        .info-box {
            background: var(--white);
            border-left: 5px solid var(--accent-purple);
            padding: 25px;
            border-radius: 10px;
            margin: 20px 0;
            box-shadow: 0 4px 15px rgba(0, 0, 0, 0.08);
        }

        .info-box.success {
            border-left-color: var(--success-green);
            background: #f0fff4;
        }

        .info-box.warning {
            border-left-color: var(--warning-orange);
            background: #fff9f0;
        }

        .info-box h4 {
            font-size: 1.3em;
            margin-bottom: 15px;
            color: var(--primary-blue);
            display: flex;
            align-items: center;
            gap: 10px;
        }

        .info-box ul {
            margin-left: 20px;
            line-height: 1.8;
        }

        .info-box li {
            margin: 8px 0;
            color: var(--text-dark);
        }

        .info-box p {
            margin: 10px 0;
            line-height: 1.8;
        }

        /* Comparison Table */
        .comparison-table {
            background: var(--white);
            border-radius: 15px;
            overflow: hidden;
            box-shadow: 0 8px 30px rgba(0, 0, 0, 0.1);
            margin: 30px 0;
        }

        table {
            width: 100%;
            border-collapse: collapse;
        }

        thead {
            background: linear-gradient(135deg, var(--primary-blue) 0%, var(--secondary-blue) 100%);
            color: var(--white);
        }

        th {
            padding: 20px;
            text-align: left;
            font-weight: 700;
            font-size: 1.1em;
        }

        tbody tr {
            border-bottom: 1px solid var(--light-bg);
            transition: background 0.2s ease;
        }

        tbody tr:hover {
            background: var(--light-bg);
        }

        td {
            padding: 18px 20px;
            color: var(--text-dark);
        }

        /* Sales Script Box */
        .script-box {
            background: linear-gradient(135deg, var(--light-bg) 0%, #e9ecef 100%);
            border-left: 5px solid var(--accent-purple);
            padding: 30px;
            border-radius: 12px;
            margin: 30px 0;
            font-family: 'Courier New', monospace;
        }

        .script-box h4 {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            color: var(--primary-blue);
            margin-bottom: 20px;
            font-size: 1.4em;
        }

        .script-line {
            margin: 15px 0;
            line-height: 1.8;
        }

        .speaker {
            font-weight: bold;
            color: var(--primary-blue);
        }

        /* CTA Section */
        .cta-section {
            background: linear-gradient(135deg, var(--primary-blue) 0%, var(--secondary-blue) 100%);
            color: var(--white);
            padding: 60px;
            text-align: center;
        }

        .cta-section h2 {
            font-size: 2.5em;
            margin-bottom: 20px;
        }

        .cta-section p {
            font-size: 1.3em;
            margin-bottom: 30px;
            opacity: 0.95;
        }

        .cta-buttons {
            display: flex;
            justify-content: center;
            gap: 20px;
            flex-wrap: wrap;
        }

        .cta-btn {
            padding: 18px 40px;
            font-size: 1.1em;
            font-weight: bold;
            border-radius: 10px;
            text-decoration: none;
            transition: all 0.3s ease;
            display: inline-flex;
            align-items: center;
            gap: 10px;
        }

        .cta-btn.primary {
            background: var(--success-green);
            color: var(--white);
        }

        .cta-btn.primary:hover {
            background: #229954;
            transform: translateY(-3px);
            box-shadow: 0 10px 30px rgba(39, 174, 96, 0.4);
        }

        .cta-btn.secondary {
            background: var(--white);
            color: var(--primary-blue);
        }

        .cta-btn.secondary:hover {
            background: var(--light-bg);
            transform: translateY(-3px);
        }

        /* Footer */
        .footer {
            background: linear-gradient(135deg, var(--primary-blue) 0%, var(--secondary-blue) 100%);
            color: var(--white);
            padding: 40px 60px;
            text-align: center;
        }

        .footer p {
            opacity: 0.9;
            margin: 5px 0;
        }

        /* Responsive Design */
        @media (max-width: 1200px) {
            .tier-grid {
                grid-template-columns: repeat(2, 1fr);
            }
        }

        @media (max-width: 768px) {
            body { padding: 10px; }
            .header, .section { padding: 30px 20px; }
            .header h1 { font-size: 2.2em; }
            .section-title { font-size: 1.8em; }
            .language-toggle {
                flex-direction: column;
                gap: 15px;
                padding: 15px;
            }
            .tier-grid {
                grid-template-columns: 1fr;
            }
        }
    </style>
</head>
<body>
    <div class="container">
        <!-- Language Toggle & Navigation -->
        <div class="language-toggle">
            <div class="nav-links">
                <a href="PRIMARY-LANDING-PAGE.html" class="back-link">
                    ← Back to Portfolio
                </a>
            </div>
            <div class="lang-buttons">
                <button class="lang-btn active" onclick="switchLanguage('en')" data-lang="en">🇺🇸 EN</button>
                <button class="lang-btn" onclick="switchLanguage('ru')" data-lang="ru">🇷🇺 RU</button>
                <button class="lang-btn" onclick="switchLanguage('uz')" data-lang="uz">🇺🇿 UZ</button>
            </div>
        </div>

        <!-- ENGLISH CONTENT -->
        <div class="lang-content active" id="content-en">
            <!-- Header -->
            <div class="header">
                <span class="doc-badge">Document 4 | Critical</span>
                <h1>💰 4-Tier Pricing Strategy</h1>
                <p class="subtitle">Comprehensive Pricing Approach for Every Market Segment</p>
                
                <div class="header-stats">
                    <div class="header-stat">
                        <span class="number">4</span>
                        <span class="label">Pricing Tiers</span>
                    </div>
                    <div class="header-stat">
                        <span class="number">25-55%</span>
                        <span class="label">Gross Margin Range</span>
                    </div>
                    <div class="header-stat">
                        <span class="number">100%</span>
                        <span class="label">Market Coverage</span>
                    </div>
                    <div class="header-stat">
                        <span class="number">Tier 2</span>
                        <span class="label">Recommended Default</span>
                    </div>
                </div>
            </div>

            <!-- Strategy Overview -->
            <div class="section">
                <div class="section-header">
                    <h2 class="section-title">Pricing Strategy Overview</h2>
                    <p class="section-subtitle">
                        Four distinct pricing tiers designed to capture every market segment from budget-conscious to luxury buyers
                    </p>
                </div>

                <div class="info-box success">
                    <h4>✅ Why 4 Tiers?</h4>
                    <p><strong>Our 4-tier pricing strategy is designed to maximize market penetration while maintaining healthy margins across all customer segments.</strong> By offering multiple price points for the same product category, we can serve budget-conscious buyers, value-seekers, "Buy American" advocates, and luxury customers—all from the same inventory system.</p>
                    
                    <p style="margin-top: 20px;"><strong>Key Benefits:</strong></p>
                    <ul>
                        <li><strong>Complete Market Coverage:</strong> From economy to luxury, we serve every price-sensitive segment</li>
                        <li><strong>Margin Optimization:</strong> Higher-tier products offset lower margins on economy items</li>
                        <li><strong>Customer Psychology:</strong> Middle options (Value tier) appear as the "smart choice" when presented with extremes</li>
                        <li><strong>Competitive Positioning:</strong> We can compete on both price and quality depending on customer needs</li>
                        <li><strong>Upsell Opportunities:</strong> Clear upgrade path from economy to value to premium tiers</li>
                        <li><strong>Insurance Flexibility:</strong> Different tiers accommodate various insurance reimbursement levels</li>
                    </ul>
                </div>

                <div class="info-box warning">
                    <h4>🎯 Recommended Default: Tier 2 (Value)</h4>
                    <p>Unless a customer specifically requests economy pricing or has clear luxury preferences, <strong>always present Tier 2 (Value) products as the default recommendation.</strong> This tier offers the best balance of quality, reliability, and price—making it the easiest to sell and resulting in the highest customer satisfaction.</p>
                    <p style="margin-top: 15px;"><strong>Only deviate from Tier 2 when:</strong></p>
                    <ul>
                        <li>Customer explicitly mentions budget constraints → Tier 1 (Economy)</li>
                        <li>Customer emphasizes "Buy American" values → Tier 3 (US-Made)</li>
                        <li>Customer is price-insensitive or wants "the best" → Tier 4 (Luxury)</li>
                    </ul>
                </div>
            </div>

            <!-- All 4 Tiers -->
            <div class="section">
                <div class="section-header">
                    <h2 class="section-title">The 4 Pricing Tiers</h2>
                    <p class="section-subtitle">
                        Comprehensive breakdown of each tier with target markets, margins, and ideal use cases
                    </p>
                </div>

                <div class="tier-grid">
                    <!-- Tier 1: Economy -->
                    <div class="tier-card economy">
                        <span class="tier-badge">Tier 1</span>
                        <span class="tier-icon">🥉</span>
                        <h3>Economy</h3>
                        <p class="tier-description">
                            Budget-friendly options for price-sensitive customers. Basic functionality without frills. 
                            Typically imported products meeting minimum quality standards.
                        </p>

                        <div class="tier-specs">
                            <h4>Tier Specifications</h4>
                            <div class="spec-item">
                                <span class="spec-label">Price Point:</span>
                                <span class="spec-value">20-30% below market avg</span>
                            </div>
                            <div class="spec-item">
                                <span class="spec-label">Gross Margin:</span>
                                <span class="spec-value">25-35%</span>
                            </div>
                            <div class="spec-item">
                                <span class="spec-label">Product Origin:</span>
                                <span class="spec-value">Imported (China, India)</span>
                            </div>
                            <div class="spec-item">
                                <span class="spec-label">Warranty:</span>
                                <span class="spec-value">90 days - 1 year</span>
                            </div>
                        </div>

                        <div class="tier-benefits">
                            <h4>Best For:</h4>
                            <ul>
                                <li>Cash-pay customers on tight budgets</li>
                                <li>Secondary/backup equipment</li>
                                <li>Short-term rental needs</li>
                                <li>Budget-conscious facilities</li>
                                <li>Customers with high deductibles</li>
                            </ul>
                        </div>
                    </div>

                    <!-- Tier 2: Value -->
                    <div class="tier-card value">
                        <span class="tier-badge">Tier 2 ⭐ Recommended</span>
                        <span class="tier-icon">⭐</span>
                        <h3>Value</h3>
                        <p class="tier-description">
                            The "sweet spot" offering excellent quality at competitive prices. This is our DEFAULT recommendation 
                            for most customers—reliable brands with proven track records.
                        </p>

                        <div class="tier-specs">
                            <h4>Tier Specifications</h4>
                            <div class="spec-item">
                                <span class="spec-label">Price Point:</span>
                                <span class="spec-value">Market competitive</span>
                            </div>
                            <div class="spec-item">
                                <span class="spec-label">Gross Margin:</span>
                                <span class="spec-value">35-45%</span>
                            </div>
                            <div class="spec-item">
                                <span class="spec-label">Product Origin:</span>
                                <span class="spec-value">Mix (quality imports & US)</span>
                            </div>
                            <div class="spec-item">
                                <span class="spec-label">Warranty:</span>
                                <span class="spec-value">1-3 years</span>
                            </div>
                        </div>

                        <div class="tier-benefits">
                            <h4>Best For:</h4>
                            <ul>
                                <li><strong>Most insurance customers (90%)</strong></li>
                                <li>Long-term/permanent use</li>
                                <li>Quality-conscious value seekers</li>
                                <li>Standard Medicare/Medicaid billing</li>
                                <li><strong>Default recommendation</strong></li>
                            </ul>
                        </div>
                    </div>

                    <!-- Tier 3: US-Made Premium -->
                    <div class="tier-card usmade">
                        <span class="tier-badge">Tier 3</span>
                        <span class="tier-icon">🇺🇸</span>
                        <h3>US-Made Premium</h3>
                        <p class="tier-description">
                            American-manufactured products for customers who value domestic production, higher quality materials, 
                            and supporting American workers and businesses.
                        </p>

                        <div class="tier-specs">
                            <h4>Tier Specifications</h4>
                            <div class="spec-item">
                                <span class="spec-label">Price Point:</span>
                                <span class="spec-value">40-60% premium over economy</span>
                            </div>
                            <div class="spec-item">
                                <span class="spec-label">Gross Margin:</span>
                                <span class="spec-value">40-50%</span>
                            </div>
                            <div class="spec-item">
                                <span class="spec-label">Product Origin:</span>
                                <span class="spec-value">Made in USA</span>
                            </div>
                            <div class="spec-item">
                                <span class="spec-label">Warranty:</span>
                                <span class="spec-value">2-5 years</span>
                            </div>
                        </div>

                        <div class="tier-benefits">
                            <h4>Best For:</h4>
                            <ul>
                                <li>"Buy American" advocates</li>
                                <li>Veterans and military families</li>
                                <li>Premium facilities and hospitals</li>
                                <li>Quality-first customers</li>
                                <li>Environmental/ethical buyers</li>
                            </ul>
                        </div>
                    </div>

                    <!-- Tier 4: Luxury -->
                    <div class="tier-card luxury">
                        <span class="tier-badge">Tier 4</span>
                        <span class="tier-icon">👑</span>
                        <h3>Luxury</h3>
                        <p class="tier-description">
                            Premium brands with cutting-edge features, superior aesthetics, and white-glove service. 
                            For affluent customers who want the absolute best available.
                        </p>

                        <div class="tier-specs">
                            <h4>Tier Specifications</h4>
                            <div class="spec-item">
                                <span class="spec-label">Price Point:</span>
                                <span class="spec-value">80-120% premium over economy</span>
                            </div>
                            <div class="spec-item">
                                <span class="spec-label">Gross Margin:</span>
                                <span class="spec-value">45-55%</span>
                            </div>
                            <div class="spec-item">
                                <span class="spec-label">Product Origin:</span>
                                <span class="spec-value">Premium brands (US/Europe)</span>
                            </div>
                            <div class="spec-item">
                                <span class="spec-label">Warranty:</span>
                                <span class="spec-value">3-7 years + concierge</span>
                            </div>
                        </div>

                        <div class="tier-benefits">
                            <h4>Best For:</h4>
                            <ul>
                                <li>High-net-worth individuals</li>
                                <li>Golf course programs (Strategy 2)</li>
                                <li>Concierge medical services</li>
                                <li>No-compromise buyers</li>
                                <li>Luxury senior living facilities</li>
                            </ul>
                        </div>
                    </div>
                </div>
            </div>

            <!-- Pricing Examples Across Categories -->
            <div class="section">
                <div class="section-header">
                    <h2 class="section-title">Pricing Examples by Product Category</h2>
                    <p class="section-subtitle">
                        Real-world pricing across all four tiers for popular DME products
                    </p>
                </div>

                <div class="comparison-table">
                    <table>
                        <thead>
                            <tr>
                                <th>Product</th>
                                <th>Tier 1: Economy</th>
                                <th>Tier 2: Value ⭐</th>
                                <th>Tier 3: US-Made</th>
                                <th>Tier 4: Luxury</th>
                            </tr>
                        </thead>
                        <tbody>
                            <tr>
                                <td><strong>Standard Cane</strong></td>
                                <td>$15-$25</td>
                                <td>$35-$50</td>
                                <td>$60-$85</td>
                                <td>$100-$150</td>
                            </tr>
                            <tr>
                                <td><strong>Folding Walker</strong></td>
                                <td>$35-$55</td>
                                <td>$70-$100</td>
                                <td>$120-$170</td>
                                <td>$200-$280</td>
                            </tr>
                            <tr>
                                <td><strong>4-Wheel Rollator</strong></td>
                                <td>$80-$120</td>
                                <td>$150-$210</td>
                                <td>$240-$330</td>
                                <td>$380-$520</td>
                            </tr>
                            <tr>
                                <td><strong>Manual Wheelchair</strong></td>
                                <td>$150-$250</td>
                                <td>$350-$500</td>
                                <td>$600-$850</td>
                                <td>$1,000-$1,500</td>
                            </tr>
                            <tr>
                                <td><strong>Transport Wheelchair</strong></td>
                                <td>$120-$180</td>
                                <td>$250-$380</td>
                                <td>$450-$650</td>
                                <td>$800-$1,200</td>
                            </tr>
                            <tr>
                                <td><strong>Shower Chair</strong></td>
                                <td>$40-$65</td>
                                <td>$85-$120</td>
                                <td>$140-$190</td>
                                <td>$220-$300</td>
                            </tr>
                            <tr>
                                <td><strong>Bedside Commode</strong></td>
                                <td>$45-$70</td>
                                <td>$90-$130</td>
                                <td>$150-$210</td>
                                <td>$250-$350</td>
                            </tr>
                            <tr>
                                <td><strong>Hospital Bed (Semi-Electric)</strong></td>
                                <td>$800-$1,200</td>
                                <td>$1,500-$2,200</td>
                                <td>$2,500-$3,500</td>
                                <td>$4,000-$5,500</td>
                            </tr>
                            <tr>
                                <td><strong>CPAP Machine</strong></td>
                                <td>$400-$600</td>
                                <td>$800-$1,200</td>
                                <td>$1,400-$1,900</td>
                                <td>$2,200-$3,000</td>
                            </tr>
                            <tr>
                                <td><strong>Compression Stockings (Knee)</strong></td>
                                <td>$25-$40</td>
                                <td>$50-$75</td>
                                <td>$90-$130</td>
                                <td>$150-$220</td>
                            </tr>
                            <tr>
                                <td><strong>Diabetic Shoes</strong></td>
                                <td>$80-$120</td>
                                <td>$150-$220</td>
                                <td>$260-$370</td>
                                <td>$420-$600</td>
                            </tr>
                            <tr>
                                <td><strong>Portable Oxygen Concentrator</strong></td>
                                <td>$1,500-$2,200</td>
                                <td>$2,500-$3,200</td>
                                <td>$3,500-$4,500</td>
                                <td>$5,000-$6,500</td>
                            </tr>
                        </tbody>
                    </table>
                </div>

                <div class="info-box">
                    <h4>💡 Pricing Pattern Observations</h4>
                    <ul>
                        <li><strong>Price Multiples:</strong> Luxury tier typically costs 2-4x economy tier for same product category</li>
                        <li><strong>Value Positioning:</strong> Tier 2 (Value) sits at 1.5-2.5x economy pricing—the psychological "sweet spot"</li>
                        <li><strong>US-Made Premium:</strong> Tier 3 commands 1.5-2x economy premium, justified by domestic manufacturing</li>
                        <li><strong>Higher-Ticket Items:</strong> More expensive categories (wheelchairs, beds) show wider price spreads</li>
                        <li><strong>Consumables:</strong> Lower-cost items (canes, compression) have tighter price ranges across tiers</li>
                    </ul>
                </div>
            </div>

            <!-- Sales Presentation Scripts -->
            <div class="section">
                <div class="section-header">
                    <h2 class="section-title">Sales Presentation Scripts</h2>
                    <p class="section-subtitle">
                        How to present pricing tiers to customers for maximum conversion and satisfaction
                    </p>
                </div>

                <div class="info-box success">
                    <h4>🎯 Presentation Strategy: The "Good-Better-Best" Approach</h4>
                    <p><strong>Always present THREE options to customers (not all four):</strong></p>
                    <ul>
                        <li><strong>Default Presentation:</strong> Economy (Good), Value (Better ⭐), US-Made (Best)</li>
                        <li><strong>For Affluent Customers:</strong> Value (Good), US-Made (Better), Luxury (Best ⭐)</li>
                        <li><strong>For Budget Customers:</strong> Economy (Good ⭐), Value (Better), US-Made (Best)</li>
                    </ul>
                    <p style="margin-top: 15px;"><strong>Why three options?</strong> Psychology research shows that when presented with 3 choices, most customers choose the middle option—which should always be your target tier. Four options creates analysis paralysis.</p>
                </div>

                <div class="script-box">
                    <h4>Script 1: Standard Customer (Default to Tier 2 - Value)</h4>
                    
                    <div class="script-line">
                        <span class="speaker">Sales Rep:</span> "We have several excellent options for you. Let me show you our three most popular models."
                    </div>
                    
                    <div class="script-line">
                        <span class="speaker">Sales Rep:</span> "First, we have our <strong>Economy model</strong> at $150. It's a solid, basic wheelchair that gets the job done. Great if you're on a tight budget or need something temporary."
                    </div>
                    
                    <div class="script-line">
                        <span class="speaker">Sales Rep:</span> "Next is our <strong>Value model</strong> at $350—this is actually our most popular choice. It's a quality wheelchair from a trusted brand with a 2-year warranty. Most of our customers find this to be the sweet spot between quality and price. <strong>This is what I'd recommend for most people.</strong>"
                    </div>
                    
                    <div class="script-line">
                        <span class="speaker">Sales Rep:</span> "Finally, we have our <strong>US-Made Premium model</strong> at $600. This is manufactured right here in America with higher-quality materials and a 3-year warranty. Great if you want to support American manufacturing or need the most durable option."
                    </div>
                    
                    <div class="script-line">
                        <span class="speaker">Sales Rep:</span> "Which of these sounds like the best fit for your needs?"
                    </div>
                    
                    <div class="script-line">
                        <span class="speaker">[Expected Result:]</span> <em>Customer chooses Value tier (Tier 2) - your target</em>
                    </div>
                </div>

                <div class="script-box">
                    <h4>Script 2: Affluent Customer (Default to Tier 3 - US-Made)</h4>
                    
                    <div class="script-line">
                        <span class="speaker">Sales Rep:</span> "For someone looking for quality, I'd recommend looking at our premium options."
                    </div>
                    
                    <div class="script-line">
                        <span class="speaker">Sales Rep:</span> "We have our <strong>Value model</strong> at $350—it's a solid, reliable wheelchair that most people choose."
                    </div>
                    
                    <div class="script-line">
                        <span class="speaker">Sales Rep:</span> "Our <strong>US-Made Premium</strong> at $600 is manufactured in America with superior craftsmanship and materials. This is what I personally would choose—it's built to last and supports American workers."
                    </div>
                    
                    <div class="script-line">
                        <span class="speaker">Sales Rep:</span> "And if you want absolutely the best available, our <strong>Luxury model</strong> at $1,000 features cutting-edge technology, premium materials, and includes white-glove delivery and setup. This is for customers who don't want to compromise on anything."
                    </div>
                    
                    <div class="script-line">
                        <span class="speaker">Sales Rep:</span> "Given what you've told me about your needs, which of these appeals to you most?"
                    </div>
                    
                    <div class="script-line">
                        <span class="speaker">[Expected Result:]</span> <em>Customer chooses US-Made (Tier 3) or Luxury (Tier 4)</em>
                    </div>
                </div>

                <div class="script-box">
                    <h4>Script 3: Budget-Conscious Customer (Default to Tier 1 - Economy)</h4>
                    
                    <div class="script-line">
                        <span class="speaker">Customer:</span> "I really need to keep costs down. What's your cheapest option?"
                    </div>
                    
                    <div class="script-line">
                        <span class="speaker">Sales Rep:</span> "I completely understand. Let me show you our budget-friendly options that still provide good quality."
                    </div>
                    
                    <div class="script-line">
                        <span class="speaker">Sales Rep:</span> "Our <strong>Economy model</strong> is $150. It's our most affordable option and meets all safety standards. It's perfect if you're on a tight budget."
                    </div>
                    
                    <div class="script-line">
                        <span class="speaker">Sales Rep:</span> "Now, I want to mention our <strong>Value model</strong> at $350. It's $200 more, but you get a significantly better warranty and it's much more durable. Many customers find that spending a bit more upfront saves money long-term because it lasts longer. If you can swing the extra $200, I'd recommend it."
                    </div>
                    
                    <div class="script-line">
                        <span class="speaker">Sales Rep:</span> "We also have a US-Made option at $600 if you're interested, but given your budget concerns, I'd focus on these first two."
                    </div>
                    
                    <div class="script-line">
                        <span class="speaker">Sales Rep:</span> "What fits your budget better—the Economy at $150 or would the Value model at $350 work?"
                    </div>
                    
                    <div class="script-line">
                        <span class="speaker">[Expected Result:]</span> <em>Customer chooses Economy (Tier 1) or upgrades to Value (Tier 2)</em>
                    </div>
                </div>

                <div class="info-box warning">
                    <h4>⚠️ Critical Sales Rules</h4>
                    <ul>
                        <li><strong>Never present all 4 tiers at once</strong> - Always show 3 options maximum</li>
                        <li><strong>Lead with benefits, not just price</strong> - "Quality construction" not just "$350"</li>
                        <li><strong>Position the middle as recommended</strong> - "This is our most popular" or "This is what I'd choose"</li>
                        <li><strong>Anchor with the highest price first</strong> - Makes middle option seem more reasonable</li>
                        <li><strong>If customer wants cheaper than Economy</strong> - Don't have anything cheaper, but emphasize value</li>
                        <li><strong>If customer wants more than Luxury</strong> - Position Luxury as "the absolute best available"</li>
                    </ul>
                </div>
            </div>

            <!-- Competitive Positioning -->
            <div class="section">
                <div class="section-header">
                    <h2 class="section-title">Competitive Positioning</h2>
                    <p class="section-subtitle">
                        How our 4-tier pricing stacks up against major competitors
                    </p>
                </div>

                <div class="comparison-table">
                    <table>
                        <thead>
                            <tr>
                                <th>Product Category</th>
                                <th>Online Retailers<br>(Amazon, etc.)</th>
                                <th>Big Box Stores<br>(Walmart, Costco)</th>
                                <th>National Chains<br>(Apria, Lincare)</th>
                                <th>Our Positioning</th>
                            </tr>
                        </thead>
                        <tbody>
                            <tr>
                                <td><strong>Standard Walker</strong></td>
                                <td>$35-$60<br><em>(Economy tier)</em></td>
                                <td>$50-$80<br><em>(Economy-Value)</em></td>
                                <td>$90-$140<br><em>(Value-Premium)</em></td>
                                <td><strong>$35-$280</strong><br><em>Compete at all levels</em></td>
                            </tr>
                            <tr>
                                <td><strong>Manual Wheelchair</strong></td>
                                <td>$100-$300<br><em>(Economy-Value)</em></td>
                                <td>$150-$400<br><em>(Economy-Value)</em></td>
                                <td>$350-$800<br><em>(Value-Premium)</em></td>
                                <td><strong>$150-$1,500</strong><br><em>Match + exceed</em></td>
                            </tr>
                            <tr>
                                <td><strong>Hospital Bed</strong></td>
                                <td>$600-$1,800<br><em>(Limited selection)</em></td>
                                <td>Not typically carried</td>
                                <td>$1,200-$3,500<br><em>(Rental focus)</em></td>
                                <td><strong>$800-$5,500</strong><br><em>Lower floor, higher ceiling</em></td>
                            </tr>
                            <tr>
                                <td><strong>CPAP Machine</strong></td>
                                <td>$300-$1,200<br><em>(No insurance)</em></td>
                                <td>Not typically carried</td>
                                <td>$800-$2,000<br><em>(Insurance only)</em></td>
                                <td><strong>$400-$3,000</strong><br><em>Cash + insurance</em></td>
                            </tr>
                        </tbody>
                    </table>
                </div>

                <div class="info-box success">
                    <h4>✅ Our Competitive Advantages</h4>
                    <ul>
                        <li><strong>Price Matching:</strong> Our Economy tier can compete with online retailers and big box stores</li>
                        <li><strong>Service Differentiation:</strong> We offer setup, training, and ongoing support—online retailers don't</li>
                        <li><strong>Insurance Expertise:</strong> We handle insurance billing—competitors often charge full retail</li>
                        <li><strong>Product Range:</strong> Four tiers mean we can match any competitor's price point</li>
                        <li><strong>Local Presence:</strong> Same-day delivery and in-person service beats online shipping</li>
                        <li><strong>Quality Options:</strong> We offer premium tiers that mass merchants don't carry</li>
                    </ul>
                </div>

                <div class="info-box warning">
                    <h4>⚠️ When to Price Match</h4>
                    <p><strong>If a customer mentions a lower price from a competitor:</strong></p>
                    <ul>
                        <li><strong>Step 1:</strong> Ask what product specifically (model number, features)</li>
                        <li><strong>Step 2:</strong> Verify it's apples-to-apples comparison (same quality/warranty)</li>
                        <li><strong>Step 3:</strong> If it's Economy tier equivalent, offer our Economy pricing</li>
                        <li><strong>Step 4:</strong> Then upsell to Value tier: "For just $X more, you get much better quality..."</li>
                        <li><strong>Step 5:</strong> Emphasize our service, insurance handling, and local support</li>
                    </ul>
                    <p style="margin-top: 15px;"><strong>Don't automatically match</strong> without understanding what they're comparing. Often competitors quote lower-quality products.</p>
                </div>
            </div>

            <!-- Implementation Guidelines -->
            <div class="section">
                <div class="section-header">
                    <h2 class="section-title">Implementation Guidelines</h2>
                    <p class="section-subtitle">
                        Practical steps for rolling out the 4-tier pricing strategy across all operations
                    </p>
                </div>

                <div class="info-box">
                    <h4>📋 Phase 1: Setup (Week 1-2)</h4>
                    <ul>
                        <li><strong>Inventory Setup:</strong> Ensure you have stock in at least Tier 1 (Economy) and Tier 2 (Value) for top 20 products</li>
                        <li><strong>Price Lists:</strong> Create printed price sheets showing all 4 tiers for each product category</li>
                        <li><strong>POS System:</strong> Configure point-of-sale to show all tiers when staff scan a product</li>
                        <li><strong>Website Updates:</strong> Add tier filters and comparison tools to e-commerce platform</li>
                        <li><strong>Sales Training:</strong> Train all sales staff on the 3-option presentation method</li>
                    </ul>
                </div>

                <div class="info-box">
                    <h4>📋 Phase 2: Staff Training (Week 2-3)</h4>
                    <ul>
                        <li><strong>Role Playing:</strong> Practice sales scripts with all customer-facing staff</li>
                        <li><strong>Product Knowledge:</strong> Ensure staff understand the actual differences between tiers</li>
                        <li><strong>Objection Handling:</strong> Train on responding to "that's too expensive" or "do you have anything cheaper?"</li>
                        <li><strong>Insurance Coordination:</strong> Billing staff understand which tiers are typically covered at what rates</li>
                        <li><strong>Performance Metrics:</strong> Track which tiers are being sold and average transaction value</li>
                    </ul>
                </div>

                <div class="info-box">
                    <h4>📋 Phase 3: Marketing & Communication (Week 3-4)</h4>
                    <ul>
                        <li><strong>Showroom Displays:</strong> Create visual displays showing same product in all 4 tiers side-by-side</li>
                        <li><strong>Printed Materials:</strong> Design brochures explaining the 4 tiers and helping customers choose</li>
                        <li><strong>Digital Marketing:</strong> Update website, social media, and ads to reference "options for every budget"</li>
                        <li><strong>Partnership Communication:</strong> Inform hospitals, facilities, and partners about pricing structure</li>
                        <li><strong>Patient Education:</strong> Create simple guides explaining how to choose the right tier</li>
                    </ul>
                </div>

                <div class="info-box warning">
                    <h4>🎯 Monitoring & Optimization (Ongoing)</h4>
                    <ul>
                        <li><strong>Track Sales Mix:</strong> Goal should be 20% Tier 1, 60% Tier 2, 15% Tier 3, 5% Tier 4</li>
                        <li><strong>Monitor Margins:</strong> Ensure overall gross margin stays above 40% blended across all tiers</li>
                        <li><strong>Customer Feedback:</strong> Survey satisfaction levels by tier—are Economy customers happy?</li>
                        <li><strong>Price Adjustments:</strong> Review pricing quarterly and adjust for cost changes</li>
                        <li><strong>Competitive Intelligence:</strong> Monitor competitor pricing and adjust positioning as needed</li>
                    </ul>
                </div>
            </div>

            <!-- Price Flexibility Guidelines -->
            <div class="section">
                <div class="section-header">
                    <h2 class="section-title">Price Flexibility & Discounting</h2>
                    <p class="section-subtitle">
                        When and how to offer discounts while protecting margins
                    </p>
                </div>

                <div class="info-box warning">
                    <h4>⚠️ Discount Authority Levels</h4>
                    <ul>
                        <li><strong>Sales Staff (No approval needed):</strong> 0-5% discount for any reason</li>
                        <li><strong>Sales Manager Approval Required:</strong> 5-10% discount</li>
                        <li><strong>Owner/Director Approval Required:</strong> 10-15% discount (rare circumstances only)</li>
                        <li><strong>Never Discount Below:</strong> 15% off retail price (protects minimum margins)</li>
                    </ul>
                </div>

                <div class="comparison-table">
                    <table>
                        <thead>
                            <tr>
                                <th>Situation</th>
                                <th>Recommended Action</th>
                                <th>Max Discount</th>
                                <th>Approval Needed</th>
                            </tr>
                        </thead>
                        <tbody>
                            <tr>
                                <td>Customer mentions lower competitor price</td>
                                <td>Verify, then offer Economy tier</td>
                                <td>0% (change tier)</td>
                                <td>None</td>
                            </tr>
                            <tr>
                                <td>Customer buying multiple items (3+)</td>
                                <td>Volume discount</td>
                                <td>5-10%</td>
                                <td>Manager if >5%</td>
                            </tr>
                            <tr>
                                <td>Slow-moving inventory</td>
                                <td>Clearance pricing</td>
                                <td>10-20%</td>
                                <td>Manager</td>
                            </tr>
                            <tr>
                                <td>Facility/partnership program</td>
                                <td>Contract pricing</td>
                                <td>15%</td>
                                <td>Owner</td>
                            </tr>
                            <tr>
                                <td>Military/veteran customer</td>
                                <td>Thank you discount</td>
                                <td>5-10%</td>
                                <td>None if ≤5%</td>
                            </tr>
                            <tr>
                                <td>Financial hardship (documented)</td>
                                <td>Hardship pricing program</td>
                                <td>10-15%</td>
                                <td>Manager</td>
                            </tr>
                            <tr>
                                <td>Product defect/damage</td>
                                <td>As-is discount</td>
                                <td>20-40%</td>
                                <td>Manager</td>
                            </tr>
                            <tr>
                                <td>Customer service recovery</td>
                                <td>Goodwill discount</td>
                                <td>10-25%</td>
                                <td>Manager</td>
                            </tr>
                        </tbody>
                    </table>
                </div>

                <div class="info-box success">
                    <h4>✅ Better Than Discounting: Value Adds</h4>
                    <p><strong>Instead of lowering price, consider adding value:</strong></p>
                    <ul>
                        <li><strong>Free Delivery:</strong> Saves customer $50-$100, costs you $20-$30</li>
                        <li><strong>Free Setup/Training:</strong> Perceived value $75-$150, costs you $30-$60 in labor</li>
                        <li><strong>Extended Warranty:</strong> Add 1 year warranty (costs minimal, high perceived value)</li>
                        <li><strong>Accessories Bundle:</strong> Include $50 in accessories (cushion, basket, etc.) at cost</li>
                        <li><strong>Future Discount Coupon:</strong> "$50 off next purchase" keeps them coming back</li>
                        <li><strong>Consumables Package:</strong> For CPAP, include 3 months of supplies</li>
                    </ul>
                    <p style="margin-top: 15px;"><strong>Why value-adds beat discounts:</strong> Perceived value is higher than actual cost, maintains price integrity, builds loyalty, and protects margins better than straight discounts.</p>
                </div>
            </div>

            <!-- CTA Section -->
            <div class="cta-section">
                <h2>💰 Ready to Implement This Pricing Strategy?</h2>
                <p>
                    This 4-tier approach maximizes market coverage and margin optimization. Review the complete 
                    product portfolio and revenue projections to see how this pricing drives profitability.
                </p>
                <div class="cta-buttons">
                    <a href="complete-dme-product-portfolio.html" class="cta-btn primary">
                        View Product Portfolio →
                    </a>
                    <a href="complete-revenue-summary.html" class="cta-btn secondary">
                        Revenue Projections →
                    </a>
                    <a href="PRIMARY-LANDING-PAGE.html#all-strategies" class="cta-btn secondary">
                        All 11 Strategies →
                    </a>
                </div>
            </div>

            <!-- Footer -->
            <div class="footer">
                <p><strong>Holistic Medical Supply</strong> | 4-Tier Pricing Strategy</p>
                <p>Document 4 of 34 | Last Updated: October 25, 2025 | Version 1.0</p>
                <p>Nassau County, New York | Tier 2 (Value) Recommended Default</p>
            </div>
        </div>

        <!-- RUSSIAN & UZBEK CONTENT (Abbreviated) -->
        <div class="lang-content" id="content-ru">
            <div class="header">
                <span class="doc-badge">Документ 4 | Критический</span>
                <h1>💰 4-уровневая стратегия ценообразования</h1>
                <p class="subtitle">Комплексный подход к ценообразованию для каждого сегмента рынка</p>
                
                <div class="header-stats">
                    <div class="header-stat">
                        <span class="number">4</span>
                        <span class="label">Ценовых уровня</span>
                    </div>
                    <div class="header-stat">
                        <span class="number">25-55%</span>
                        <span class="label">Диапазон маржи</span>
                    </div>
                    <div class="header-stat">
                        <span class="number">100%</span>
                        <span class="label">Покрытие рынка</span>
                    </div>
                    <div class="header-stat">
                        <span class="number">Уровень 2</span>
                        <span class="label">Рекомендуется по умолчанию</span>
                    </div>
                </div>
            </div>

            <div class="section">
                <div class="info-box success">
                    <h4>✅ 4-уровневая система ценообразования</h4>
                    <p>Полная информация о стратегии ценообразования доступна в английской версии документа.</p>
                    <p><strong>Четыре уровня:</strong></p>
                    <ul>
                        <li><strong>Уровень 1: Эконом (🥉):</strong> 25-35% маржа, бюджетные покупатели</li>
                        <li><strong>Уровень 2: Оптимальное качество (⭐ Рекомендуется):</strong> 35-45% маржа, лучшее соотношение цены и качества</li>
                        <li><strong>Уровень 3: Сделано в США (🇺🇸):</strong> 40-50% маржа, американское производство</li>
                        <li><strong>Уровень 4: Люкс (👑):</strong> 45-55% маржа, премиум покупатели</li>
                    </ul>
                    <p style="margin-top: 20px;"><strong>Рекомендация по умолчанию:</strong> Уровень 2 (Оптимальное качество) для 90% клиентов</p>
                </div>
            </div>

            <div class="cta-section">
                <h2>💰 Готовы внедрить эту стратегию?</h2>
                <div class="cta-buttons">
                    <a href="complete-dme-product-portfolio.html" class="cta-btn primary">
                        Портфель продуктов →
                    </a>
                    <a href="PRIMARY-LANDING-PAGE.html#all-strategies" class="cta-btn secondary">
                        Все стратегии →
                    </a>
                </div>
            </div>

            <div class="footer">
                <p><strong>Holistic Medical Supply</strong> | 4-уровневая стратегия ценообразования</p>
                <p>Документ 4 из 34 | 25 октября 2025 | Версия 1.0</p>
            </div>
        </div>

        <div class="lang-content" id="content-uz">
            <div class="header">
                <span class="doc-badge">Hujjat 4 | Muhim</span>
                <h1>💰 4 darajali narx strategiyasi</h1>
                <p class="subtitle">Har bir bozor segmenti uchun kompleks narxlash yondashuvi</p>
                
                <div class="header-stats">
                    <div class="header-stat">
                        <span class="number">4</span>
                        <span class="label">Narx darajalari</span>
                    </div>
                    <div class="header-stat">
                        <span class="number">25-55%</span>
                        <span class="label">Marja diapazoni</span>
                    </div>
                    <div class="header-stat">
                        <span class="number">100%</span>
                        <span class="label">Bozor qamrovi</span>
                    </div>
                    <div class="header-stat">
                        <span class="number">Daraja 2</span>
                        <span class="label">Tavsiya etiladi</span>
                    </div>
                </div>
            </div>

            <div class="section">
                <div class="info-box success">
                    <h4>✅ 4 darajali narxlash tizimi</h4>
                    <p>Narxlash strategiyasi haqida to'liq ma'lumot hujjatning ingliz tilidagi versiyasida mavjud.</p>
                    <p><strong>To'rt daraja:</strong></p>
                    <ul>
                        <li><strong>Daraja 1: Ekonom (🥉):</strong> 25-35% marja, byudjet xaridorlari</li>
                        <li><strong>Daraja 2: Qiymat (⭐ Tavsiya etiladi):</strong> 35-45% marja, eng yaxshi narx va sifat</li>
                        <li><strong>Daraja 3: AQShda ishlab chiqarilgan (🇺🇸):</strong> 40-50% marja, Amerika ishlab chiqarish</li>
                        <li><strong>Daraja 4: Hashamatli (👑):</strong> 45-55% marja, premium xaridorlar</li>
                    </ul>
                    <p style="margin-top: 20px;"><strong>Standart tavsiya:</strong> 90% mijozlar uchun Daraja 2 (Qiymat)</p>
                </div>
            </div>

            <div class="cta-section">
                <h2>💰 Ushbu strategiyani joriy qilishga tayyormisiz?</h2>
                <div class="cta-buttons">
                    <a href="complete-dme-product-portfolio.html" class="cta-btn primary">
                        Mahsulot portfeli →
                    </a>
                    <a href="PRIMARY-LANDING-PAGE.html#all-strategies" class="cta-btn secondary">
                        Barcha strategiyalar →
                    </a>
                </div>
            </div>

            <div class="footer">
                <p><strong>Holistic Medical Supply</strong> | 4 darajali narx strategiyasi</p>
                <p>34 dan 4-hujjat | 25-oktabr 2025 | Versiya 1.0</p>
            </div>
        </div>
    </div>

    <script>
        function switchLanguage(lang) {
            document.querySelectorAll('.lang-content').forEach(content => {
                content.classList.remove('active');
            });
            document.querySelectorAll('.lang-btn').forEach(btn => {
                btn.classList.remove('active');
            });
            document.getElementById('content-' + lang).classList.add('active');
            document.querySelector('.lang-btn[data-lang="' + lang + '"]').classList.add('active');
            localStorage.setItem('preferredLanguage', lang);
        }

        window.addEventListener('DOMContentLoaded', function() {
            const savedLang = localStorage.getItem('preferredLanguage');
            if (savedLang && ['en', 'ru', 'uz'].includes(savedLang)) {
                switchLanguage(savedLang);
            }
        });
    </script>
</body>
</html>
