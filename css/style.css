

        :root {
            --bg-dark: #0b0f1a;
            --bg-card: rgba(22, 28, 45, 0.7);
            --text-main: #f1f5f9;
            --text-muted: #94a3b8;
            --accent: #818cf8; 
            --accent-glow: rgba(129, 140, 248, 0.4);
            --success: #2dd4bf;
            --danger: #ef4444;
            --border: rgba(255, 255, 255, 0.1);
        }

        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            background-color: var(--bg-dark);
            color: var(--text-main);
            font-family: 'Inter', system-ui, -apple-system, sans-serif;
            margin: 0;
            display: flex;
            justify-content: center;
            align-items: center;
            min-height: 100vh;
            background: linear-gradient(135deg, #0b0f1a 0%, #1a1f35 100%);
        }

        .app-container {
            width: 95%;
            max-width: 1100px;
            padding: 20px;
        }

        header { 
            text-align: center; 
            margin-bottom: 30px; 
        }
        
        header h1 { 
            font-size: 2.8rem; 
            margin: 0; 
            letter-spacing: -1px;
            background: linear-gradient(135deg, #818cf8 0%, #2dd4bf 100%);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
            background-clip: text;
        }

        header .badge {
            display: inline-block;
            background: rgba(129, 140, 248, 0.2);
            color: var(--accent);
            padding: 4px 12px;
            border-radius: 12px;
            font-size: 0.75rem;
            font-weight: 600;
            margin-top: 8px;
        }
        
        header p { 
            color: var(--text-muted);
            margin-top: 10px;
        }

        .main-layout {
            display: grid;
            grid-template-columns: 1fr 1.3fr;
            gap: 20px;
        }

        .visual-section {
            background: var(--bg-card);
            border-radius: 24px;
            padding: 40px;
            border: 1px solid var(--border);
            backdrop-filter: blur(10px);
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: center;
            position: relative;
        }

        .sphere {
            width: 200px;
            height: 200px;
            background: radial-gradient(circle, var(--accent) 0%, transparent 70%);
            border-radius: 50%;
            display: flex;
            align-items: center;
            justify-content: center;
            box-shadow: 0 0 50px var(--accent-glow);
            margin-bottom: 20px;
            position: relative;
            overflow: hidden;
        }

        .sphere.recording {
            animation: pulse-glow 1.5s ease-in-out infinite;
            box-shadow: 0 0 80px var(--danger);
            background: radial-gradient(circle, #ef4444 0%, transparent 70%);
        }

        @keyframes pulse-glow {
            0%, 100% { transform: scale(1); opacity: 1; }
            50% { transform: scale(1.05); opacity: 0.8; }
        }

        canvas { 
            width: 100%; 
            height: 100%; 
            border-radius: 50%; 
        }

        .upload-zone {
            border: 2px dashed var(--border);
            border-radius: 16px;
            padding: 30px;
            text-align: center;
            transition: all 0.3s ease;
            cursor: pointer;
            background: rgba(255,255,255,0.02);
        }

        .upload-zone:hover {
            border-color: var(--accent);
            background: rgba(129, 140, 248, 0.05);
            transform: translateY(-2px);
        }

        .data-card {
            background: var(--bg-card);
            border-radius: 20px;
            padding: 24px;
            border: 1px solid var(--border);
            backdrop-filter: blur(10px);
            margin-bottom: 20px;
        }

        .data-card h3 {
            color: var(--text-muted);
            font-size: 0.9rem;
            font-weight: 500;
            text-transform: uppercase;
            letter-spacing: 1px;
            margin-bottom: 15px;
        }

        .emotion-display { 
            font-size: 2.8rem; 
            font-weight: 800; 
            color: var(--accent); 
            margin: 10px 0;
            text-transform: uppercase;
            letter-spacing: -1px;
        }

        .progress-bar {
            height: 10px;
            background: #1e293b;
            border-radius: 5px;
            overflow: hidden;
            margin: 15px 0;
        }

        #confidence-fill {
            height: 100%;
            width: 0%;
            background: linear-gradient(90deg, var(--accent), var(--success));
            transition: width 0.8s cubic-bezier(0.17, 0.67, 0.83, 0.67);
        }

        .status-pill {
            display: inline-block;
            padding: 6px 16px;
            border-radius: 12px;
            background: rgba(129, 140, 248, 0.1);
            color: var(--accent);
            font-size: 0.85rem;
            margin-top: 10px;
            font-weight: 500;
        }

        .status-pill.ready {
            background: rgba(45, 212, 191, 0.1);
            color: var(--success);
        }

        .status-pill.recording {
            background: rgba(239, 68, 68, 0.1);
            color: var(--danger);
            animation: pulse 1.5s ease-in-out infinite;
        }

        #file-input { 
            display: none; 
        }

        .loader {
            display: none;
            width: 40px;
            height: 40px;
            border: 4px solid rgba(129, 140, 248, 0.2);
            border-top-color: var(--accent);
            border-radius: 50%;
            animation: spin 1s linear infinite;
            margin: 20px auto;
        }

        .loader.active {
            display: block;
        }

        @keyframes spin {
            to { transform: rotate(360deg); }
        }

        @keyframes pulse {
            0%, 100% { opacity: 1; }
            50% { opacity: 0.6; }
        }

        .btn {
            width: 100%;
            padding: 18px;
            border: none;
            border-radius: 12px;
            font-size: 1.1rem;
            font-weight: 600;
            cursor: pointer;
            transition: all 0.3s ease;
            display: flex;
            align-items: center;
            justify-content: center;
            gap: 10px;
            margin-bottom: 15px;
        }

        .btn-record {
            background: linear-gradient(135deg, var(--accent) 0%, var(--success) 100%);
            color: white;
        }

        .btn-record:hover {
            transform: translateY(-2px);
            box-shadow: 0 5px 20px rgba(129, 140, 248, 0.4);
        }

        .btn-record.recording {
            background: linear-gradient(135deg, var(--danger) 0%, #dc2626 100%);
            animation: pulse 1.5s ease-in-out infinite;
        }

        .timer {
            font-size: 2.5rem;
            font-weight: bold;
            color: var(--danger);
            text-align: center;
            margin: 10px 0;
            min-height: 50px;
        }

        .divider {
            text-align: center;
            color: var(--text-muted);
            font-size: 0.85rem;
            margin: 20px 0;
            position: relative;
        }

        .divider::before,
        .divider::after {
            content: '';
            position: absolute;
            top: 50%;
            width: 40%;
            height: 1px;
            background: var(--border);
        }

        .divider::before { left: 0; }
        .divider::after { right: 0; }

        .features-grid {
            display: grid;
            grid-template-columns: repeat(3, 1fr);
            gap: 10px;
            margin-top: 20px;
        }

        .feature-box {
            background: rgba(255, 255, 255, 0.03);
            padding: 12px;
            border-radius: 10px;
            border: 1px solid var(--border);
            text-align: center;
        }

        .feature-box .label {
            font-size: 0.7rem;
            color: var(--text-muted);
            text-transform: uppercase;
            letter-spacing: 0.5px;
        }

        .feature-box .value {
            font-size: 1.2rem;
            color: var(--accent);
            font-weight: 700;
            margin-top: 4px;
        }

        .emotion-chart {
            background: rgba(255, 255, 255, 0.03);
            border-radius: 12px;
            padding: 15px;
            margin-top: 15px;
        }

        .chart-bar {
            display: flex;
            align-items: center;
            margin-bottom: 10px;
        }

        .chart-label {
            width: 100px;
            font-size: 0.8rem;
            color: var(--text-muted);
        }

        .chart-track {
            flex: 1;
            height: 8px;
            background: #1e293b;
            border-radius: 4px;
            margin: 0 10px;
            overflow: hidden;
        }

        .chart-fill {
            height: 100%;
            background: linear-gradient(90deg, var(--accent), var(--success));
            transition: width 0.6s ease;
        }

        .chart-value {
            width: 45px;
            font-size: 0.75rem;
            color: var(--accent);
            font-weight: 600;
            text-align: right;
        }

        .debug-info {
            background: rgba(0,0,0,0.3);
            border-radius: 8px;
            padding: 10px;
            margin-top: 10px;
            font-family: 'Courier New', monospace;
            font-size: 0.75rem;
            color: #00d2d3;
        }

        @media (max-width: 968px) {
            .main-layout { 
                grid-template-columns: 1fr; 
            }
            .features-grid {
                grid-template-columns: repeat(2, 1fr);
            }
        }
    
