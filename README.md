<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Business Strategy Visual Mockups - DME Positioning Tiers</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            line-height: 1.6;
            color: #333;
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            padding: 20px;
        }

        .container {
            max-width: 1400px;
            margin: 0 auto;
            background: white;
            border-radius: 20px;
            box-shadow: 0 20px 60px rgba(0,0,0,0.3);
            overflow: hidden;
        }

        .header {
            background: linear-gradient(135deg, #1e3c72 0%, #2a5298 100%);
            color: white;
            padding: 60px 40px;
            text-align: center;
        }

        .header h1 {
            font-size: 3em;
            margin-bottom: 15px;
            text-shadow: 2px 2px 4px rgba(0,0,0,0.3);
        }

        .header p {
            font-size: 1.3em;
            opacity: 0.9;
        }

        .strategy-overview {
            padding: 40px;
            background: #f8f9fa;
            border-bottom: 4px solid #667eea;
        }

        .strategy-overview h2 {
            color: #1e3c72;
            margin-bottom: 20px;
            font-size: 2em;
        }

        .strategy-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 20px;
            margin-top: 30px;
        }

        .strategy-card-mini {
            background: white;
            padding: 25px;
            border-radius: 12px;
            box-shadow: 0 4px 15px rgba(0,0,0,0.1);
            border-left: 5px solid;
            transition: transform 0.3s ease;
        }

        .strategy-card-mini:hover {
            transform: translateY(-5px);
        }

        .economy { border-left-color: #28a745; }
        .value { border-left-color: #007bff; }
        .usmade { border-left-color: #dc3545; }
        .luxury { border-left-color: #ffc107; }

        .tier-section {
            padding: 60px 40px;
            border-bottom: 3px solid #e9ecef;
        }

        .tier-section:nth-child(even) {
            background: #f8f9fa;
        }

        .tier-header {
            text-align: center;
            margin-bottom: 50px;
        }

        .tier-badge {
            display: inline-block;
            padding: 12px 30px;
            border-radius: 50px;
            color: white;
            font-weight: bold;
            font-size: 1.1em;
            margin-bottom: 20px;
            text-transform: uppercase;
            letter-spacing: 1px;
        }

        .economy-badge { background: linear-gradient(135deg, #28a745, #20c997); }
        .value-badge { background: linear-gradient(135deg, #007bff, #0056b3); }
        .usmade-badge { background: linear-gradient(135deg, #dc3545, #c82333); }
        .luxury-badge { background: linear-gradient(135deg, #ffc107, #e0a800); }

        .tier-title {
            font-size: 2.5em;
            color: #1e3c72;
            margin-bottom: 15px;
        }

        .tier-subtitle {
            font-size: 1.2em;
            color: #6c757d;
        }

        .content-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(400px, 1fr));
            gap: 30px;
            margin-top: 40px;
        }

        .mockup-card {
            background: white;
            border-radius: 15px;
            padding: 30px;
            box-shadow: 0 5px 20px rgba(0,0,0,0.1);
            border: 2px solid #e9ecef;
        }

        .mockup-card h3 {
            color: #1e3c72;
            margin-bottom: 20px;
            font-size: 1.5em;
            border-bottom: 3px solid;
            padding-bottom: 10px;
        }

        .economy h3 { border-bottom-color: #28a745; }
        .value h3 { border-bottom-color: #007bff; }
        .usmade h3 { border-bottom-color: #dc3545; }
        .luxury h3 { border-bottom-color: #ffc107; }

        .visual-mockup {
            background: #f8f9fa;
            border-radius: 10px;
            padding: 30px;
            margin: 20px 0;
            border: 3px dashed #dee2e6;
            min-height: 250px;
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: center;
            text-align: center;
        }

        .product-showcase {
            background: linear-gradient(135deg, #667eea20, #764ba220);
            border-radius: 10px;
            padding: 25px;
            margin: 15px 0;
        }

        .product-item {
            background: white;
            padding: 20px;
            margin: 10px 0;
            border-radius: 8px;
            border-left: 4px solid;
            display: flex;
            align-items: center;
            gap: 15px;
        }

        .product-icon {
            width: 60px;
            height: 60px;
            border-radius: 50%;
            display: flex;
            align-items: center;
            justify-content: center;
            font-size: 1.8em;
            color: white;
            flex-shrink: 0;
        }

        .product-info h4 {
            margin-bottom: 5px;
            color: #1e3c72;
        }

        .product-info p {
            color: #6c757d;
            font-size: 0.9em;
        }

        .stats-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(120px, 1fr));
            gap: 15px;
            margin-top: 20px;
        }

        .stat-box {
            background: linear-gradient(135deg, #667eea, #764ba2);
            color: white;
            padding: 20px;
            border-radius: 10px;
            text-align: center;
        }

        .stat-number {
            font-size: 2em;
            font-weight: bold;
            display: block;
            margin-bottom: 5px;
        }

        .stat-label {
            font-size: 0.9em;
            opacity: 0.9;
        }

        .marketing-mockup {
            background: white;
            border-radius: 10px;
            padding: 30px;
            margin: 20px 0;
            box-shadow: 0 0 30px rgba(0,0,0,0.1);
        }

        .ad-mockup {
            border: 3px solid;
            border-radius: 12px;
            padding: 25px;
            margin: 15px 0;
            position: relative;
            overflow: hidden;
        }

        .ad-mockup::before {
            content: '';
            position: absolute;
            top: 0;
            left: 0;
            right: 0;
            height: 5px;
        }

        .customer-journey {
            background: #f8f9fa;
            border-radius: 10px;
            padding: 25px;
            margin: 20px 0;
        }

        .journey-step {
            background: white;
            padding: 20px;
            margin: 15px 0;
            border-radius: 8px;
            border-left: 5px solid;
            position: relative;
            padding-left: 50px;
        }

        .journey-step::before {
            content: attr(data-step);
            position: absolute;
            left: 15px;
            top: 50%;
            transform: translateY(-50%);
            width: 30px;
            height: 30px;
            border-radius: 50%;
            background: currentColor;
            color: white;
            display: flex;
            align-items: center;
            justify-content: center;
            font-weight: bold;
        }

        .pricing-mockup {
            background: linear-gradient(135deg, #667eea10, #764ba210);
            border-radius: 10px;
            padding: 30px;
            margin: 20px 0;
        }

        .price-card {
            background: white;
            border-radius: 10px;
            padding: 25px;
            margin: 10px 0;
            box-shadow: 0 3px 15px rgba(0,0,0,0.1);
            display: flex;
            justify-content: space-between;
            align-items: center;
        }

        .price-amount {
            font-size: 2.5em;
            font-weight: bold;
            color: #1e3c72;
        }

        .margin-indicator {
            padding: 8px 20px;
            border-radius: 50px;
            font-weight: bold;
            color: white;
        }

        .store-mockup {
            background: white;
            border-radius: 10px;
            padding: 30px;
            margin: 20px 0;
            border: 2px solid #dee2e6;
        }

        .shelf-display {
            background: #f8f9fa;
            border-radius: 8px;
            padding: 20px;
            margin: 10px 0;
            border: 2px solid #e9ecef;
        }

        .shelf-row {
            display: flex;
            gap: 10px;
            margin: 10px 0;
            flex-wrap: wrap;
        }

        .shelf-item {
            flex: 1;
            min-width: 80px;
            height: 100px;
            border-radius: 8px;
            display: flex;
            align-items: center;
            justify-content: center;
            font-size: 2em;
            color: white;
            box-shadow: 0 2px 10px rgba(0,0,0,0.1);
        }

        .comparison-table {
            width: 100%;
            margin: 20px 0;
            border-collapse: collapse;
            background: white;
            border-radius: 10px;
            overflow: hidden;
            box-shadow: 0 3px 15px rgba(0,0,0,0.1);
        }

        .comparison-table th {
            background: linear-gradient(135deg, #1e3c72, #2a5298);
            color: white;
            padding: 15px;
            text-align: left;
        }

        .comparison-table td {
            padding: 15px;
            border-bottom: 1px solid #e9ecef;
        }

        .comparison-table tr:hover {
            background: #f8f9fa;
        }

        .footer {
            background: #1e3c72;
            color: white;
            padding: 40px;
            text-align: center;
        }

        .footer h3 {
            margin-bottom: 15px;
            font-size: 1.8em;
        }

        @media (max-width: 768px) {
            .content-grid {
                grid-template-columns: 1fr;
            }
            
            .header h1 {
                font-size: 2em;
            }
            
            .tier-title {
                font-size: 1.8em;
            }
        }

        .icon-large {
            font-size: 4em;
            margin: 20px 0;
        }

        .highlight-box {
            background: linear-gradient(135deg, #667eea15, #764ba215);
            border-left: 5px solid #667eea;
            padding: 20px;
            margin: 15px 0;
            border-radius: 8px;
        }

        .tag {
            display: inline-block;
            padding: 5px 15px;
            border-radius: 20px;
            font-size: 0.85em;
            margin: 5px;
            font-weight: 600;
        }
    </style>
</head>
<body>
    <div class="container">
        <!-- Header -->
        <div class="header">
            <h1>🏥 Business Strategy Visual Mockups</h1>
            <p>Comprehensive DME Positioning Tier Strategies with Visual Representations</p>
        </div>

        <!-- Strategy Overview -->
        <div class="strategy-overview">
            <h2>📊 Strategic Positioning Overview</h2>
            <p style="font-size: 1.1em; margin-bottom: 20px;">Four distinct positioning tiers designed to capture different market segments and maximize market coverage while maintaining operational efficiency.</p>
            
            <div class="strategy-grid">
                <div class="strategy-card-mini economy">
                    <h3 style="color: #28a745; margin-bottom: 10px;">🟢 Economy Tier</h3>
                    <p><strong>5% of Inventory</strong></p>
                    <p style="margin-top: 10px;">Price-sensitive customers seeking affordable, functional solutions</p>
                </div>
                
                <div class="strategy-card-mini value">
                    <h3 style="color: #007bff; margin-bottom: 10px;">🔵 Value Tier</h3>
                    <p><strong>90% of Inventory</strong></p>
                    <p style="margin-top: 10px;">Core market seeking best balance of price and performance</p>
                </div>
                
                <div class="strategy-card-mini usmade">
                    <h3 style="color: #dc3545; margin-bottom: 10px;">🇺🇸 US-Made Tier</h3>
                    <p><strong>2-3% of Inventory</strong></p>
                    <p style="margin-top: 10px;">Patriotic customers prioritizing domestic manufacturing</p>
                </div>
                
                <div class="strategy-card-mini luxury">
                    <h3 style="color: #ffc107; margin-bottom: 10px;">💎 Luxury Tier</h3>
                    <p><strong>2-3% of Inventory</strong></p>
                    <p style="margin-top: 10px;">Affluent customers seeking premium features and latest technology</p>
                </div>
            </div>

            <!-- Quick Stats -->
            <div class="stats-grid" style="margin-top: 40px;">
                <div class="stat-box">
                    <span class="stat-number">4</span>
                    <span class="stat-label">Positioning Tiers</span>
                </div>
                <div class="stat-box">
                    <span class="stat-number">100%</span>
                    <span class="stat-label">Market Coverage</span>
                </div>
                <div class="stat-box">
                    <span class="stat-number">20-60%</span>
                    <span class="stat-label">Margin Range</span>
                </div>
                <div class="stat-box">
                    <span class="stat-number">∞</span>
                    <span class="stat-label">Growth Potential</span>
                </div>
            </div>
        </div>

        <!-- ECONOMY TIER -->
        <div class="tier-section economy">
            <div class="tier-header">
                <div class="tier-badge economy-badge">🟢 Economy Tier Strategy</div>
                <h2 class="tier-title">Economy Tier: Accessible Healthcare for All</h2>
                <p class="tier-subtitle">5% of Inventory | 20-30% Margins | Affordability Focus</p>
            </div>

            <div class="content-grid">
                <!-- Target Customer Profile -->
                <div class="mockup-card economy">
                    <h3>👥 Target Customer Profile</h3>
                    <div class="visual-mockup">
                        <div class="icon-large">🎯</div>
                        <h4 style="margin-bottom: 15px;">Primary Demographic</h4>
                        <div style="text-align: left; width: 100%;">
                            <p><strong>Income Level:</strong> Lower to lower-middle income</p>
                            <p><strong>Insurance:</strong> Medicaid, Medicare with limited supplemental</p>
                            <p><strong>Priority:</strong> Functional equipment at lowest cost</p>
                            <p><strong>Decision Factor:</strong> Price is primary concern</p>
                            <p><strong>Shopping Behavior:</strong> Compares prices extensively</p>
                        </div>
                    </div>
                    
                    <div class="highlight-box">
                        <strong>Key Insight:</strong> These customers need DME equipment but have limited financial resources. They value reliability over features and prioritize immediate affordability over long-term cost of ownership.
                    </div>
                </div>

                <!-- Product Examples -->
                <div class="mockup-card economy">
                    <h3>🛒 Product Showcase Examples</h3>
                    <div class="product-showcase">
                        <div class="product-item" style="border-left-color: #28a745;">
                            <div class="product-icon" style="background: #28a745;">♿</div>
                            <div class="product-info">
                                <h4>Basic Manual Wheelchair</h4>
                                <p>Standard steel frame, fixed armrests, basic footrests</p>
                                <p style="color: #28a745; font-weight: bold;">$150-$250</p>
                            </div>
                        </div>
                        
                        <div class="product-item" style="border-left-color: #28a745;">
                            <div class="product-icon" style="background: #28a745;">🚶</div>
                            <div class="product-info">
                                <h4>Standard Walker</h4>
                                <p>Aluminum frame, no wheels, basic rubber tips</p>
                                <p style="color: #28a745; font-weight: bold;">$35-$60</p>
                            </div>
                        </div>
                        
                        <div class="product-item" style="border-left-color: #28a745;">
                            <div class="product-icon" style="background: #28a745;">😴</div>
                            <div class="product-info">
                                <h4>Entry-Level CPAP Machine</h4>
                                <p>Basic pressure settings, standard mask, minimal features</p>
                                <p style="color: #28a745; font-weight: bold;">$400-$600</p>
                            </div>
                        </div>

                        <div class="product-item" style="border-left-color: #28a745;">
                            <div class="product-icon" style="background: #28a745;">🩹</div>
                            <div class="product-info">
                                <h4>Basic Medical Supplies</h4>
                                <p>Generic bandages, basic wound care, disposables</p>
                                <p style="color: #28a745; font-weight: bold;">$5-$25</p>
                            </div>
                        </div>
                    </div>
                </div>

                <!-- Marketing Approach -->
                <div class="mockup-card economy">
                    <h3>📢 Marketing & Messaging Mockup</h3>
                    <div class="marketing-mockup">
                        <div class="ad-mockup" style="border-color: #28a745; background: linear-gradient(135deg, #28a74510, #20c99710);">
                            <h4 style="color: #28a745; font-size: 1.8em; margin-bottom: 15px;">💚 Quality Healthcare, Affordable Prices</h4>
                            <p style="font-size: 1.2em; margin-bottom: 20px;"><strong>"Essential Medical Equipment That Fits Your Budget"</strong></p>
                            <ul style="text-align: left; margin-left: 20px;">
                                <li>✓ Lowest prices guaranteed</li>
                                <li>✓ Insurance accepted</li>
                                <li>✓ Flexible payment plans available</li>
                                <li>✓ No hidden fees</li>
                                <li>✓ Same reliable quality at better prices</li>
                            </ul>
                            <div style="background: #28a745; color: white; padding: 15px; margin-top: 20px; border-radius: 8px; text-align: center; font-size: 1.3em; font-weight: bold;">
                                SAVE UP TO 40% ON ESSENTIAL DME
                            </div>
                        </div>
                        
                        <div style="margin-top: 20px;">
                            <strong>Marketing Channels:</strong>
                            <div class="tag" style="background: #28a745; color: white;">Community Centers</div>
                            <div class="tag" style="background: #28a745; color: white;">Senior Services</div>
                            <div class="tag" style="background: #28a745; color: white;">Medicaid Networks</div>
                            <div class="tag" style="background: #28a745; color: white;">Local Newspapers</div>
                            <div class="tag" style="background: #28a745; color: white;">Price Comparison Sites</div>
                        </div>
                    </div>
                </div>

                <!-- Store Display Mockup -->
                <div class="mockup-card economy">
                    <h3>🏪 Store Display Strategy</h3>
                    <div class="store-mockup">
                        <h4 style="margin-bottom: 15px;">Physical & Online Presence</h4>
                        <div class="shelf-display">
                            <p style="margin-bottom: 10px;"><strong>💚 Economy Section</strong> - Prominent signage with clear pricing</p>
                            <div class="shelf-row">
                                <div class="shelf-item" style="background: linear-gradient(135deg, #28a745, #20c997);">♿</div>
                                <div class="shelf-item" style="background: linear-gradient(135deg, #28a745, #20c997);">🚶</div>
                                <div class="shelf-item" style="background: linear-gradient(135deg, #28a745, #20c997);">🦽</div>
                                <div class="shelf-item" style="background: linear-gradient(135deg, #28a745, #20c997);">🩺</div>
                            </div>
                        </div>
                        
                        <div class="highlight-box">
                            <p><strong>Display Strategy:</strong></p>
                            <ul style="margin-left: 20px; margin-top: 10px;">
                                <li>Large price tags prominently displayed</li>
                                <li>Clear comparison charts with competitors</li>
                                <li>Financing information readily available</li>
                                <li>Grouped together in dedicated "Value Zone"</li>
                                <li>Simple, straightforward signage</li>
                            </ul>
                        </div>
                    </div>
                </div>

                <!-- Customer Journey -->
                <div class="mockup-card economy">
                    <h3>🗺️ Customer Journey Mockup</h3>
                    <div class="customer-journey">
                        <div class="journey-step" style="border-left-color: #28a745; color: #28a745;" data-step="1">
                            <h4>Discovery</h4>
                            <p>Customer searches online for "affordable wheelchair" or sees community flyer</p>
                        </div>
                        
                        <div class="journey-step" style="border-left-color: #28a745; color: #28a745;" data-step="2">
                            <h4>Price Comparison</h4>
                            <p>Compares prices across 3-5 suppliers, reads reviews focused on value</p>
                        </div>
                        
                        <div class="journey-step" style="border-left-color: #28a745; color: #28a745;" data-step="3">
                            <h4>Insurance Verification</h4>
                            <p>Calls to confirm insurance acceptance and out-of-pocket costs</p>
                        </div>
                        
                        <div class="journey-step" style="border-left-color: #28a745; color: #28a745;" data-step="4">
                            <h4>Purchase Decision</h4>
                            <p>Chooses based primarily on lowest price with acceptable quality</p>
                        </div>
                        
                        <div class="journey-step" style="border-left-color: #28a745; color: #28a745;" data-step="5">
                            <h4>Post-Purchase</h4>
                            <p>Satisfied if product works as expected; becomes loyal if savings realized</p>
                        </div>
                    </div>
                </div>

                <!-- Pricing Strategy -->
                <div class="mockup-card economy">
                    <h3>💰 Pricing Strategy Mockup</h3>
                    <div class="pricing-mockup">
                        <div class="price-card">
                            <div>
                                <h4>Basic Manual Wheelchair</h4>
                                <p style="color: #6c757d;">Entry-level mobility solution</p>
                            </div>
                            <div style="text-align: right;">
                                <div class="price-amount" style="color: #28a745;">$199</div>
                                <div class="margin-indicator" style="background: #28a745;">25% Margin</div>
                            </div>
                        </div>
                        
                        <div class="price-card">
                            <div>
                                <h4>Standard Walker</h4>
                                <p style="color: #6c757d;">Aluminum frame with rubber tips</p>
                            </div>
                            <div style="text-align: right;">
                                <div class="price-amount" style="color: #28a745;">$49</div>
                                <div class="margin-indicator" style="background: #28a745;">22% Margin</div>
                            </div>
                        </div>
                        
                        <div class="price-card">
                            <div>
                                <h4>Entry CPAP Package</h4>
                                <p style="color: #6c757d;">Machine + standard mask + supplies</p>
                            </div>
                            <div style="text-align: right;">
                                <div class="price-amount" style="color: #28a745;">$499</div>
                                <div class="margin-indicator" style="background: #28a745;">28% Margin</div>
                            </div>
                        </div>
                    </div>
                    
                    <div class="highlight-box">
                        <strong>Pricing Philosophy:</strong> Aggressive cost control while maintaining acceptable quality. Bulk purchasing, efficient operations, and lower service overhead enable competitive pricing. Payment plans and insurance processing streamlined for efficiency.
                    </div>
                </div>
            </div>
        </div>

        <!-- VALUE TIER -->
        <div class="tier-section value">
            <div class="tier-header">
                <div class="tier-badge value-badge">🔵 Value Tier Strategy</div>
                <h2 class="tier-title">Value Tier: The Smart Choice</h2>
                <p class="tier-subtitle">90% of Inventory | 30-40% Margins | Best Price-Performance Ratio</p>
            </div>

            <div class="content-grid">
                <!-- Target Customer Profile -->
                <div class="mockup-card value">
                    <h3>👥 Target Customer Profile</h3>
                    <div class="visual-mockup">
                        <div class="icon-large">🎯</div>
                        <h4 style="margin-bottom: 15px;">Primary Demographic</h4>
                        <div style="text-align: left; width: 100%;">
                            <p><strong>Income Level:</strong> Middle income, financially stable</p>
                            <p><strong>Insurance:</strong> Good coverage with reasonable co-pays</p>
                            <p><strong>Priority:</strong> Quality equipment at fair prices</p>
                            <p><strong>Decision Factor:</strong> Best value for money</p>
                            <p><strong>Shopping Behavior:</strong> Researches features and reviews</p>
                        </div>
                    </div>
                    
                    <div class="highlight-box">
                        <strong>Key Insight:</strong> These customers represent the majority of the market. They're willing to pay more than economy tier for better features and quality, but won't splurge on premium. They're educated consumers who research thoroughly and value both quality and price.
                    </div>
                </div>

                <!-- Product Examples -->
                <div class="mockup-card value">
                    <h3>🛒 Product Showcase Examples</h3>
                    <div class="product-showcase">
                        <div class="product-item" style="border-left-color: #007bff;">
                            <div class="product-icon" style="background: #007bff;">♿</div>
                            <div class="product-info">
                                <h4>Mid-Range Power Wheelchair</h4>
                                <p>Adjustable seat, good battery life, smooth controls, comfortable ride</p>
                                <p style="color: #007bff; font-weight: bold;">$2,500-$4,500</p>
                            </div>
                        </div>
                        
                        <div class="product-item" style="border-left-color: #007bff;">
                            <div class="product-icon" style="background: #007bff;">💨</div>
                            <div class="product-info">
                                <h4>Feature-Rich Oxygen Concentrator</h4>
                                <p>Quiet operation, portable, multiple flow settings, user-friendly</p>
                                <p style="color: #007bff; font-weight: bold;">$1,800-$2,800</p>
                            </div>
                        </div>
                        
                        <div class="product-item" style="border-left-color: #007bff;">
                            <div class="product-icon" style="background: #007bff;">🛏️</div>
                            <div class="product-info">
                                <h4>Adjustable Hospital Bed</h4>
                                <p>Electric controls, multiple positions, side rails, comfortable mattress</p>
                                <p style="color: #007bff; font-weight: bold;">$1,200-$2,000</p>
                            </div>
                        </div>

                        <div class="product-item" style="border-left-color: #007bff;">
                            <div class="product-icon" style="background: #007bff;">🚶</div>
                            <div class="product-info">
                                <h4>Rollator with Features</h4>
                                <p>Built-in seat, basket, locking brakes, adjustable height, lightweight</p>
                                <p style="color: #007bff; font-weight: bold;">$150-$300</p>
                            </div>
                        </div>
                    </div>
                </div>

                <!-- Marketing Approach -->
                <div class="mockup-card value">
                    <h3>📢 Marketing & Messaging Mockup</h3>
                    <div class="marketing-mockup">
                        <div class="ad-mockup" style="border-color: #007bff; background: linear-gradient(135deg, #007bff10, #0056b310);">
                            <h4 style="color: #007bff; font-size: 1.8em; margin-bottom: 15px;">💙 Smart Healthcare Decisions Start Here</h4>
                            <p style="font-size: 1.2em; margin-bottom: 20px;"><strong>"Quality Equipment at Prices That Make Sense"</strong></p>
                            <ul style="text-align: left; margin-left: 20px;">
                                <li>✓ Proven reliability and performance</li>
                                <li>✓ Features you'll actually use</li>
                                <li>✓ Comprehensive warranty coverage</li>
                                <li>✓ Expert guidance and support</li>
                                <li>✓ Best value in the market</li>
                            </ul>
                            <div style="background: #007bff; color: white; padding: 15px; margin-top: 20px; border-radius: 8px; text-align: center; font-size: 1.3em; font-weight: bold;">
                                THE SMART CHOICE FOR MOST CUSTOMERS
                            </div>
                        </div>
                        
                        <div style="margin-top: 20px;">
                            <strong>Marketing Channels:</strong>
                            <div class="tag" style="background: #007bff; color: white;">Google Ads</div>
                            <div class="tag" style="background: #007bff; color: white;">Healthcare Providers</div>
                            <div class="tag" style="background: #007bff; color: white;">Social Media</div>
                            <div class="tag" style="background: #007bff; color: white;">Email Marketing</div>
                            <div class="tag" style="background: #007bff; color: white;">Review Sites</div>
                            <div class="tag" style="background: #007bff; color: white;">Local Events</div>
                        </div>
                    </div>
                </div>

                <!-- Store Display Mockup -->
                <div class="mockup-card value">
                    <h3>🏪 Store Display Strategy</h3>
                    <div class="store-mockup">
                        <h4 style="margin-bottom: 15px;">Prime Real Estate Positioning</h4>
                        <div class="shelf-display">
                            <p style="margin-bottom: 10px;"><strong>💙 Value Section</strong> - Central location with excellent visibility</p>
                            <div class="shelf-row">
                                <div class="shelf-item" style="background: linear-gradient(135deg, #007bff, #0056b3);">♿</div>
                                <div class="shelf-item" style="background: linear-gradient(135deg, #007bff, #0056b3);">💨</div>
                                <div class="shelf-item" style="background: linear-gradient(135deg, #007bff, #0056b3);">🛏️</div>
                                <div class="shelf-item" style="background: linear-gradient(135deg, #007bff, #0056b3);">🚶</div>
                            </div>
                            <div class="shelf-row">
                                <div class="shelf-item" style="background: linear-gradient(135deg, #007bff, #0056b3);">🦽</div>
                                <div class="shelf-item" style="background: linear-gradient(135deg, #007bff, #0056b3);">😴</div>
                                <div class="shelf-item" style="background: linear-gradient(135deg, #007bff, #0056b3);">🩺</div>
                                <div class="shelf-item" style="background: linear-gradient(135deg, #007bff, #0056b3);">💊</div>
                            </div>
                        </div>
                        
                        <div class="highlight-box">
                            <p><strong>Display Strategy:</strong></p>
                            <ul style="margin-left: 20px; margin-top: 10px;">
                                <li>Featured prominently throughout store</li>
                                <li>Hands-on demonstration areas</li>
                                <li>Feature comparison displays</li>
                                <li>Customer testimonials visible</li>
                                <li>Staff trained to highlight value proposition</li>
                                <li>Professional, clean presentation</li>
                            </ul>
                        </div>
                    </div>
                </div>

                <!-- Customer Journey -->
                <div class="mockup-card value">
                    <h3>🗺️ Customer Journey Mockup</h3>
                    <div class="customer-journey">
                        <div class="journey-step" style="border-left-color: #007bff; color: #007bff;" data-step="1">
                            <h4>Research Phase</h4>
                            <p>Extensive online research, reads multiple reviews, consults with healthcare provider</p>
                        </div>
                        
                        <div class="journey-step" style="border-left-color: #007bff; color: #007bff;" data-step="2">
                            <h4>Feature Comparison</h4>
                            <p>Creates spreadsheet comparing features, prices, and warranty across options</p>
                        </div>
                        
                        <div class="journey-step" style="border-left-color: #007bff; color: #007bff;" data-step="3">
                            <h4>Store Visit</h4>
                            <p>Visits store to test equipment, asks detailed questions, discusses insurance</p>
                        </div>
                        
                        <div class="journey-step" style="border-left-color: #007bff; color: #007bff;" data-step="4">
                            <h4>Decision Making</h4>
                            <p>Balances features, price, and quality; chooses best overall value</p>
                        </div>
                        
                        <div class="journey-step" style="border-left-color: #007bff; color: #007bff;" data-step="5">
                            <h4>Long-term Relationship</h4>
                            <p>Satisfied with purchase; leaves reviews, refers friends, returns for future needs</p>
                        </div>
                    </div>
                </div>

                <!-- Pricing Strategy -->
                <div class="mockup-card value">
                    <h3>💰 Pricing Strategy Mockup</h3>
                    <div class="pricing-mockup">
                        <div class="price-card">
                            <div>
                                <h4>Mid-Range Power Wheelchair</h4>
                                <p style="color: #6c757d;">Comfort & functionality balanced</p>
                            </div>
                            <div style="text-align: right;">
                                <div class="price-amount" style="color: #007bff;">$3,499</div>
                                <div class="margin-indicator" style="background: #007bff;">35% Margin</div>
                            </div>
                        </div>
                        
                        <div class="price-card">
                            <div>
                                <h4>Feature-Rich Oxygen Concentrator</h4>
                                <p style="color: #6c757d;">Quiet, efficient, user-friendly</p>
                            </div>
                            <div style="text-align: right;">
                                <div class="price-amount" style="color: #007bff;">$2,299</div>
                                <div class="margin-indicator" style="background: #007bff;">33% Margin</div>
                            </div>
                        </div>
                        
                        <div class="price-card">
                            <div>
                                <h4>Adjustable Hospital Bed</h4>
                                <p style="color: #6c757d;">Electric controls & comfort features</p>
                            </div>
                            <div style="text-align: right;">
                                <div class="price-amount" style="color: #007bff;">$1,699</div>
                                <div class="margin-indicator" style="background: #007bff;">37% Margin</div>
                            </div>
                        </div>
                    </div>
                    
                    <div class="highlight-box">
                        <strong>Pricing Philosophy:</strong> Competitive pricing on quality equipment with proven reliability. Strategic supplier relationships enable strong margins while maintaining attractive price points. Focus on total cost of ownership, not just initial price.
                    </div>
                </div>
            </div>
        </div>

        <!-- US-MADE TIER -->
        <div class="tier-section usmade">
            <div class="tier-header">
                <div class="tier-badge usmade-badge">🇺🇸 US-Made Tier Strategy</div>
                <h2 class="tier-title">US-Made Tier: Proudly American</h2>
                <p class="tier-subtitle">2-3% of Inventory | 35-50% Margins | Patriotic & Quality-Focused</p>
            </div>

            <div class="content-grid">
                <!-- Target Customer Profile -->
                <div class="mockup-card usmade">
                    <h3>👥 Target Customer Profile</h3>
                    <div class="visual-mockup">
                        <div class="icon-large">🎯</div>
                        <h4 style="margin-bottom: 15px;">Primary Demographic</h4>
                        <div style="text-align: left; width: 100%;">
                            <p><strong>Income Level:</strong> Middle to upper-middle income</p>
                            <p><strong>Values:</strong> Patriotism, supporting American jobs</p>
                            <p><strong>Priority:</strong> Domestic manufacturing first</p>
                            <p><strong>Decision Factor:</strong> Country of origin matters most</p>
                            <p><strong>Shopping Behavior:</strong> Actively seeks "Made in USA"</p>
                        </div>
                    </div>
                    
                    <div class="highlight-box">
                        <strong>Key Insight:</strong> These customers are willing to pay a premium for products made in America. They value supporting domestic jobs, local economies, and American craftsmanship. They believe US-made products are higher quality and more reliable.
                    </div>
                </div>

                <!-- Product Examples -->
                <div class="mockup-card usmade">
                    <h3>🛒 Product Showcase Examples</h3>
                    <div class="product-showcase">
                        <div class="product-item" style="border-left-color: #dc3545;">
                            <div class="product-icon" style="background: #dc3545;">♿</div>
                            <div class="product-info">
                                <h4>TiLite Custom Wheelchair 🇺🇸</h4>
                                <p>Manufactured in Pasco, Washington • Aerospace-grade titanium • Custom fit</p>
                                <p style="color: #dc3545; font-weight: bold;">$4,500-$8,000</p>
                            </div>
                        </div>
                        
                        <div class="product-item" style="border-left-color: #dc3545;">
                            <div class="product-icon" style="background: #dc3545;">🛏️</div>
                            <div class="product-info">
                                <h4>Sunrise Medical Equipment 🇺🇸</h4>
                                <p>Made in Colorado • Premium materials • American craftsmanship</p>
                                <p style="color: #dc3545; font-weight: bold;">$2,000-$4,500</p>
                            </div>
                        </div>
                        
                        <div class="product-item" style="border-left-color: #dc3545;">
                            <div class="product-icon" style="background: #dc3545;">🚶</div>
                            <div class="product-info">
                                <h4>Drive Medical USA Line 🇺🇸</h4>
                                <p>Assembled in America • Quality components • Local support</p>
                                <p style="color: #dc3545; font-weight: bold;">$300-$800</p>
                            </div>
                        </div>

                        <div class="product-item" style="border-left-color: #dc3545;">
                            <div class="product-icon" style="background: #dc3545;">🩺</div>
                            <div class="product-info">
                                <h4>American-Made Medical Supplies 🇺🇸</h4>
                                <p>Sourced and produced domestically • Quality assured • Supporting US jobs</p>
                                <p style="color: #dc3545; font-weight: bold;">$50-$500</p>
                            </div>
                        </div>
                    </div>
                </div>

                <!-- Marketing Approach -->
                <div class="mockup-card usmade">
                    <h3>📢 Marketing & Messaging Mockup</h3>
                    <div class="marketing-mockup">
                        <div class="ad-mockup" style="border-color: #dc3545; background: linear-gradient(135deg, #dc354510, #c8233310);">
                            <h4 style="color: #dc3545; font-size: 2em; margin-bottom: 15px;">🇺🇸 MADE IN AMERICA, BUILT FOR AMERICANS</h4>
                            <p style="font-size: 1.3em; margin-bottom: 20px;"><strong>"Supporting American Jobs While Getting Superior Quality"</strong></p>
                            <ul style="text-align: left; margin-left: 20px; font-size: 1.1em;">
                                <li>✓ 100% American manufacturing</li>
                                <li>✓ Supporting local communities and jobs</li>
                                <li>✓ Superior quality and craftsmanship</li>
                                <li>✓ Stricter safety and quality standards</li>
                                <li>✓ Better customer service and support</li>
                                <li>✓ Proudly displaying "Made in USA"</li>
                            </ul>
                            <div style="background: linear-gradient(135deg, #dc3545, #c82333); color: white; padding: 20px; margin-top: 20px; border-radius: 8px; text-align: center; font-size: 1.4em; font-weight: bold;">
                                🇺🇸 CHOOSE AMERICAN. CHOOSE QUALITY. 🇺🇸
                            </div>
                        </div>
                        
                        <div style="margin-top: 20px;">
                            <strong>Marketing Channels:</strong>
                            <div class="tag" style="background: #dc3545; color: white;">Veterans Organizations</div>
                            <div class="tag" style="background: #dc3545; color: white;">Patriotic Groups</div>
                            <div class="tag" style="background: #dc3545; color: white;">Local Chamber</div>
                            <div class="tag" style="background: #dc3545; color: white;">Made in USA Directories</div>
                            <div class="tag" style="background: #dc3545; color: white;">Conservative Media</div>
                        </div>
                    </div>
                </div>

                <!-- Store Display Mockup -->
                <div class="mockup-card usmade">
                    <h3>🏪 Store Display Strategy</h3>
                    <div class="store-mockup">
                        <h4 style="margin-bottom: 15px;">Patriotic Presentation</h4>
                        <div class="shelf-display" style="background: linear-gradient(135deg, #f8f9fa, #e3f2fd);">
                            <p style="margin-bottom: 10px;"><strong>🇺🇸 MADE IN AMERICA SECTION</strong> - Prominent American flag displays</p>
                            <div class="shelf-row">
                                <div class="shelf-item" style="background: linear-gradient(135deg, #dc3545, #c82333);">🇺🇸</div>
                                <div class="shelf-item" style="background: linear-gradient(135deg, #dc3545, #c82333);">♿</div>
                                <div class="shelf-item" style="background: linear-gradient(135deg, #dc3545, #c82333);">🛏️</div>
                                <div class="shelf-item" style="background: linear-gradient(135deg, #dc3545, #c82333);">🚶</div>
                            </div>
                        </div>
                        
                        <div class="highlight-box">
                            <p><strong>Display Strategy:</strong></p>
                            <ul style="margin-left: 20px; margin-top: 10px;">
                                <li>Dedicated "Made in USA" section with American flag imagery</li>
                                <li>Prominent manufacturing location labels</li>
                                <li>Stories about American workers and craftsmanship</li>
                                <li>Certificates of origin displayed</li>
                                <li>Comparison highlighting American quality advantages</li>
                                <li>Red, white, and blue color scheme in signage</li>
                            </ul>
                        </div>
                    </div>
                </div>

                <!-- Customer Journey -->
                <div class="mockup-card usmade">
                    <h3>🗺️ Customer Journey Mockup</h3>
                    <div class="customer-journey">
                        <div class="journey-step" style="border-left-color: #dc3545; color: #dc3545;" data-step="1">
                            <h4>Value-Driven Search</h4>
                            <p>Specifically searches for "American-made wheelchair" or "USA manufactured DME"</p>
                        </div>
                        
                        <div class="journey-step" style="border-left-color: #dc3545; color: #dc3545;" data-step="2">
                            <h4>Origin Verification</h4>
                            <p>Researches company background, manufacturing locations, certifications</p>
                        </div>
                        
                        <div class="journey-step" style="border-left-color: #dc3545; color: #dc3545;" data-step="3">
                            <h4>Store Visit</h4>
                            <p>Asks about manufacturing location, interested in company's American story</p>
                        </div>
                        
                        <div class="journey-step" style="border-left-color: #dc3545; color: #dc3545;" data-step="4">
                            <h4>Proud Purchase</h4>
                            <p>Pays premium gladly, feels good about supporting American workers</p>
                        </div>
                        
                        <div class="journey-step" style="border-left-color: #dc3545; color: #dc3545;" data-step="5">
                            <h4>Brand Ambassador</h4>
                            <p>Tells others about buying American, displays products proudly, strong loyalty</p>
                        </div>
                    </div>
                </div>

                <!-- Pricing Strategy -->
                <div class="mockup-card usmade">
                    <h3>💰 Pricing Strategy Mockup</h3>
                    <div class="pricing-mockup">
                        <div class="price-card">
                            <div>
                                <h4>TiLite Custom Wheelchair 🇺🇸</h4>
                                <p style="color: #6c757d;">Made in Pasco, Washington</p>
                            </div>
                            <div style="text-align: right;">
                                <div class="price-amount" style="color: #dc3545;">$6,499</div>
                                <div class="margin-indicator" style="background: #dc3545;">42% Margin</div>
                            </div>
                        </div>
                        
                        <div class="price-card">
                            <div>
                                <h4>Sunrise Medical Hospital Bed 🇺🇸</h4>
                                <p style="color: #6c757d;">Colorado manufacturing</p>
                            </div>
                            <div style="text-align: right;">
                                <div class="price-amount" style="color: #dc3545;">$3,299</div>
                                <div class="margin-indicator" style="background: #dc3545;">38% Margin</div>
                            </div>
                        </div>
                        
                        <div class="price-card">
                            <div>
                                <h4>Drive Medical USA Line 🇺🇸</h4>
                                <p style="color: #6c757d;">Assembled in America</p>
                            </div>
                            <div style="text-align: right;">
                                <div class="price-amount" style="color: #dc3545;">$549</div>
                                <div class="margin-indicator" style="background: #dc3545;">45% Margin</div>
                            </div>
                        </div>
                    </div>
                    
                    <div class="highlight-box">
                        <strong>Pricing Philosophy:</strong> Premium pricing justified by American manufacturing, higher quality standards, and supporting domestic economy. Customers willingly pay 20-40% more knowing their purchase supports American workers and communities.
                    </div>
                </div>
            </div>
        </div>

        <!-- LUXURY/PREMIUM TIER -->
        <div class="tier-section luxury">
            <div class="tier-header">
                <div class="tier-badge luxury-badge">💎 Luxury/Premium Tier Strategy</div>
                <h2 class="tier-title">Luxury/Premium Tier: The Ultimate Experience</h2>
                <p class="tier-subtitle">2-3% of Inventory | 40-60% Margins | Cutting-Edge Technology & Premium Features</p>
            </div>

            <div class="content-grid">
                <!-- Target Customer Profile -->
                <div class="mockup-card luxury">
                    <h3>👥 Target Customer Profile</h3>
                    <div class="visual-mockup">
                        <div class="icon-large">🎯</div>
                        <h4 style="margin-bottom: 15px;">Primary Demographic</h4>
                        <div style="text-align: left; width: 100%;">
                            <p><strong>Income Level:</strong> High income, affluent</p>
                            <p><strong>Expectation:</strong> The absolute best available</p>
                            <p><strong>Priority:</strong> Latest technology and premium features</p>
                            <p><strong>Decision Factor:</strong> Quality and prestige over price</p>
                            <p><strong>Shopping Behavior:</strong> Seeks exclusivity and innovation</p>
                        </div>
                    </div>
                    
                    <div class="highlight-box">
                        <strong>Key Insight:</strong> These customers demand the best and are willing to pay for it. They want cutting-edge technology, superior comfort, exclusive features, and the prestige of owning top-tier equipment. Price is secondary to performance and status.
                    </div>
                </div>

                <!-- Product Examples -->
                <div class="mockup-card luxury">
                    <h3>🛒 Product Showcase Examples</h3>
                    <div class="product-showcase">
                        <div class="product-item" style="border-left-color: #ffc107;">
                            <div class="product-icon" style="background: linear-gradient(135deg, #ffc107, #ff9800);">♿</div>
                            <div class="product-info">
                                <h4>Pride Jazzy Air 2 💎</h4>
                                <p>Elevating power chair • Standing capability • Advanced suspension • App control</p>
                                <p style="color: #ffc107; font-weight: bold;">$25,000-$35,000</p>
                            </div>
                        </div>
                        
                        <div class="product-item" style="border-left-color: #ffc107;">
                            <div class="product-icon" style="background: linear-gradient(135deg, #ffc107, #ff9800);">💨</div>
                            <div class="product-info">
                                <h4>Inogen G5 Premium Package 💎</h4>
                                <p>Ultra-portable • Intelligent technology • Whisper-quiet • Premium accessories</p>
                                <p style="color: #ffc107; font-weight: bold;">$3,500-$4,500</p>
                            </div>
                        </div>
                        
                        <div class="product-item" style="border-left-color: #ffc107;">
                            <div class="product-icon" style="background: linear-gradient(135deg, #ffc107, #ff9800);">🛏️</div>
                            <div class="product-info">
                                <h4>Stryker InTouch Hospital Bed 💎</h4>
                                <p>Full electric • Therapeutic mattress • Premium controls • Hospital-grade</p>
                                <p style="color: #ffc107; font-weight: bold;">$8,000-$15,000</p>
                            </div>
                        </div>

                        <div class="product-item" style="border-left-color: #ffc107;">
                            <div class="product-icon" style="background: linear-gradient(135deg, #ffc107, #ff9800);">😴</div>
                            <div class="product-info">
                                <h4>ResMed AirSense 11 AutoSet 💎</h4>
                                <p>AI-powered • Cloud connectivity • Premium humidifier • Personalized therapy</p>
                                <p style="color: #ffc107; font-weight: bold;">$1,800-$2,500</p>
                            </div>
                        </div>
                    </div>
                </div>

                <!-- Marketing Approach -->
                <div class="mockup-card luxury">
                    <h3>📢 Marketing & Messaging Mockup</h3>
                    <div class="marketing-mockup">
                        <div class="ad-mockup" style="border-color: #ffc107; background: linear-gradient(135deg, #ffc10710, #e0a80010);">
                            <h4 style="color: #ffc107; font-size: 2.2em; margin-bottom: 15px;">💎 EXCELLENCE WITHOUT COMPROMISE</h4>
                            <p style="font-size: 1.4em; margin-bottom: 25px;"><strong>"Where Innovation Meets Luxury in Medical Equipment"</strong></p>
                            <ul style="text-align: left; margin-left: 20px; font-size: 1.1em;">
                                <li>✓ Cutting-edge technology and innovation</li>
                                <li>✓ Superior comfort and premium materials</li>
                                <li>✓ Exclusive features unavailable elsewhere</li>
                                <li>✓ White-glove service and support</li>
                                <li>✓ Extended warranties and VIP treatment</li>
                                <li>✓ Status and prestige of premium brands</li>
                            </ul>
                            <div style="background: linear-gradient(135deg, #ffc107, #e0a800); color: white; padding: 25px; margin-top: 25px; border-radius: 8px; text-align: center; font-size: 1.5em; font-weight: bold;">
                                EXPERIENCE THE PINNACLE OF MEDICAL EQUIPMENT
                            </div>
                        </div>
                        
                        <div style="margin-top: 20px;">
                            <strong>Marketing Channels:</strong>
                            <div class="tag" style="background: linear-gradient(135deg, #ffc107, #e0a800); color: white;">Luxury Magazines</div>
                            <div class="tag" style="background: linear-gradient(135deg, #ffc107, #e0a800); color: white;">Private Healthcare</div>
                            <div class="tag" style="background: linear-gradient(135deg, #ffc107, #e0a800); color: white;">Concierge Services</div>
                            <div class="tag" style="background: linear-gradient(135deg, #ffc107, #e0a800); color: white;">Exclusive Events</div>
                            <div class="tag" style="background: linear-gradient(135deg, #ffc107, #e0a800); color: white;">Premium Referrals</div>
                        </div>
                    </div>
                </div>

                <!-- Store Display Mockup -->
                <div class="mockup-card luxury">
                    <h3>🏪 Store Display Strategy</h3>
                    <div class="store-mockup">
                        <h4 style="margin-bottom: 15px;">Premium Showroom Experience</h4>
                        <div class="shelf-display" style="background: linear-gradient(135deg, #ffc10720, #e0a80020); border: 3px solid #ffc107;">
                            <p style="margin-bottom: 10px;"><strong>💎 LUXURY COLLECTION</strong> - Exclusive boutique-style display</p>
                            <div class="shelf-row">
                                <div class="shelf-item" style="background: linear-gradient(135deg, #ffc107, #e0a800); font-size: 2.5em; box-shadow: 0 5px 20px rgba(255, 193, 7, 0.4);">👑</div>
                                <div class="shelf-item" style="background: linear-gradient(135deg, #ffc107, #e0a800); font-size: 2.5em; box-shadow: 0 5px 20px rgba(255, 193, 7, 0.4);">💎</div>
                                <div class="shelf-item" style="background: linear-gradient(135deg, #ffc107, #e0a800); font-size: 2.5em; box-shadow: 0 5px 20px rgba(255, 193, 7, 0.4);">✨</div>
                                <div class="shelf-item" style="background: linear-gradient(135deg, #ffc107, #e0a800); font-size: 2.5em; box-shadow: 0 5px 20px rgba(255, 193, 7, 0.4);">🏆</div>
                            </div>
                        </div>
                        
                        <div class="highlight-box">
                            <p><strong>Display Strategy:</strong></p>
                            <ul style="margin-left: 20px; margin-top: 10px;">
                                <li>Separate, boutique-style premium showroom area</li>
                                <li>Elegant lighting and sophisticated décor</li>
                                <li>Private consultation rooms available</li>
                                <li>Personalized demonstration experiences</li>
                                <li>Premium brand certifications prominently displayed</li>
                                <li>Exclusive membership program materials</li>
                                <li>Refreshments and comfortable seating</li>
                            </ul>
                        </div>
                    </div>
                </div>

                <!-- Customer Journey -->
                <div class="mockup-card luxury">
                    <h3>🗺️ Customer Journey Mockup</h3>
                    <div class="customer-journey">
                        <div class="journey-step" style="border-left-color: #ffc107; color: #ffc107;" data-step="1">
                            <h4>Referral or Discovery</h4>
                            <p>Referred by physician or concierge, or finds through premium healthcare channels</p>
                        </div>
                        
                        <div class="journey-step" style="border-left-color: #ffc107; color: #ffc107;" data-step="2">
                            <h4>Private Consultation</h4>
                            <p>Schedules exclusive appointment, expects VIP treatment and expert guidance</p>
                        </div>
                        
                        <div class="journey-step" style="border-left-color: #ffc107; color: #ffc107;" data-step="3">
                            <h4>Premium Experience</h4>
                            <p>Personalized product demonstration, white-glove service, no pressure tactics</p>
                        </div>
                        
                        <div class="journey-step" style="border-left-color: #ffc107; color: #ffc107;" data-step="4">
                            <h4>Investment Decision</h4>
                            <p>Views purchase as investment in quality of life, not concerned about price</p>
                        </div>
                        
                        <div class="journey-step" style="border-left-color: #ffc107; color: #ffc107;" data-step="5">
                            <h4>Ongoing Relationship</h4>
                            <p>Expects concierge-level service, premium support, and exclusive access to new products</p>
                        </div>
                    </div>
                </div>

                <!-- Pricing Strategy -->
                <div class="mockup-card luxury">
                    <h3>💰 Pricing Strategy Mockup</h3>
                    <div class="pricing-mockup">
                        <div class="price-card">
                            <div>
                                <h4>Pride Jazzy Air 2 💎</h4>
                                <p style="color: #6c757d;">Ultimate mobility technology</p>
                            </div>
                            <div style="text-align: right;">
                                <div class="price-amount" style="color: #ffc107;">$29,999</div>
                                <div class="margin-indicator" style="background: linear-gradient(135deg, #ffc107, #e0a800);">52% Margin</div>
                            </div>
                        </div>
                        
                        <div class="price-card">
                            <div>
                                <h4>Stryker InTouch Hospital Bed 💎</h4>
                                <p style="color: #6c757d;">Hospital-grade premium comfort</p>
                            </div>
                            <div style="text-align: right;">
                                <div class="price-amount" style="color: #ffc107;">$12,499</div>
                                <div class="margin-indicator" style="background: linear-gradient(135deg, #ffc107, #e0a800);">48% Margin</div>
                            </div>
                        </div>
                        
                        <div class="price-card">
                            <div>
                                <h4>Inogen G5 Premium Package 💎</h4>
                                <p style="color: #6c757d;">Top-tier portable oxygen</p>
                            </div>
                            <div style="text-align: right;">
                                <div class="price-amount" style="color: #ffc107;">$3,999</div>
                                <div class="margin-indicator" style="background: linear-gradient(135deg, #ffc107, #e0a800);">55% Margin</div>
                            </div>
                        </div>
                    </div>
                    
                    <div class="highlight-box">
                        <strong>Pricing Philosophy:</strong> Premium pricing reflects superior technology, exclusive features, and exceptional service. Customers expect to pay more for the best and view price as quality indicator. Focus on value delivered, not price justification.
                    </div>
                </div>
            </div>
        </div>

        <!-- Comparison Section -->
        <div class="tier-section" style="background: #f8f9fa;">
            <div class="tier-header">
                <h2 class="tier-title" style="margin-bottom: 30px;">📊 Tier Comparison Matrix</h2>
            </div>

            <table class="comparison-table">
                <thead>
                    <tr>
                        <th>Criteria</th>
                        <th style="background: linear-gradient(135deg, #28a745, #20c997);">🟢 Economy</th>
                        <th style="background: linear-gradient(135deg, #007bff, #0056b3);">🔵 Value</th>
                        <th style="background: linear-gradient(135deg, #dc3545, #c82333);">🇺🇸 US-Made</th>
                        <th style="background: linear-gradient(135deg, #ffc107, #e0a800);">💎 Luxury</th>
                    </tr>
                </thead>
                <tbody>
                    <tr>
                        <td><strong>Inventory %</strong></td>
                        <td>5%</td>
                        <td>90%</td>
                        <td>2-3%</td>
                        <td>2-3%</td>
                    </tr>
                    <tr>
                        <td><strong>Margin Range</strong></td>
                        <td>20-30%</td>
                        <td>30-40%</td>
                        <td>35-50%</td>
                        <td>40-60%</td>
                    </tr>
                    <tr>
                        <td><strong>Target Customer</strong></td>
                        <td>Price-sensitive, lower income</td>
                        <td>Value-conscious, middle income</td>
                        <td>Patriotic, "Buy American"</td>
                        <td>Affluent, quality-focused</td>
                    </tr>
                    <tr>
                        <td><strong>Primary Value</strong></td>
                        <td>Affordability</td>
                        <td>Best price-performance</td>
                        <td>American manufacturing</td>
                        <td>Premium features & prestige</td>
                    </tr>
                    <tr>
                        <td><strong>Purchase Driver</strong></td>
                        <td>Necessity meets budget</td>
                        <td>Balanced decision-making</td>
                        <td>Patriotic values</td>
                        <td>Best available regardless of cost</td>
                    </tr>
                    <tr>
                        <td><strong>Service Level</strong></td>
                        <td>Standard, efficient</td>
                        <td>Professional, attentive</td>
                        <td>Personal, story-focused</td>
                        <td>White-glove, concierge</td>
                    </tr>
                    <tr>
                        <td><strong>Marketing Focus</strong></td>
                        <td>Price, affordability, access</td>
                        <td>Value, features, quality</td>
                        <td>Made in USA, American jobs</td>
                        <td>Innovation, luxury, exclusivity</td>
                    </tr>
                    <tr>
                        <td><strong>Example Product</strong></td>
                        <td>Basic manual wheelchair $199</td>
                        <td>Mid-range power chair $3,499</td>
                        <td>TiLite wheelchair $6,499</td>
                        <td>Pride Jazzy Air 2 $29,999</td>
                    </tr>
                    <tr>
                        <td><strong>Store Placement</strong></td>
                        <td>Value zone, clear pricing</td>
                        <td>Central, prominent display</td>
                        <td>Patriotic section with flags</td>
                        <td>Premium boutique showroom</td>
                    </tr>
                </tbody>
            </table>

            <div style="margin-top: 40px; background: white; padding: 30px; border-radius: 15px; box-shadow: 0 5px 20px rgba(0,0,0,0.1);">
                <h3 style="color: #1e3c72; margin-bottom: 20px;">🎯 Strategic Rationale</h3>
                <div class="highlight-box">
                    <p><strong>Economy Tier (5%):</strong> Captures price-sensitive market segment while maintaining acceptable margins. Essential for market coverage and meeting insurance-only customers' needs.</p>
                </div>
                <div class="highlight-box">
                    <p><strong>Value Tier (90%):</strong> Core business driver with largest market share. Balances volume and margins effectively. Most customers fall in this category seeking quality at reasonable prices.</p>
                </div>
                <div class="highlight-box">
                    <p><strong>US-Made Tier (2-3%):</strong> Captures patriotic customer segment willing to pay premium. Higher margins justify smaller inventory commitment. Strong differentiation from competitors.</p>
                </div>
                <div class="highlight-box">
                    <p><strong>Luxury Tier (2-3%):</strong> Highest margins with minimal inventory risk. Services affluent customers demanding best-in-class. Premium positioning enhances overall brand perception.</p>
                </div>
            </div>
        </div>

        <!-- Footer -->
        <div class="footer">
            <h3>💼 Strategic Implementation Success</h3>
            <p style="font-size: 1.1em; margin-top: 15px;">Four distinct positioning tiers working together to capture 100% of market opportunities</p>
            <p style="margin-top: 20px; opacity: 0.8;">From essential affordability to ultimate luxury - serving every customer's unique needs</p>
        </div>
    </div>
</body>
</html>
