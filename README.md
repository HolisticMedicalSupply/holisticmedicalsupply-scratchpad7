<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Pricing Strategy & Market Positioning</title>
    <style>
        * { margin: 0; padding: 0; box-sizing: border-box; }
        body { font-family: 'Segoe UI', sans-serif; background: linear-gradient(135deg, #f39c12, #e67e22); padding: 20px; }
        .container { max-width: 1600px; margin: 0 auto; background: white; border-radius: 20px; box-shadow: 0 20px 60px rgba(0,0,0,0.3); }
        .language-toggle { position: sticky; top: 0; z-index: 1000; background: rgba(255,255,255,0.98); padding: 15px 40px; display: flex; justify-content: center; gap: 15px; border-bottom: 3px solid #f39c12; box-shadow: 0 3px 15px rgba(0,0,0,0.1); }
        .lang-btn { padding: 12px 30px; border: 2px solid #f39c12; background: white; color: #f39c12; border-radius: 8px; cursor: pointer; font-size: 1.1em; font-weight: bold; transition: all 0.3s ease; }
        .lang-btn:hover { background: #fff8e8; transform: translateY(-2px); }
        .lang-btn.active { background: #f39c12; color: white; }
        .lang-content { display: none; }
        .lang-content.active { display: block; }
        .header { background: linear-gradient(135deg, #f39c12, #e67e22); color: white; padding: 60px 40px; text-align: center; }
        .header h1 { font-size: 4em; margin-bottom: 20px; }
        .section { padding: 50px 40px; }
        .section:nth-child(even) { background: #f8f9fa; }
        .tier-card { background: #fff8e8; padding: 30px; border-radius: 12px; margin: 25px 0; border-left: 5px solid #f39c12; }
        .tier-card h3 { color: #f39c12; margin-bottom: 15px; font-size: 1.8em; }
        ul { line-height: 1.9; margin-left: 20px; }
        ul li { margin: 10px 0; }
        .back-link { display: inline-block; background: #3498db; color: white; padding: 12px 30px; border-radius: 8px; text-decoration: none; margin: 20px 0; font-weight: bold; }
        .back-link:hover { background: #2980b9; }
        .pricing-grid { display: grid; grid-template-columns: repeat(auto-fit, minmax(280px, 1fr)); gap: 25px; margin: 40px 0; }
        .price-tier { background: white; padding: 30px; border-radius: 15px; box-shadow: 0 8px 25px rgba(0,0,0,0.1); text-align: center; border-top: 5px solid; }
        .price-tier.economy { border-top-color: #95a5a6; }
        .price-tier.value { border-top-color: #3498db; }
        .price-tier.usmade { border-top-color: #e74c3c; }
        .price-tier.luxury { border-top-color: #f39c12; }
        .price-tier h4 { font-size: 2em; margin-bottom: 15px; }
        .price-tier .margin { font-size: 2.5em; font-weight: bold; color: #27ae60; margin: 20px 0; }
    </style>
</head>
<body>
    <div class="container">
        <div class="language-toggle">
            <button class="lang-btn active" onclick="switchLanguage('en')" data-lang="en">🇺🇸 English</button>
            <button class="lang-btn" onclick="switchLanguage('ru')" data-lang="ru">🇷🇺 Русский</button>
            <button class="lang-btn" onclick="switchLanguage('uz')" data-lang="uz">🇺🇿 O'zbek</button>
        </div>

        <!-- ENGLISH -->
        <div class="lang-content active" id="content-en">
            <div class="header">
                <h1>💰 PRICING STRATEGY</h1>
                <p style="font-size: 1.8em;">4-Tier Market Positioning Model</p>
            </div>

            <div class="section">
                <a href="https://holisticmedicalsupply.github.io/holisticmedicalsupply-scratchpad4/" class="back-link">← Back to Portfolio</a>

                <h2 style="font-size: 2.5em; margin: 40px 0 30px 0; text-align: center; color: #e67e22;">Four Pricing Tiers</h2>

                <div class="pricing-grid">
                    <div class="price-tier economy">
                        <h4>🥉 ECONOMY</h4>
                        <p style="font-size: 1.2em; margin: 15px 0;"><strong>Import/Basic Models</strong></p>
                        <div class="margin">30-35%</div>
                        <p>Margin</p>
                        <ul style="text-align: left; margin-top: 20px;">
                            <li>Imported products</li>
                            <li>Basic functionality</li>
                            <li>Price-conscious buyers</li>
                            <li>Medicare baseline</li>
                        </ul>
                    </div>

                    <div class="price-tier value">
                        <h4>🥈 VALUE</h4>
                        <p style="font-size: 1.2em; margin: 15px 0;"><strong>Quality Mid-Range</strong></p>
                        <div class="margin">40-50%</div>
                        <p>Margin</p>
                        <ul style="text-align: left; margin-top: 20px;">
                            <li>Better features</li>
                            <li>Mix US/Import</li>
                            <li>Standard insurance tier</li>
                            <li>Most volume sales</li>
                        </ul>
                    </div>

                    <div class="price-tier usmade">
                        <h4>🇺🇸 US-MADE</h4>
                        <p style="font-size: 1.2em; margin: 15px 0;"><strong>Made in America Premium</strong></p>
                        <div class="margin">50-60%</div>
                        <p>Margin</p>
                        <ul style="text-align: left; margin-top: 20px;">
                            <li>100% US manufacturing</li>
                            <li>Quality assurance</li>
                            <li>Patriotic positioning</li>
                            <li>Premium justified</li>
                        </ul>
                    </div>

                    <div class="price-tier luxury">
                        <h4>💎 LUXURY</h4>
                        <p style="font-size: 1.2em; margin: 15px 0;"><strong>Premium/Complex Rehab</strong></p>
                        <div class="margin">55-70%</div>
                        <p>Margin</p>
                        <ul style="text-align: left; margin-top: 20px;">
                            <li>Top-tier brands</li>
                            <li>Custom solutions</li>
                            <li>Concierge service</li>
                            <li>Highest margins</li>
                        </ul>
                    </div>
                </div>

                <div class="tier-card">
                    <h3>📊 Implementation Strategy</h3>
                    <ul>
                        <li><strong>Stock All Tiers:</strong> Offer customers choice at every price point</li>
                        <li><strong>Insurance Flexibility:</strong> Accept all major insurance at all tiers</li>
                        <li><strong>Upsell Training:</strong> Staff trained to present higher-tier benefits</li>
                        <li><strong>Made in USA Marketing:</strong> Premium positioning for domestic products</li>
                        <li><strong>Volume Mix:</strong> Target 20% Economy, 50% Value, 20% US-Made, 10% Luxury</li>
                    </ul>
                </div>

                <div class="tier-card">
                    <h3>💡 Why This Works</h3>
                    <ul>
                        <li>✅ <strong>Customer Choice:</strong> Never lose a sale due to price - have options for all budgets</li>
                        <li>✅ <strong>Margin Optimization:</strong> Average 45-55% margins across product mix</li>
                        <li>✅ <strong>Insurance Friendly:</strong> Can work with any insurance approval level</li>
                        <li>✅ <strong>Competitive Edge:</strong> Most competitors only offer 1-2 tiers</li>
                        <li>✅ <strong>US-Made Premium:</strong> 10-20% premium pricing justified by quality and patriotism</li>
                    </ul>
                </div>

                <a href="https://holisticmedicalsupply.github.io/holisticmedicalsupply-scratchpad4/" class="back-link">← Back to Portfolio</a>
            </div>
        </div>

        <!-- RUSSIAN -->
        <div class="lang-content" id="content-ru">
            <div class="header">
                <h1>💰 ЦЕНОВАЯ СТРАТЕГИЯ</h1>
                <p style="font-size: 1.8em;">Модель Позиционирования на Рынке с 4 Уровнями</p>
            </div>

            <div class="section">
                <a href="https://holisticmedicalsupply.github.io/holisticmedicalsupply-scratchpad4/" class="back-link">← Назад</a>

                <h2 style="font-size: 2.5em; margin: 40px 0 30px 0; text-align: center; color: #e67e22;">Четыре Ценовых Уровня</h2>

                <div class="pricing-grid">
                    <div class="price-tier economy">
                        <h4>🥉 ЭКОНОМ</h4>
                        <p style="font-size: 1.2em; margin: 15px 0;"><strong>Импорт/Базовые Модели</strong></p>
                        <div class="margin">30-35%</div>
                        <p>Маржа</p>
                        <ul style="text-align: left; margin-top: 20px;">
                            <li>Импортные продукты</li>
                            <li>Базовый функционал</li>
                            <li>Экономные покупатели</li>
                            <li>Базовая линия Medicare</li>
                        </ul>
                    </div>

                    <div class="price-tier value">
                        <h4>🥈 ЦЕННОСТЬ</h4>
                        <p style="font-size: 1.2em; margin: 15px 0;"><strong>Качественный Средний Сегмент</strong></p>
                        <div class="margin">40-50%</div>
                        <p>Маржа</p>
                        <ul style="text-align: left; margin-top: 20px;">
                            <li>Лучшие функции</li>
                            <li>Микс США/Импорт</li>
                            <li>Стандартная страховка</li>
                            <li>Максимум продаж</li>
                        </ul>
                    </div>

                    <div class="price-tier usmade">
                        <h4>🇺🇸 СДЕЛАНО В США</h4>
                        <p style="font-size: 1.2em; margin: 15px 0;"><strong>Премиум Американского Производства</strong></p>
                        <div class="margin">50-60%</div>
                        <p>Маржа</p>
                        <ul style="text-align: left; margin-top: 20px;">
                            <li>100% производство США</li>
                            <li>Гарантия качества</li>
                            <li>Патриотическое позиционирование</li>
                            <li>Оправданная премия</li>
                        </ul>
                    </div>

                    <div class="price-tier luxury">
                        <h4>💎 ЛЮКС</h4>
                        <p style="font-size: 1.2em; margin: 15px 0;"><strong>Премиум/Сложная Реабилитация</strong></p>
                        <div class="margin">55-70%</div>
                        <p>Маржа</p>
                        <ul style="text-align: left; margin-top: 20px;">
                            <li>Топовые бренды</li>
                            <li>Индивидуальные решения</li>
                            <li>Консьерж-сервис</li>
                            <li>Максимальная маржа</li>
                        </ul>
                    </div>
                </div>

                <a href="https://holisticmedicalsupply.github.io/holisticmedicalsupply-scratchpad4/" class="back-link">← Назад</a>
            </div>
        </div>

        <!-- UZBEK -->
        <div class="lang-content" id="content-uz">
            <div class="header">
                <h1>💰 NARX STRATEGIYASI</h1>
                <p style="font-size: 1.8em;">4 Darajali Bozor Joylashuv Modeli</p>
            </div>

            <div class="section">
                <a href="https://holisticmedicalsupply.github.io/holisticmedicalsupply-scratchpad4/" class="back-link">← Orqaga</a>

                <h2 style="font-size: 2.5em; margin: 40px 0 30px 0; text-align: center; color: #e67e22;">To'rt Narx Darajasi</h2>

                <div class="pricing-grid">
                    <div class="price-tier economy">
                        <h4>🥉 IQTISODIY</h4>
                        <p style="font-size: 1.2em; margin: 15px 0;"><strong>Import/Asosiy Modellar</strong></p>
                        <div class="margin">30-35%</div>
                        <p>Marja</p>
                        <ul style="text-align: left; margin-top: 20px;">
                            <li>Import mahsulotlar</li>
                            <li>Asosiy funksionallik</li>
                            <li>Narxga e'tiborli xaridorlar</li>
                            <li>Medicare bazasi</li>
                        </ul>
                    </div>

                    <div class="price-tier value">
                        <h4>🥈 QIYMAT</h4>
                        <p style="font-size: 1.2em; margin: 15px 0;"><strong>Sifatli O'rta Segment</strong></p>
                        <div class="margin">40-50%</div>
                        <p>Marja</p>
                        <ul style="text-align: left; margin-top: 20px;">
                            <li>Yaxshiroq xususiyatlar</li>
                            <li>AQSH/Import aralashma</li>
                            <li>Standart sug'urta</li>
                            <li>Ko'p hajmda sotish</li>
                        </ul>
                    </div>

                    <div class="price-tier usmade">
                        <h4>🇺🇸 AQSH ISHLAB CHIQARILGAN</h4>
                        <p style="font-size: 1.2em; margin: 15px 0;"><strong>Amerika Ishlab Chiqarish Premium</strong></p>
                        <div class="margin">50-60%</div>
                        <p>Marja</p>
                        <ul style="text-align: left; margin-top: 20px;">
                            <li>100% AQSH ishlab chiqarish</li>
                            <li>Sifat kafolati</li>
                            <li>Vatanparvarlik joylashuvi</li>
                            <li>Oqlangan premium</li>
                        </ul>
                    </div>

                    <div class="price-tier luxury">
                        <h4>💎 HASHAMAT</h4>
                        <p style="font-size: 1.2em; margin: 15px 0;"><strong>Premium/Murakkab Reabilitatsiya</strong></p>
                        <div class="margin">55-70%</div>
                        <p>Marja</p>
                        <ul style="text-align: left; margin-top: 20px;">
                            <li>Eng yaxshi brendlar</li>
                            <li>Maxsus yechimlar</li>
                            <li>Konserzh xizmati</li>
                            <li>Eng yuqori marja</li>
                        </ul>
                    </div>
                </div>

                <a href="https://holisticmedicalsupply.github.io/holisticmedicalsupply-scratchpad4/" class="back-link">← Orqaga</a>
            </div>
        </div>
    </div>

    <script>
        function switchLanguage(lang) {
            document.querySelectorAll('.lang-content').forEach(content => content.classList.remove('active'));
            document.querySelectorAll('.lang-btn').forEach(btn => btn.classList.remove('active'));
            document.getElementById('content-' + lang).classList.add('active');
            document.querySelector(`.lang-btn[data-lang="${lang}"]`).classList.add('active');
            localStorage.setItem('preferred-language', lang);
            window.scrollTo(0, 0);
        }
        window.addEventListener('DOMContentLoaded', function() {
            const savedLang = localStorage.getItem('preferred-language');
            if (savedLang && ['en', 'ru', 'uz'].includes(savedLang)) switchLanguage(savedLang);
        });
    </script>
</body>
</html>
