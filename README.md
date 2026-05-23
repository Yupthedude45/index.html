<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Phaedra Aegis | Risk Guardian</title>
    <style>
        body {
            background-color: #0b0c10;
            color: #ffffff;
            font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
            margin: 0;
            padding: 15px;
            display: flex;
            flex-direction: column;
            align-items: center;
        }
        .container {
            max-width: 500px;
            width: 100%;
            text-align: center;
            padding-top: 20px;
            box-sizing: border-box;
        }
        h1 {
            font-size: 2.2rem;
            margin-bottom: 5px;
            letter-spacing: -1px;
        }
        .subtitle {
            color: #7f7cad;
            font-size: 1.1rem;
            margin-bottom: 25px;
            font-weight: 500;
        }
        .description {
            color: #a0a0a0;
            line-height: 1.5;
            margin-bottom: 30px;
            font-size: 0.95rem;
        }
        .form-container {
            background-color: #121212;
            border: 1px solid #222;
            border-radius: 12px;
            padding: 20px;
            margin: 30px 0;
            box-sizing: border-box;
            text-align: center;
        }
        .form-group {
            display: flex;
            flex-direction: column;
            gap: 12px;
        }
        .email-input {
            background-color: #1a1a1a;
            border: 1px solid #333;
            color: #ffffff;
            padding: 15px;
            font-size: 1rem;
            border-radius: 8px;
            width: 100%;
            box-sizing: border-box;
            outline: none;
            text-align: center;
            transition: border-color 0.2s ease;
        }
        .email-input:focus {
            border-color: #7f7cad;
        }
        .btn {
            background: linear-gradient(135deg, #7f7cad, #c39ea0);
            color: white;
            border: none;
            padding: 15px 20px;
            font-size: 1rem;
            font-weight: bold;
            border-radius: 8px;
            width: 100%;
            cursor: pointer;
            box-sizing: border-box;
            transition: opacity 0.2s ease;
        }
        .btn:disabled {
            opacity: 0.6;
            cursor: not-allowed;
        }
        [data-fs-success] {
            display: none;
            color: #c39ea0;
            font-weight: bold;
            font-size: 1.1rem;
            padding: 10px;
            border: 1px dashed #7f7cad;
            border-radius: 8px;
            background-color: #1a1a1a;
            margin-bottom: 15px;
        }
        [data-fs-error] {
            color: #ff6b6b;
            font-size: 0.85rem;
            margin-top: 5px;
            text-align: center;
        }
        .feature-card {
            background-color: #121212;
            border: 1px solid #222;
            border-radius: 12px;
            padding: 15px;
            margin-bottom: 20px;
            text-align: left;
            box-sizing: border-box;
        }
        .feature-card img {
            width: 100%;
            height: auto;
            border-radius: 8px;
            margin-top: 12px;
            display: block;
        }
        .feature-title {
            font-size: 1.1rem;
            font-weight: bold;
            color: #ffffff;
        }
        .feature-desc {
            color: #888;
            font-size: 0.9rem;
            margin-top: 5px;
            line-height: 1.4;
        }
        .legal {
            font-size: 0.7rem;
            color: #555;
            text-align: justify;
            margin-top: 35px;
            line-height: 1.4;
            border-top: 1px solid #222;
            padding-top: 15px;
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>Phaedra Aegis</h1>
        <div class="subtitle">Complex Volatility, Simplified.</div>
        
        <p class="description">An automated, non-custodial risk execution shield built for investors who don't speak numbers. Experience a calm desk while the system monitors market weather, manages guardrails, and defends your capital.</p>

        <div class="form-container">
            <div data-fs-success>🛡️ Beta Spot Secured! Welcome to the Guardrail.</div>
            <div data-fs-error></div>

            <form id="beta-form" class="form-group">
                <input type="email" id="email" name="email" class="email-input" placeholder="Enter your email address" data-fs-field required>
                <span data-fs-error="email"></span>
                <button type="submit" class="btn" data-fs-submit-btn>SECURE MY BETA SPOT</button>
            </form>
        </div>

        <h2 style="margin-top: 30px; margin-bottom: 15px; font-size: 1.4rem; letter-spacing: 1px;">CORE FEATURES</h2>

        <div class="feature-card">
            <div class="feature-title">Automated Wallet Execution</div>
            <div class="feature-desc">Connect safely via restricted APIs. The system handles protective buy/sell execution the second boundaries are crossed.</div>
            <img src="IMG_7357.png" alt="Wallet Execution Interface">
        </div>

        <div class="feature-card">
            <div class="feature-title">Real-Time Signal Parsing</div>
            <div class="feature-desc">Automated keyword detection across authorized channels and market weather feeds.</div>
            <img src="IMG_7358.png" alt="Signal Parsing Interface">
        </div>

        <div class="feature-card">
            <div class="feature-title">Global Currency Translation</div>
            <div class="feature-desc">Built-in CAD Lag Detector and multi-language localization parameters for borderless tracking.</div>
            <img src="IMG_7359.png" alt="CAD Lag Detector Interface">
        </div>
        
        <div class="legal">
            <strong>⚖️ PHAEDRA AEGIS: REGULATORY, EXECUTION & PRIVACY COMPLIANCE MANDATE</strong><br><br>
            Phaedra Aegis is a proprietary automated algorithmic execution, risk-management, and analytical support interface. By initializing this application, providing an account email address, and selecting a local region, you explicitly authorize the platform to utilize these data points solely to personalize localized market weather alerts, track macro data infrastructure, and display native localized currency matrices. Users maintain the absolute right to account termination and may request the permanent deletion of their account metadata and registration email from our secure authentication records at any time. Phaedra Aegis is a non-custodial interface; it does not hold, store, or maintain direct access to your private cryptographic keys, seed phrases, or external exchange credentials. By actively connecting third-party digital wallets or exchange API keys to this interface, you grant explicit authorization for Phaedra Aegis to automatically deploy and execute buy and sell orders on your behalf, based entirely on the custom allocation parameters, risk guardrails, and system thresholds configured within your local user settings. This software functions strictly as a neutral, user-directed execution interface; it does not analyze individual investor suitability, offer tailored investment strategies, or provide personalized financial, legal, tax, or investment advisory services. You acknowledge that automated execution involves severe inherent risks, including network latency, API disconnects, market slippage, and sudden liquidity shocks; the developer assumes no financial or legal liability for execution delays, unexpected market movements, or losses resulting from automated trading logic. To deliver real-time localized tracking, this application utilizes user-authorized background parsing tools to scan specified inbound text message keywords and user-forwarded data strings—including clipped information from restricted networks such as Facebook groups. This background string-parsing is executed strictly in real-time on your local device to trigger automated alerts; no private conversational text or contextual social data is scraped, logged, or transmitted to external databases. All fiat banking connectivity, payment interactions, and subscription processing are routed through secure, end-to-end encrypted third-party financial gateways including Stripe and Plaid API architectures; Phaedra Aegis never reads, accesses, or retains raw banking credentials, account routing numbers, or credit card primary account details. All session tokens, parsed tracking preferences, and encrypted API configurations remain stored strictly within the localized, secure sandbox partition of the user’s host device. Past analytical performance or simulated trends do not guarantee future results. All automation parameters are operated independently and solely at the risk of the user.
    </div>

    <script>
      window.formspree = window.formspree || function () { (formspree.q = formspree.q || []).push(arguments); };
      formspree('initForm', { formElement: '#beta-form', formId: 'mjgzrdnn' });
    </script>
    <script src="https://unpkg.com/@formspree/ajax@1" defer></script>
</body>
</html>
