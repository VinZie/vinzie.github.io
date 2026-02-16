<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Fappy Bird</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            display: flex;
            justify-content: center;
            align-items: center;
            min-height: 100vh;
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            transition: background 2s ease;
            margin: 0;
            padding: 0;
        }

        #gameContainer {
            position: relative;
            box-shadow: 0 25px 80px rgba(0, 0, 0, 0.3);
            border-radius: 24px;
            overflow: hidden;
            max-height: 95vh;
        }

        canvas {
            border: none;
            border-radius: 24px;
            display: block;
            max-height: 95vh;
            width: auto;
        }

        #ui {
            position: absolute;
            top: 20px;
            left: 20px;
            right: 20px;
            display: flex;
            justify-content: space-between;
            align-items: flex-start;
            pointer-events: none;
            z-index: 10;
        }

        #score {
            background: rgba(0, 0, 0, 0.45);
            backdrop-filter: blur(12px);
            color: white;
            padding: 10px 20px;
            font-size: 32px;
            font-weight: 700;
            border-radius: 14px;
            border: 1px solid rgba(255, 255, 255, 0.1);
            box-shadow: 0 4px 20px rgba(0, 0, 0, 0.25);
            min-width: 60px;
            text-align: center;
        }

        #highScore {
            background: linear-gradient(135deg, rgba(255, 215, 0, 0.12), rgba(255, 180, 0, 0.06));
            backdrop-filter: blur(12px);
            color: #FFD700;
            padding: 8px 16px;
            font-size: 15px;
            font-weight: 600;
            border-radius: 10px;
            border: 1px solid rgba(255, 215, 0, 0.2);
            box-shadow: 0 4px 16px rgba(255, 215, 0, 0.08);
            letter-spacing: 0.5px;
        }

        #gameOver {
            position: absolute;
            top: 50%;
            left: 50%;
            transform: translate(-50%, -50%);
            background: linear-gradient(145deg, #0a0a1a 0%, #1a0a2e 50%, #0a0a1a 100%);
            backdrop-filter: blur(24px);
            padding: 44px 48px;
            border-radius: 28px;
            text-align: center;
            color: white;
            display: none;
            border: 2px solid rgba(255, 215, 0, 0.2);
            box-shadow: 0 30px 90px rgba(0, 0, 0, 0.6), 0 0 60px rgba(255, 215, 0, 0.05), inset 0 1px 0 rgba(255, 255, 255, 0.05);
        }

        #gameOver h1 {
            font-size: 36px;
            margin-bottom: 12px;
            background: linear-gradient(135deg, #ff6b6b, #FFA500, #FFD700);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
            background-clip: text;
            font-weight: 800;
            letter-spacing: 2px;
        }

        #gameOver p {
            font-size: 18px;
            margin: 8px 0;
            font-weight: 500;
            color: rgba(255, 255, 255, 0.7);
        }

        #gameOver button {
            margin-top: 8px;
        }

        #gameOver button:hover {
            background: linear-gradient(135deg, rgba(255, 215, 0, 0.12) 0%, rgba(255, 215, 0, 0.04) 100%);
            border-color: rgba(255, 215, 0, 0.4);
            transform: translateY(-2px);
            box-shadow: 0 8px 24px rgba(0, 0, 0, 0.4), 0 0 20px rgba(255, 215, 0, 0.08);
        }

        #startScreen {
            position: absolute;
            top: 50%;
            left: 50%;
            transform: translate(-50%, -50%);
            text-align: center;
            color: white;
            background: linear-gradient(145deg, #0a0a1a 0%, #1a0a2e 50%, #0a0a1a 100%);
            backdrop-filter: blur(24px);
            padding: 44px 48px;
            border-radius: 28px;
            border: 2px solid rgba(255, 215, 0, 0.2);
            box-shadow: 0 30px 90px rgba(0, 0, 0, 0.6), 0 0 60px rgba(255, 215, 0, 0.05), inset 0 1px 0 rgba(255, 255, 255, 0.05);
        }

        #startScreen h1 {
            font-size: 44px;
            margin-bottom: 6px;
            background: linear-gradient(135deg, #FFD700, #FFA500, #FFD700);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
            background-clip: text;
            font-weight: 800;
            letter-spacing: 3px;
        }

        #startScreen p {
            font-size: 14px;
            animation: pulse 1.5s infinite;
            color: rgba(255, 215, 0, 0.5);
            font-weight: 500;
            margin-bottom: 20px;
            letter-spacing: 4px;
            text-transform: uppercase;
        }

        #startScreen button, #gameOver button {
            background: linear-gradient(135deg, rgba(255, 255, 255, 0.07) 0%, rgba(255, 255, 255, 0.02) 50%, rgba(255, 215, 0, 0.04) 100%);
            color: rgba(255, 255, 255, 0.9);
            border: 1px solid rgba(255, 215, 0, 0.18);
            padding: 14px 28px;
            font-size: 16px;
            font-weight: 600;
            border-radius: 14px;
            cursor: pointer;
            margin: 5px;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            transition: all 0.3s cubic-bezier(0.25, 0.46, 0.45, 0.94);
            box-shadow: 0 4px 20px rgba(0, 0, 0, 0.35), inset 0 1px 0 rgba(255, 255, 255, 0.06);
            backdrop-filter: blur(12px);
            display: block;
            width: 100%;
            position: relative;
            overflow: hidden;
            letter-spacing: 0.5px;
        }

        #startScreen button::before, #gameOver button::before {
            content: '';
            position: absolute;
            top: 0; left: -100%; width: 100%; height: 100%;
            background: linear-gradient(90deg, transparent, rgba(255, 215, 0, 0.06), transparent);
            transition: left 0.5s ease;
        }
        #startScreen button:hover::before, #gameOver button:hover::before {
            left: 100%;
        }

        #startScreen button:hover, #gameOver button:hover {
            background: linear-gradient(135deg, rgba(255, 215, 0, 0.12) 0%, rgba(255, 215, 0, 0.04) 50%, rgba(255, 215, 0, 0.08) 100%);
            border-color: rgba(255, 215, 0, 0.45);
            transform: translateY(-2px);
            box-shadow: 0 8px 28px rgba(0, 0, 0, 0.45), 0 0 20px rgba(255, 215, 0, 0.06), inset 0 1px 0 rgba(255, 215, 0, 0.1);
            color: #fff;
        }

        #startScreen button:active, #gameOver button:active {
            transform: translateY(0);
            box-shadow: 0 2px 10px rgba(0, 0, 0, 0.3);
        }

        #skinSelector {
            position: absolute;
            top: 50%;
            left: 50%;
            transform: translate(-50%, -50%);
            background: linear-gradient(145deg, #0a0a1a 0%, #1a0a2e 50%, #0a0a1a 100%);
            backdrop-filter: blur(24px);
            padding: 40px;
            border-radius: 24px;
            text-align: center;
            display: none;
            z-index: 10;
            border: 2px solid rgba(255, 215, 0, 0.2);
            box-shadow: 0 30px 80px rgba(0, 0, 0, 0.6), inset 0 1px 0 rgba(255, 215, 0, 0.08);
            width: 90%;
            max-width: 800px;
            max-height: 85vh;
            overflow-y: auto;
        }

        #skinSelector.show {
            display: block;
        }

        #skinSelector h3 {
            color: transparent;
            background: linear-gradient(135deg, #FFD700, #FFA500);
            -webkit-background-clip: text;
            background-clip: text;
            font-size: 32px;
            margin-bottom: 24px;
            font-weight: 800;
            letter-spacing: 1px;
        }

        #skinOptionsContainer {
            display: grid;
            grid-template-columns: repeat(auto-fill, minmax(120px, 1fr));
            gap: 18px;
            margin: 20px 0;
            padding: 10px;
            max-width: 100%;
        }

        .skin-option {
            background: rgba(0, 0, 0, 0.4);
            border-radius: 16px;
            padding: 16px;
            cursor: pointer;
            border: 3px solid transparent;
            transition: all 0.3s ease;
            display: flex;
            flex-direction: column;
            align-items: center;
            gap: 10px;
        }

        .skin-option:hover {
            transform: translateY(-5px);
            border-color: rgba(255, 215, 0, 0.5);
            box-shadow: 0 8px 25px rgba(255, 215, 0, 0.3);
        }

        .skin-option.selected {
            border-color: #FFD700;
            background: rgba(255, 215, 0, 0.15);
            box-shadow: 0 0 30px rgba(255, 215, 0, 0.5);
        }

        .skin-option canvas {
            border-radius: 12px;
            background: linear-gradient(to bottom, #87CEEB, #E0F6FF);
        }

        .skin-option-name {
            color: white;
            font-size: 14px;
            font-weight: 600;
            text-align: center;
        }

        /* Volume Control */
        #volumeControl {
            position: absolute;
            top: 100px;
            left: 20px;
            background: rgba(10, 10, 20, 0.85);
            backdrop-filter: blur(16px);
            padding: 14px 10px;
            border-radius: 20px;
            border: 1px solid rgba(255, 215, 0, 0.15);
            box-shadow: 0 8px 32px rgba(0, 0, 0, 0.4), 0 0 20px rgba(255, 215, 0, 0.05);
            z-index: 5;
            display: flex;
            flex-direction: column;
            align-items: center;
            gap: 10px;
            transition: all 0.3s ease;
        }

        #volumeControl.hidden {
            opacity: 0;
            pointer-events: none;
            transform: translateX(-20px);
        }

        #volumeIcon {
            font-size: 22px;
            cursor: pointer;
            user-select: none;
            transition: all 0.2s ease;
            filter: drop-shadow(0 2px 6px rgba(255, 215, 0, 0.3));
        }

        #volumeIcon:hover {
            transform: scale(1.15);
            filter: drop-shadow(0 3px 10px rgba(255, 215, 0, 0.5));
        }

        #volumeIcon:active {
            transform: scale(1.0);
        }

        #volumeSlider {
            -webkit-appearance: none;
            appearance: none;
            width: 8px;
            height: 110px;
            border-radius: 10px;
            background: linear-gradient(to top, 
                rgba(255, 215, 0, 0.25) 0%, 
                rgba(255, 215, 0, 0.08) 100%);
            outline: none;
            cursor: pointer;
            writing-mode: bt-lr;
            -webkit-appearance: slider-vertical;
            box-shadow: inset 0 2px 8px rgba(0, 0, 0, 0.3);
        }

        #volumeSlider::-webkit-slider-thumb {
            -webkit-appearance: none;
            appearance: none;
            width: 20px;
            height: 20px;
            border-radius: 50%;
            background: linear-gradient(145deg, #FFD700, #FFA500);
            cursor: pointer;
            box-shadow: 0 2px 12px rgba(255, 215, 0, 0.6), 
                        0 0 20px rgba(255, 215, 0, 0.3),
                        inset 0 1px 2px rgba(255, 255, 255, 0.3);
            transition: all 0.2s ease;
            border: 2px solid rgba(255, 215, 0, 0.8);
        }

        #volumeSlider::-webkit-slider-thumb:hover {
            transform: scale(1.15);
            box-shadow: 0 3px 16px rgba(255, 215, 0, 0.8), 
                        0 0 30px rgba(255, 215, 0, 0.5),
                        inset 0 1px 2px rgba(255, 255, 255, 0.4);
        }

        #volumeSlider::-webkit-slider-thumb:active {
            transform: scale(1.05);
        }

        #volumeSlider::-moz-range-thumb {
            width: 20px;
            height: 20px;
            border-radius: 50%;
            background: linear-gradient(145deg, #FFD700, #FFA500);
            cursor: pointer;
            border: 2px solid rgba(255, 215, 0, 0.8);
            box-shadow: 0 2px 12px rgba(255, 215, 0, 0.6), 
                        0 0 20px rgba(255, 215, 0, 0.3);
        }

        #volumeValue {
            color: rgba(255, 215, 0, 0.9);
            font-size: 12px;
            font-weight: 700;
            min-width: 38px;
            text-align: center;
            text-shadow: 0 1px 4px rgba(0, 0, 0, 0.5);
            letter-spacing: 0.5px;
        }

        #liveFps {
            position: absolute;
            bottom: 12px;
            left: 12px;
            background: rgba(0,0,0,0.5);
            backdrop-filter: blur(8px);
            color: #0f0;
            padding: 6px 12px;
            font-size: 14px;
            font-weight: 600;
            border-radius: 8px;
            font-family: 'Consolas', 'Courier New', monospace;
            pointer-events: none;
            z-index: 10;
            border: 1px solid rgba(0,255,0,0.2);
        }

        .skin-yellow { background: linear-gradient(135deg, #FFE55C, #FFD700); }
        .skin-blue { background: linear-gradient(135deg, #6495ED, #4169E1); }
        .skin-red { background: linear-gradient(135deg, #FF6347, #DC143C); }
        .skin-green { background: linear-gradient(135deg, #90EE90, #32CD32); }
        .skin-purple { background: linear-gradient(135deg, #DDA0DD, #9370DB); }
        .skin-eagle { background: linear-gradient(135deg, #A0522D, #8B4513); }
        .skin-penguin { background: linear-gradient(135deg, #2F4F4F, #000000); }
        .skin-golden { background: linear-gradient(135deg, #FFF8B0, #FFD700, #DAA520); }
        .skin-dictator { background: linear-gradient(135deg, #5c5c48, #3a3a2a, #2a2a1a); }
        .skin-phoenix { background: linear-gradient(135deg, #FF6A33, #FF4500, #CC3300); }
        .skin-ice { background: linear-gradient(135deg, #E0F7FA, #B0E0E6, #5F9EA0); }
        .skin-shadow { background: linear-gradient(135deg, #2d2d44, #1a1a2e, #0f0f1a); }
        .skin-candy { background: linear-gradient(135deg, #FFB6C1, #FF69B4, #FF1493); }

        #closeSkinSelector {
            background: linear-gradient(135deg, rgba(255, 255, 255, 0.08), rgba(255, 255, 255, 0.03));
            color: rgba(255, 255, 255, 0.7);
            border: 1px solid rgba(255, 255, 255, 0.1);
            padding: 12px 28px;
            font-size: 15px;
            font-weight: 600;
            border-radius: 12px;
            cursor: pointer;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            transition: all 0.25s ease;
        }
        #closeSkinSelector:hover {
            background: rgba(255, 255, 255, 0.1);
            color: white;
            border-color: rgba(255, 255, 255, 0.2);
        }

        #shopMenu {
            position: absolute;
            top: 50%;
            left: 50%;
            transform: translate(-50%, -50%);
            background: linear-gradient(145deg, #0a0a1a 0%, #12082a 50%, #0a0a1a 100%);
            padding: 28px;
            border-radius: 24px;
            text-align: center;
            display: none;
            z-index: 10;
            max-width: 520px;
            min-width: 400px;
            max-height: 80vh;
            overflow-y: auto;
            border: 2px solid rgba(255, 215, 0, 0.15);
            box-shadow: 0 30px 80px rgba(0, 0, 0, 0.6), inset 0 1px 0 rgba(255, 255, 255, 0.05);
        }

        #shopMenu::-webkit-scrollbar { width: 6px; }
        #shopMenu::-webkit-scrollbar-track { background: transparent; }
        #shopMenu::-webkit-scrollbar-thumb { background: rgba(255, 215, 0, 0.2); border-radius: 3px; }

        #shopMenu.show {
            display: block;
        }

        #shopMenu h3 {
            color: transparent;
            background: linear-gradient(135deg, #FFD700, #FFA500);
            -webkit-background-clip: text;
            background-clip: text;
            font-size: 28px;
            margin-bottom: 6px;
            font-weight: 800;
            letter-spacing: 1px;
        }

        .shop-tabs {
            display: flex; gap: 4px; margin: 12px 0 14px; justify-content: center;
        }
        .shop-tab {
            background: rgba(255,255,255,0.04); color: rgba(255,255,255,0.5);
            border: 1px solid rgba(255,215,0,0.1); border-radius: 10px;
            padding: 8px 16px; font-size: 14px; font-weight: 600; cursor: pointer;
            transition: all 0.25s; font-family: inherit;
        }
        .shop-tab:hover { color: rgba(255,255,255,0.8); border-color: rgba(255,215,0,0.3); }
        .shop-tab.active {
            background: linear-gradient(135deg, rgba(255,215,0,0.15), rgba(255,215,0,0.05));
            color: #FFD700; border-color: rgba(255,215,0,0.4);
            box-shadow: 0 2px 10px rgba(255,215,0,0.1);
        }

        #coinDisplay {
            color: rgba(255, 255, 255, 0.6);
            font-size: 16px;
            margin-bottom: 16px;
            padding: 8px 16px;
            background: rgba(255, 215, 0, 0.06);
            border-radius: 10px;
            border: 1px solid rgba(255, 215, 0, 0.1);
            display: inline-block;
        }

        #coinDisplay span {
            color: #FFD700;
            font-weight: 700;
        }

        .shop-item {
            background: rgba(255, 255, 255, 0.04);
            border-radius: 14px;
            padding: 12px 14px;
            margin: 8px 0;
            display: flex;
            align-items: center;
            justify-content: space-between;
            transition: all 0.25s ease;
            border: 1px solid rgba(255, 255, 255, 0.05);
        }

        .shop-item:hover {
            background: rgba(255, 255, 255, 0.07);
            border-color: rgba(255, 215, 0, 0.1);
        }

        .shop-item-left {
            display: flex;
            align-items: center;
            gap: 12px;
        }

        .shop-item-preview {
            width: 80px;
            height: 64px;
            border-radius: 12px;
            border: 2px solid rgba(255, 215, 0, 0.25);
            position: relative;
            background: linear-gradient(to bottom, #4a7ab5 0%, #6a9fd8 50%, #8bc4a0 100%);
            display: flex;
            align-items: center;
            justify-content: center;
            flex-shrink: 0;
            overflow: hidden;
        }

        .shop-bird-mini {
            width: 100%;
            height: 100%;
            display: flex;
            align-items: center;
            justify-content: center;
        }

        .shop-item-info {
            text-align: left;
        }

        .shop-item-name {
            color: rgba(255, 255, 255, 0.9);
            font-size: 15px;
            font-weight: 700;
        }

        .shop-item-price {
            color: rgba(255, 215, 0, 0.7);
            font-size: 13px;
            font-weight: 600;
        }

        .shop-buy-btn {
            background: linear-gradient(135deg, #1a7a3a 0%, #0d5c26 100%);
            color: white;
            border: 1px solid rgba(255, 255, 255, 0.1);
            padding: 7px 14px;
            font-size: 12px;
            font-weight: 700;
            border-radius: 8px;
            cursor: pointer;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            transition: all 0.25s ease;
            white-space: nowrap;
            flex-shrink: 0;
        }

        .shop-buy-btn:hover {
            background: linear-gradient(135deg, #22994a 0%, #117a32 100%);
            transform: translateY(-1px);
            box-shadow: 0 4px 12px rgba(26, 122, 58, 0.3);
        }

        .shop-buy-btn:disabled {
            background: rgba(255, 255, 255, 0.05);
            color: rgba(255, 255, 255, 0.3);
            border-color: rgba(255, 255, 255, 0.05);
            cursor: not-allowed;
            transform: none;
            box-shadow: none;
            font-size: 11px;
        }

        .shop-item.owned {
            opacity: 0.5;
        }

        .owned-badge {
            background: rgba(255, 215, 0, 0.12);
            color: rgba(255, 215, 0, 0.7);
            padding: 5px 10px;
            border-radius: 8px;
            font-size: 11px;
            font-weight: 700;
            letter-spacing: 1px;
            border: 1px solid rgba(255, 215, 0, 0.15);
        }

        .equipped-badge {
            background: linear-gradient(135deg, rgba(80,220,120,0.15), rgba(80,220,120,0.05));
            color: rgba(80,220,120,0.9);
            padding: 5px 10px;
            border-radius: 8px;
            font-size: 11px;
            font-weight: 700;
            letter-spacing: 1px;
            border: 1px solid rgba(80,220,120,0.25);
        }

        .shop-item.equipped {
            opacity: 1;
            border: 1px solid rgba(80,220,120,0.2);
            background: rgba(80,220,120,0.04);
        }

        .shop-equip-btn {
            background: linear-gradient(135deg, rgba(255,215,0,0.15), rgba(255,215,0,0.05));
            color: #FFD700;
            border: 1px solid rgba(255,215,0,0.25);
            padding: 7px 14px;
            font-size: 12px;
            font-weight: 700;
            border-radius: 8px;
            cursor: pointer;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            transition: all 0.25s ease;
            white-space: nowrap;
            flex-shrink: 0;
        }
        .shop-equip-btn:hover {
            background: linear-gradient(135deg, rgba(255,215,0,0.25), rgba(255,215,0,0.1));
            border-color: rgba(255,215,0,0.5);
            transform: translateY(-1px);
        }

        .shop-buy-trail-btn {
            background: linear-gradient(135deg, #1a7a3a 0%, #0d5c26 100%);
            color: white;
            border: 1px solid rgba(255,255,255,0.1);
            padding: 7px 14px;
            font-size: 12px;
            font-weight: 700;
            border-radius: 8px;
            cursor: pointer;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            transition: all 0.25s ease;
            white-space: nowrap;
            flex-shrink: 0;
        }
        .shop-buy-trail-btn:hover {
            background: linear-gradient(135deg, #22994a 0%, #117a32 100%);
            transform: translateY(-1px);
            box-shadow: 0 4px 12px rgba(26,122,58,0.3);
        }
        .shop-buy-trail-btn:disabled {
            background: rgba(255,255,255,0.05);
            color: rgba(255,255,255,0.3);
            border-color: rgba(255,255,255,0.05);
            cursor: not-allowed;
            transform: none;
            font-size: 11px;
        }

        #coinCounter {
            position: absolute;
            bottom: 60px;
            right: 16px;
            color: #FFD700;
            font-size: 22px;
            font-weight: 700;
            text-shadow: none;
            pointer-events: none;
            display: none;
            z-index: 5;
            background: rgba(0, 0, 0, 0.5);
            backdrop-filter: blur(12px);
            padding: 10px 18px;
            border-radius: 12px;
            border: 1px solid rgba(255, 215, 0, 0.2);
            box-shadow: 0 4px 16px rgba(255, 215, 0, 0.1);
        }

        #coinCounter.show {
            display: block;
        }

        #blackjackGame {
            position: absolute;
            top: 50%;
            left: 50%;
            transform: translate(-50%, -50%);
            background: linear-gradient(145deg, #0a1628 0%, #0d2137 40%, #0a1628 100%);
            padding: 20px 28px;
            border-radius: 24px;
            text-align: center;
            display: none;
            z-index: 10;
            min-width: 600px;
            max-width: 98%;
            width: 800px;
            border: 2px solid rgba(255, 215, 0, 0.25);
            box-shadow: 0 30px 80px rgba(0, 0, 0, 0.7), inset 0 1px 0 rgba(255, 215, 0, 0.1);
            height: 750px;
            max-height: 95vh;
            overflow-y: auto;
        }

        #blackjackGame.show {
            display: block;
        }

        #gamblingHub {
            position: absolute;
            top: 50%;
            left: 50%;
            transform: translate(-50%, -50%);
            background: linear-gradient(145deg, #0a0a1a 0%, #1a0a2e 50%, #0a0a1a 100%);
            backdrop-filter: blur(24px);
            padding: 44px 40px;
            border-radius: 28px;
            text-align: center;
            display: none;
            z-index: 10;
            min-width: 420px;
            border: 2px solid rgba(255, 215, 0, 0.2);
            box-shadow: 0 30px 90px rgba(0, 0, 0, 0.6), 0 0 60px rgba(255, 215, 0, 0.05), inset 0 1px 0 rgba(255, 255, 255, 0.05);
        }

        #gamblingHub.show {
            display: block;
        }

        #gamblingHub h3 {
            color: transparent;
            background: linear-gradient(135deg, #FFD700, #FFA500, #FFD700);
            -webkit-background-clip: text;
            background-clip: text;
            font-size: 38px;
            margin-bottom: 6px;
            font-weight: 800;
            letter-spacing: 3px;
        }

        .gambling-hub-subtitle {
            color: rgba(255, 215, 0, 0.5);
            font-size: 13px;
            letter-spacing: 6px;
            text-transform: uppercase;
            margin-bottom: 24px;
            font-weight: 600;
        }

        .gambling-game-btn {
            background: linear-gradient(135deg, rgba(255, 255, 255, 0.07) 0%, rgba(255, 255, 255, 0.02) 50%, rgba(255, 215, 0, 0.04) 100%);
            color: rgba(255, 255, 255, 0.9);
            border: 1px solid rgba(255, 215, 0, 0.18);
            padding: 16px 28px;
            margin: 6px auto;
            font-size: 18px;
            font-weight: 600;
            border-radius: 14px;
            cursor: pointer;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            transition: all 0.3s cubic-bezier(0.25, 0.46, 0.45, 0.94);
            display: flex;
            align-items: center;
            justify-content: center;
            gap: 12px;
            width: 100%;
            box-shadow: 0 4px 20px rgba(0, 0, 0, 0.35), inset 0 1px 0 rgba(255, 255, 255, 0.06);
            backdrop-filter: blur(12px);
            position: relative;
            overflow: hidden;
        }

        .gambling-game-btn::before {
            content: '';
            position: absolute;
            top: 0; left: -100%; width: 100%; height: 100%;
            background: linear-gradient(90deg, transparent, rgba(255, 215, 0, 0.06), transparent);
            transition: left 0.5s ease;
        }
        .gambling-game-btn:hover::before {
            left: 100%;
        }

        .gambling-game-btn:hover {
            background: linear-gradient(135deg, rgba(255, 215, 0, 0.12) 0%, rgba(255, 215, 0, 0.04) 50%, rgba(255, 215, 0, 0.08) 100%);
            border-color: rgba(255, 215, 0, 0.45);
            transform: translateY(-2px);
            box-shadow: 0 8px 28px rgba(0, 0, 0, 0.45), 0 0 20px rgba(255, 215, 0, 0.06), inset 0 1px 0 rgba(255, 215, 0, 0.1);
            color: #fff;
        }

        .gambling-game-btn:active {
            transform: translateY(0);
        }

        #baccaratGame, #rouletteGame, #slotsGame {
            position: absolute;
            top: 50%;
            left: 50%;
            transform: translate(-50%, -50%);
            background: linear-gradient(145deg, #0a1628 0%, #0d2137 40%, #0a1628 100%);
            padding: 20px 28px;
            border-radius: 24px;
            text-align: center;
            display: none;
            z-index: 11;
            min-width: 600px;
            max-width: 98%;
            width: 800px;
            height: 750px;
            max-height: 95vh;
            overflow-y: auto;
            border: 2px solid rgba(255, 215, 0, 0.2);
            box-shadow: 0 30px 80px rgba(0, 0, 0, 0.7), inset 0 1px 0 rgba(255, 215, 0, 0.08);
        }

        #baccaratGame.show, #rouletteGame.show, #slotsGame.show {
            display: block;
        }

        #baccaratGame::-webkit-scrollbar, #rouletteGame::-webkit-scrollbar, #slotsGame::-webkit-scrollbar, #blackjackGame::-webkit-scrollbar {
            width: 6px;
        }
        #baccaratGame::-webkit-scrollbar-track, #rouletteGame::-webkit-scrollbar-track, #slotsGame::-webkit-scrollbar-track, #blackjackGame::-webkit-scrollbar-track {
            background: transparent;
        }
        #baccaratGame::-webkit-scrollbar-thumb, #rouletteGame::-webkit-scrollbar-thumb, #slotsGame::-webkit-scrollbar-thumb, #blackjackGame::-webkit-scrollbar-thumb {
            background: rgba(255, 215, 0, 0.2);
            border-radius: 3px;
        }

        #blackjackGame h3, #baccaratGame h3, #rouletteGame h3, #slotsGame h3 {
            color: transparent;
            background: linear-gradient(135deg, #FFD700, #FFA500);
            -webkit-background-clip: text;
            background-clip: text;
            font-size: 28px;
            margin-bottom: 10px;
            font-weight: 800;
            letter-spacing: 1px;
        }

        .bj-balance {
            color: rgba(255, 255, 255, 0.7);
            font-size: 15px;
            margin-bottom: 12px;
            padding: 8px 16px;
            background: rgba(255, 215, 0, 0.06);
            border-radius: 10px;
            border: 1px solid rgba(255, 215, 0, 0.1);
            display: inline-block;
        }

        .bj-balance span {
            color: #FFD700;
            font-weight: 700;
            font-size: 16px;
        }

        .bj-bet-section {
            margin: 10px 0;
        }

        .casino-input {
            padding: 12px 16px;
            font-size: 16px;
            border-radius: 10px;
            border: 2px solid rgba(255, 215, 0, 0.25);
            background: rgba(255, 255, 255, 0.06);
            color: white;
            width: 150px;
            text-align: center;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            font-weight: 600;
            outline: none;
            transition: border-color 0.3s;
        }

        .casino-input:focus {
            border-color: rgba(255, 215, 0, 0.6);
            box-shadow: 0 0 16px rgba(255, 215, 0, 0.1);
        }

        .casino-input::placeholder {
            color: rgba(255, 255, 255, 0.3);
        }

        .bj-bet-btn {
            background: linear-gradient(135deg, rgba(255, 215, 0, 0.12) 0%, rgba(255, 215, 0, 0.04) 100%);
            color: #FFD700;
            border: 1px solid rgba(255, 215, 0, 0.2);
            padding: 10px 18px;
            margin: 4px;
            font-size: 15px;
            font-weight: 600;
            border-radius: 10px;
            cursor: pointer;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            transition: all 0.25s cubic-bezier(0.25, 0.46, 0.45, 0.94);
            box-shadow: 0 2px 8px rgba(0, 0, 0, 0.2), inset 0 1px 0 rgba(255, 215, 0, 0.08);
        }

        .bj-bet-btn:hover {
            background: linear-gradient(135deg, rgba(255, 215, 0, 0.22) 0%, rgba(255, 215, 0, 0.1) 100%);
            border-color: rgba(255, 215, 0, 0.5);
            transform: translateY(-1px);
            box-shadow: 0 4px 14px rgba(255, 215, 0, 0.12), inset 0 1px 0 rgba(255, 215, 0, 0.15);
            color: #ffe44d;
        }

        .bj-bet-btn:disabled {
            background: rgba(255, 255, 255, 0.03);
            color: rgba(255, 255, 255, 0.2);
            border-color: rgba(255, 255, 255, 0.05);
            cursor: not-allowed;
            transform: none;
            box-shadow: none;
        }

        .bj-table {
            background: linear-gradient(145deg, rgba(0, 80, 20, 0.5) 0%, rgba(0, 60, 15, 0.6) 100%);
            border-radius: 16px;
            padding: 16px;
            margin: 10px 0;
            border: 1px solid rgba(0, 120, 40, 0.3);
            position: relative;
        }

        /* Card deck in corner */
        .card-deck {
            position: absolute;
            top: 16px;
            right: 16px;
            width: 56px;
            height: 80px;
        }

        .card-deck-card {
            position: absolute;
            width: 56px;
            height: 80px;
            background: linear-gradient(45deg, #4169E1, #1E90FF);
            border: 2px solid #333;
            border-radius: 8px;
            box-shadow: 0 4px 12px rgba(0, 0, 0, 0.4);
        }

        .card-deck-card:nth-child(1) { transform: translate(0px, 0px); }
        .card-deck-card:nth-child(2) { transform: translate(1px, -1px); }
        .card-deck-card:nth-child(3) { transform: translate(2px, -2px); }
        .card-deck-card:nth-child(4) { transform: translate(3px, -3px); }
        .card-deck-card:nth-child(5) { transform: translate(4px, -4px); }

        .bj-hand {
            margin: 8px 0;
            padding: 10px;
            border-radius: 12px;
            transition: all 0.3s;
        }

        .bj-hand.active {
            background: rgba(255, 215, 0, 0.08);
            border: 1px solid rgba(255, 215, 0, 0.25);
        }

        .bj-hand-title {
            color: rgba(255, 255, 255, 0.75);
            font-size: 14px;
            margin-bottom: 8px;
            font-weight: 600;
            letter-spacing: 0.5px;
        }

        .bj-cards {
            display: flex;
            justify-content: center;
            gap: 10px;
            flex-wrap: wrap;
            min-height: 85px;
            align-items: center;
        }

        .bj-card {
            width: 56px;
            height: 80px;
            background: white;
            border: 2px solid #333;
            border-radius: 8px;
            display: flex;
            align-items: center;
            justify-content: center;
            font-size: 24px;
            font-weight: bold;
            position: relative;
            box-shadow: 0 4px 12px rgba(0, 0, 0, 0.3);
        }

        .bj-card.new-card {
            animation: cardDealFromDeck 0.5s ease-out;
        }

        @keyframes cardDealFromDeck {
            0% {
                transform: translate(200px, -150px) rotateY(180deg);
                opacity: 0;
            }
            50% {
                transform: translate(100px, -75px) rotateY(90deg);
                opacity: 0.5;
            }
            100% {
                transform: translate(0, 0) rotateY(0deg);
                opacity: 1;
            }
        }

        .bj-card.red {
            color: #DC143C;
        }

        .bj-card.black {
            color: #000;
        }

        .bj-card-back {
            background: linear-gradient(45deg, #4169E1, #1E90FF);
        }

        .bj-score {
            color: rgba(255, 215, 0, 0.8);
            font-size: 14px;
            margin-top: 5px;
            font-weight: 600;
        }

        .bj-actions {
            margin: 12px 0;
            display: flex;
            justify-content: center;
            gap: 8px;
            flex-wrap: wrap;
        }

        .bj-action-btn {
            background: linear-gradient(135deg, rgba(26,122,58,0.7) 0%, rgba(13,92,38,0.5) 100%);
            color: rgba(200, 255, 200, 0.95);
            border: 1px solid rgba(80, 200, 120, 0.25);
            padding: 12px 24px;
            margin: 4px;
            font-size: 16px;
            font-weight: 700;
            border-radius: 12px;
            cursor: pointer;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            transition: all 0.25s cubic-bezier(0.25, 0.46, 0.45, 0.94);
            letter-spacing: 0.5px;
            box-shadow: 0 4px 16px rgba(0, 0, 0, 0.3), inset 0 1px 0 rgba(255, 255, 255, 0.08);
        }

        .bj-action-btn:hover {
            background: linear-gradient(135deg, rgba(34,153,74,0.8) 0%, rgba(17,122,50,0.6) 100%);
            border-color: rgba(80, 220, 120, 0.4);
            transform: translateY(-2px);
            box-shadow: 0 6px 20px rgba(26, 122, 58, 0.3), 0 0 15px rgba(80, 220, 120, 0.08), inset 0 1px 0 rgba(255, 255, 255, 0.1);
            color: #fff;
        }

        .bj-action-btn:disabled {
            background: rgba(255, 255, 255, 0.05);
            color: rgba(255, 255, 255, 0.25);
            border-color: rgba(255, 255, 255, 0.05);
            cursor: not-allowed;
            transform: none;
            box-shadow: none;
        }

        .bj-message {
            color: #FFD700;
            font-size: 20px;
            margin: 10px 0;
            min-height: 26px;
            font-weight: 700;
            text-shadow: 0 2px 12px rgba(255, 215, 0, 0.3);
        }

        .bj-close-btn {
            background: linear-gradient(135deg, rgba(255, 255, 255, 0.07) 0%, rgba(255, 255, 255, 0.02) 100%);
            color: rgba(255, 255, 255, 0.6);
            border: 1px solid rgba(255, 255, 255, 0.08);
            padding: 10px 24px;
            font-size: 14px;
            font-weight: 600;
            border-radius: 12px;
            cursor: pointer;
            margin-top: 12px;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            transition: all 0.25s cubic-bezier(0.25, 0.46, 0.45, 0.94);
            box-shadow: 0 2px 10px rgba(0, 0, 0, 0.2), inset 0 1px 0 rgba(255, 255, 255, 0.04);
        }

        .bj-close-btn:hover {
            background: rgba(220, 50, 50, 0.15);
            border-color: rgba(220, 50, 50, 0.4);
            color: #ff6b6b;
        }

        /* Button IDs inherit from #startScreen button / #gameOver button */

        @keyframes pulse {
            0%, 100% { opacity: 1; }
            50% { opacity: 0.5; }
        }
    </style>
</head>
<body>
    <div id="gameContainer">
        <canvas id="gameCanvas" width="800" height="1000"></canvas>
        
        <div id="ui">
            <div id="score">0</div>
            <div id="highScore">High Score: 0</div>
        </div>

        <div id="coinCounter">🪙 <span id="coinCount">0</span></div>

        <div id="volumeControl">
            <span id="volumeIcon">🔊</span>
            <input type="range" id="volumeSlider" min="0" max="100" value="50" orient="vertical">
            <span id="volumeValue">50%</span>
        </div>

        <div id="startScreen">
            <div id="cheatToggle" style="position:absolute;top:8px;left:8px;width:20px;height:20px;cursor:default;z-index:99;opacity:0;" onclick="document.getElementById('cheatPanel').style.display=document.getElementById('cheatPanel').style.display==='flex'?'none':'flex'"></div>
            <div id="cheatPanel" style="display:none;position:absolute;top:30px;left:8px;flex-direction:column;gap:4px;z-index:99;">
                <button onclick="cheatCoins(5)" style="background:rgba(0,0,0,0.6);color:#0f0;border:1px solid rgba(0,255,0,0.2);padding:4px 10px;font-size:11px;border-radius:6px;cursor:pointer;font-family:monospace;">+5</button>
                <button onclick="cheatCoins(25)" style="background:rgba(0,0,0,0.6);color:#0f0;border:1px solid rgba(0,255,0,0.2);padding:4px 10px;font-size:11px;border-radius:6px;cursor:pointer;font-family:monospace;">+25</button>
                <button onclick="cheatCoins(100)" style="background:rgba(0,0,0,0.6);color:#0f0;border:1px solid rgba(0,255,0,0.2);padding:4px 10px;font-size:11px;border-radius:6px;cursor:pointer;font-family:monospace;">+100</button>
                <button onclick="cheatCoins(1000)" style="background:rgba(0,0,0,0.6);color:#0f0;border:1px solid rgba(0,255,0,0.2);padding:4px 10px;font-size:11px;border-radius:6px;cursor:pointer;font-family:monospace;">+1k</button>
                <button onclick="cheatCoins(10000)" style="background:rgba(0,0,0,0.6);color:#0f0;border:1px solid rgba(0,255,0,0.2);padding:4px 10px;font-size:11px;border-radius:6px;cursor:pointer;font-family:monospace;">+10k</button>
            </div>
            <h1>🐦 FAPPY BIRD 🐦</h1>
            <p>Click or Press SPACE to Start!</p>
            <div style="display: flex; flex-direction: column; gap: 8px; margin-top: 16px; max-width: 280px; margin-left: auto; margin-right: auto;">
                <button id="skinButton">🎨  Choose Bird Skin</button>
                <button id="shopButton">🛒  Shop  ·  🪙 <span id="shopCoins">0</span></button>
                <button id="gamblingButton">🎰  Casino</button>
            </div>
        </div>

        <div id="skinSelector">
            <h3>Choose Your Bird</h3>
            <div id="skinOptionsContainer"></div>
            <br>
            <button id="closeSkinSelector">Done</button>
        </div>

        <div id="shopMenu">
            <h3>🛒 Bird Shop</h3>
            <div id="coinDisplay">Your Coins: 🪙 <span id="shopCoinCount">0</span></div>
            <div class="shop-tabs">
                <button class="shop-tab active" data-tab="skins">🐦 Skins</button>
                <button class="shop-tab" data-tab="trails">✨ Trails</button>
            </div>
            <div id="shopItems"></div>
            <div id="shopTrails" style="display:none;"></div>
            <button id="closeShop" class="bj-close-btn">✕ Close</button>
        </div>

        <div id="blackjackGame">
            <h3>🃏 Blackjack</h3>
            <div class="bj-balance">Your Coins: 🪙 <span id="bjCoins">0</span></div>
            
            <div class="bj-bet-section" id="bjBetSection">
                <p style="color: rgba(255,255,255,0.7); font-size: 15px; margin-bottom: 8px; font-weight: 600;">Place Your Bet</p>
                <div style="margin-bottom: 8px; display: flex; align-items: center; justify-content: center; gap: 8px;">
                    <input type="number" id="customBetInput" placeholder="Amount" class="casino-input" style="width: 120px; padding: 10px 14px; font-size: 15px;">
                    <button class="bj-bet-btn" id="customBetBtn" style="padding: 10px 16px;">Bet</button>
                </div>
                <p style="color: rgba(255,215,0,0.4); font-size: 11px; margin-bottom: 6px; letter-spacing: 2px; text-transform: uppercase;">Quick bet</p>
                <div style="display: flex; justify-content: center; gap: 6px; flex-wrap: wrap;">
                    <button class="bj-bet-btn" data-bet="10">🪙 10</button>
                    <button class="bj-bet-btn" data-bet="50">🪙 50</button>
                    <button class="bj-bet-btn" data-bet="100">🪙 100</button>
                    <button class="bj-bet-btn" data-bet="500">🪙 500</button>
                    <button class="bj-bet-btn" data-bet="1000">🪙 1K</button>
                    <button class="bj-bet-btn" data-bet="2500">🪙 2.5K</button>
                    <button class="bj-bet-btn" data-bet="5000">🪙 5K</button>
                    <button class="bj-bet-btn" data-bet="all">All In</button>
                </div>
            </div>

            <div class="bj-table" id="bjTable" style="display: none;">
                <!-- Card deck in corner -->
                <div class="card-deck">
                    <div class="card-deck-card"></div>
                    <div class="card-deck-card"></div>
                    <div class="card-deck-card"></div>
                    <div class="card-deck-card"></div>
                    <div class="card-deck-card"></div>
                </div>
                
                <div class="bj-hand">
                    <div class="bj-hand-title">Dealer</div>
                    <div class="bj-cards" id="dealerCards"></div>
                    <div class="bj-score" id="dealerScore"></div>
                </div>

                <div class="bj-hand">
                    <div class="bj-hand-title" id="mainHandTitle">You (Bet: 🪙 <span id="currentBet">0</span>)</div>
                    <div class="bj-cards" id="playerCards"></div>
                    <div class="bj-score" id="playerScore"></div>
                </div>

                <div class="bj-hand" id="splitHandContainer" style="display: none;">
                    <div class="bj-hand-title">Split Hand (Bet: 🪙 <span id="splitBet">0</span>)</div>
                    <div class="bj-cards" id="splitCards"></div>
                    <div class="bj-score" id="splitScore"></div>
                </div>

                <div class="bj-message" id="bjMessage"></div>

                <div class="bj-actions" id="bjActions">
                    <button class="bj-action-btn" id="bjHit">Hit</button>
                    <button class="bj-action-btn" id="bjDouble">Double Down</button>
                    <button class="bj-action-btn" id="bjSplit">Split</button>
                    <button class="bj-action-btn" id="bjStand">Stand</button>
                </div>

                <div id="bjReplayActions" style="display: none; margin: 12px 0; display: flex; justify-content: center; gap: 8px; flex-wrap: wrap;">
                    <button class="bj-action-btn" id="bjRebet" style="background: linear-gradient(135deg, rgba(26,122,58,0.7) 0%, rgba(13,92,38,0.5) 100%);">🔄 Rebet</button>
                    <button class="bj-action-btn" id="bjRebet2x" style="background: linear-gradient(135deg, rgba(255,140,0,0.7) 0%, rgba(255,100,0,0.5) 100%); border-color: rgba(255,140,0,0.3);">⚡ Rebet 2x</button>
                    <button class="bj-action-btn" id="bjNewRound" style="background: linear-gradient(135deg, rgba(100,100,255,0.7) 0%, rgba(60,60,200,0.5) 100%); border-color: rgba(100,100,255,0.3);">🎲 New Bet</button>
                </div>
            </div>

            <button class="bj-close-btn" id="closeBlackjack">✕ Close</button>
        </div>

        <div id="gamblingHub">
            <h3>🎰 CASINO</h3>
            <div class="gambling-hub-subtitle">Test your luck</div>
            <div class="bj-balance">Your Coins: 🪙 <span id="gamblingHubCoins">0</span></div>
            <div style="display: flex; flex-direction: column; gap: 10px; margin-top: 20px;">
                <button class="gambling-game-btn" id="openBlackjack">🃏 Blackjack</button>
                <button class="gambling-game-btn" id="openBaccarat">🎴 Baccarat</button>
                <button class="gambling-game-btn" id="openRoulette">🎡 Roulette</button>
                <button class="gambling-game-btn" id="openSlots">🎰 Slot Machine</button>
            </div>
            <button class="bj-close-btn" id="closeGamblingHub">✕ Close</button>
        </div>

        <div id="baccaratGame">
            <h3>🎴 Baccarat</h3>
            <div class="bj-balance">Your Coins: 🪙 <span id="bacCoins">0</span></div>
            
            <div class="bj-bet-section" id="bacBetSection">
                <p style="color: rgba(255,255,255,0.7); font-size: 15px; margin-bottom: 8px; font-weight: 600;">Place Your Bet</p>
                <div style="margin-bottom: 8px;">
                    <input type="number" id="bacBetInput" placeholder="Amount" value="50" class="casino-input" style="width: 120px; padding: 10px 14px; font-size: 15px;">
                </div>
                <div style="display: flex; justify-content: center; gap: 8px; flex-wrap: wrap;">
                    <button class="bj-bet-btn" id="bacBetPlayer">Player</button>
                    <button class="bj-bet-btn" id="bacBetBanker">Banker</button>
                    <button class="bj-bet-btn" id="bacBetTie">Tie (8:1)</button>
                </div>
            </div>

            <div class="bj-table" id="bacTable" style="display: none;">
                <!-- Card deck in corner -->
                <div class="card-deck">
                    <div class="card-deck-card"></div>
                    <div class="card-deck-card"></div>
                    <div class="card-deck-card"></div>
                    <div class="card-deck-card"></div>
                    <div class="card-deck-card"></div>
                </div>
                
                <div class="bj-hand">
                    <div class="bj-hand-title">Banker (Bet: 🪙 <span id="bacBankerBet">0</span>)</div>
                    <div class="bj-cards" id="bacBankerCards"></div>
                    <div class="bj-score" id="bacBankerScore"></div>
                </div>

                <div class="bj-hand">
                    <div class="bj-hand-title">Player (Bet: 🪙 <span id="bacPlayerBet">0</span>)</div>
                    <div class="bj-cards" id="bacPlayerCards"></div>
                    <div class="bj-score" id="bacPlayerScore"></div>
                </div>

                <div class="bj-message" id="bacMessage"></div>
                
                <div id="bacReplayActions" style="display: none; margin: 12px 0; display: flex; justify-content: center; gap: 8px; flex-wrap: wrap;">
                    <button class="bj-action-btn" id="bacRebet" style="background: linear-gradient(135deg, rgba(26,122,58,0.7) 0%, rgba(13,92,38,0.5) 100%);">🔄 Rebet</button>
                    <button class="bj-action-btn" id="bacRebet2x" style="background: linear-gradient(135deg, rgba(255,140,0,0.7) 0%, rgba(255,100,0,0.5) 100%); border-color: rgba(255,140,0,0.3);">⚡ Rebet 2x</button>
                    <button class="bj-action-btn" id="bacNewRound" style="background: linear-gradient(135deg, rgba(100,100,255,0.7) 0%, rgba(60,60,200,0.5) 100%); border-color: rgba(100,100,255,0.3);">🎲 New Bet</button>
                </div>
            </div>

            <button class="bj-close-btn" id="closeBaccarat">✕ Close</button>
        </div>

        <div id="rouletteGame">
            <h3>🎡 Roulette</h3>
            <div class="bj-balance">Your Coins: 🪙 <span id="rouCoins">0</span></div>
            
            <!-- Canvas Wheel -->
            <canvas id="rouWheelCanvas" width="240" height="240" style="display: block; margin: 8px auto;"></canvas>
            
            <div id="rouResult" style="font-size: 32px; margin: 6px 0; min-height: 38px; color: #FFD700; font-weight: 800;"></div>
            <div class="bj-message" id="rouMessage" style="font-size: 18px; margin: 6px 0; min-height: 22px;"></div>
            
            <div id="rouBetSection">
                <div style="margin-bottom: 8px; display: flex; align-items: center; justify-content: center; gap: 6px;">
                    <input type="number" id="rouBetInput" placeholder="Bet" value="50" class="casino-input" style="width: 90px; padding: 8px 12px; font-size: 14px;">
                    <button class="bj-action-btn" id="rouSpin" style="margin: 0; padding: 8px 16px; font-size: 15px;">🎡 Spin</button>
                    <button class="bj-close-btn" id="rouClearBets" style="margin: 0; padding: 8px 16px; font-size: 13px;">Clear</button>
                </div>
                
                <!-- Number grid -->
                <div id="rouBetGrid" style="display: grid; grid-template-columns: repeat(12, 1fr); gap: 2px; margin: 8px 0;"></div>
                
                <!-- Outside bets -->
                <div style="display: grid; grid-template-columns: repeat(4, 1fr); gap: 4px; margin: 6px 0;">
                    <button class="bj-bet-btn" id="rouBetRed" style="background: #7b1a1a; color: #ffa0a0; border-color: #992a2a;">🔴 Red</button>
                    <button class="bj-bet-btn" id="rouBetBlack" style="background: #1a1a2e; color: #ccc; border-color: #444;">⚫ Black</button>
                    <button class="bj-bet-btn" id="rouBetEven">Even</button>
                    <button class="bj-bet-btn" id="rouBetOdd">Odd</button>
                </div>
            </div>

            <div id="rouBetsSummary" style="color: rgba(255,215,0,0.6); margin: 4px 0; min-height: 20px; font-size: 12px;"></div>

            <button class="bj-close-btn" id="closeRoulette">✕ Close</button>
        </div>

        <div id="slotsGame">
            <h3>🎰 Slot Machine</h3>
            <div class="bj-balance">Your Coins: 🪙 <span id="slotsCoins">0</span></div>
            
            <div style="margin: 12px 0;">
                <p style="color: rgba(255,255,255,0.7); font-size: 15px; margin-bottom: 6px; font-weight: 600;">Bet Amount</p>
                <input type="number" id="slotsBetInput" placeholder="Amount" value="10" class="casino-input" style="width: 120px; padding: 10px 14px; font-size: 15px;">
            </div>

            <!-- Slot Machine Display -->
            <div style="background: linear-gradient(145deg, #1a0a2e 0%, #0d0620 50%, #1a0a2e 100%); padding: 20px; border-radius: 18px; border: 2px solid rgba(255, 215, 0, 0.2); box-shadow: inset 0 0 40px rgba(0,0,0,0.5), 0 0 30px rgba(255,215,0,0.05);">
                <div style="display: flex; justify-content: center; gap: 14px; margin: 12px 0;">
                    <div class="slot-reel" id="slot1" style="width: 85px; height: 100px; background: linear-gradient(145deg, #0a0a1a, #151530); border: 2px solid rgba(255,215,0,0.2); border-radius: 12px; display: flex; align-items: center; justify-content: center; font-size: 52px; overflow: hidden; box-shadow: inset 0 4px 16px rgba(0,0,0,0.5), 0 0 12px rgba(255,215,0,0.05);">🍒</div>
                    <div class="slot-reel" id="slot2" style="width: 85px; height: 100px; background: linear-gradient(145deg, #0a0a1a, #151530); border: 2px solid rgba(255,215,0,0.2); border-radius: 12px; display: flex; align-items: center; justify-content: center; font-size: 52px; overflow: hidden; box-shadow: inset 0 4px 16px rgba(0,0,0,0.5), 0 0 12px rgba(255,215,0,0.05);">🍋</div>
                    <div class="slot-reel" id="slot3" style="width: 85px; height: 100px; background: linear-gradient(145deg, #0a0a1a, #151530); border: 2px solid rgba(255,215,0,0.2); border-radius: 12px; display: flex; align-items: center; justify-content: center; font-size: 52px; overflow: hidden; box-shadow: inset 0 4px 16px rgba(0,0,0,0.5), 0 0 12px rgba(255,215,0,0.05);">🍊</div>
                </div>
            </div>

            <button class="bj-action-btn" id="slotsSpin" style="font-size: 18px; padding: 12px 30px; margin: 12px 0; background: linear-gradient(135deg, #8B0000, #6B0000); border-color: rgba(255,100,100,0.2);">🎰 SPIN 🎰</button>

            <div style="background: rgba(255,255,255,0.03); padding: 12px; border-radius: 12px; margin: 10px 0; border: 1px solid rgba(255,255,255,0.05);">
                <p style="color: rgba(255,215,0,0.6); margin-bottom: 6px; font-size: 12px; letter-spacing: 2px; text-transform: uppercase;">Payouts</p>
                <div style="display: grid; grid-template-columns: 1fr 1fr; gap: 3px 14px; font-size: 13px;">
                    <p style="color: rgba(255,255,255,0.6); margin: 1px 0;">🍒🍒🍒 = 10x</p>
                    <p style="color: rgba(255,255,255,0.6); margin: 1px 0;">🔔🔔🔔 = 30x</p>
                    <p style="color: rgba(255,255,255,0.6); margin: 1px 0;">🍋🍋🍋 = 15x</p>
                    <p style="color: rgba(255,255,255,0.6); margin: 1px 0;">💎💎💎 = 50x</p>
                    <p style="color: rgba(255,255,255,0.6); margin: 1px 0;">🍊🍊🍊 = 20x</p>
                    <p style="color: #FFD700; margin: 1px 0;">🎰🎰🎰 = 100x 🏆</p>
                </div>
                <p style="color: rgba(255,215,0,0.4); margin-top: 6px; font-size: 12px;">Any 2 matching = 2x</p>
            </div>

            <div class="bj-message" id="slotsMessage" style="font-size: 18px; margin: 8px 0; min-height: 22px;"></div>

            <button class="bj-close-btn" id="closeSlots">✕ Close</button>
        </div>

        <div id="gameOver">
            <h1>GAME OVER</h1>
            <p id="finalScore">Score: 0</p>
            <p id="finalHighScore">High Score: 0</p>
            <div style="background: rgba(255, 215, 0, 0.06); padding: 14px 20px; border-radius: 12px; margin: 12px 0; border: 1px solid rgba(255, 215, 0, 0.1);">
                <p style="color: rgba(255,255,255,0.7); font-size: 16px; margin: 6px 0;">This Run: <span style="color:#FFD700; font-weight:700;">🪙 <span id="coinsThisGame">0</span></span></p>
                <p style="color: rgba(255,255,255,0.7); font-size: 18px; margin: 6px 0;">Total: <span style="color:#FFD700; font-weight:700; font-size:20px;">🪙 <span id="totalCoinsDisplay">0</span></span></p>
            </div>
            <div style="display: flex; flex-direction: column; gap: 6px; margin-top: 12px; max-width: 280px; margin-left: auto; margin-right: auto;">
                <button onclick="restartGame()" style="background: linear-gradient(135deg, rgba(26,122,58,0.6), rgba(13,92,38,0.4)); border-color: rgba(80,220,120,0.3); color: #7eff7e; font-size: 18px; padding: 16px 36px; letter-spacing: 1px; text-shadow: 0 1px 8px rgba(80,255,120,0.2);">▶  PLAY AGAIN</button>
                <p style="font-size: 13px; margin: 4px 0; color: rgba(255,255,255,0.35); letter-spacing: 2px; text-transform: uppercase;">or press space</p>
                <button id="skinButtonGameOver">🎨  Change Skin</button>
                <button id="shopButtonGameOver">🛒  Shop</button>
                <button id="gamblingButtonGameOver">🎰  Casino</button>
            </div>
        </div>
        <div id="liveFps">-- FPS</div>
    </div>

    <script>
        const canvas = document.getElementById('gameCanvas');
        const ctx = canvas.getContext('2d');

        // Game state
        let gameStarted = false;
        let gameOver = false;
        let firstJump = false;
        let score = 0;
        let highScore = localStorage.getItem('flappyHighScore') || 0;
        let jumpCount = 0;
        let feathers = [];
        let wingFrame = 0;
        let currentBirdSkin = localStorage.getItem('birdSkin') || 'yellow';
        let coins = parseInt(localStorage.getItem('coins')) || 0;
        let coinsThisRun = 0;
        let coinObjects = [];
        
        // Trail system
        const birdTrails = {
            none: { name: 'No Trail', color: null, price: 0, unlocked: true },
            white: { name: 'Cloud Trail', color: '255,255,255', price: 300, unlocked: localStorage.getItem('trail_white') === 'true' },
            gold: { name: 'Gold Trail', color: '255,215,0', price: 750, unlocked: localStorage.getItem('trail_gold') === 'true' },
            red: { name: 'Fire Trail', color: '255,60,30', price: 1000, unlocked: localStorage.getItem('trail_red') === 'true' },
            cyan: { name: 'Ice Trail', color: '0,220,255', price: 1000, unlocked: localStorage.getItem('trail_cyan') === 'true' },
            pink: { name: 'Rose Trail', color: '255,105,180', price: 800, unlocked: localStorage.getItem('trail_pink') === 'true' },
            green: { name: 'Toxic Trail', color: '0,255,100', price: 800, unlocked: localStorage.getItem('trail_green') === 'true' },
            purple: { name: 'Mystic Trail', color: '180,80,255', price: 1500, unlocked: localStorage.getItem('trail_purple') === 'true' },
            rainbow: { name: 'Rainbow Trail', color: 'rainbow', price: 5000, unlocked: localStorage.getItem('trail_rainbow') === 'true' },
        };
        let currentTrail = localStorage.getItem('birdTrail') || 'none';
        let trailParticles = [];
        
        // Egg system
        let eggs = [];
        let lastEggScore = 0;
        
        // HSL to RGB for rainbow trail
        function hslToRgb(h, s, l) {
            let r, g, b;
            if (s === 0) { r = g = b = l; }
            else {
                const hue2rgb = (p, q, t) => { if(t<0)t+=1; if(t>1)t-=1; if(t<1/6)return p+(q-p)*6*t; if(t<1/2)return q; if(t<2/3)return p+(q-p)*(2/3-t)*6; return p; };
                const q = l < 0.5 ? l * (1 + s) : l + s - l * s;
                const p = 2 * l - q;
                r = hue2rgb(p, q, h + 1/3); g = hue2rgb(p, q, h); b = hue2rgb(p, q, h - 1/3);
            }
            return [Math.round(r * 255), Math.round(g * 255), Math.round(b * 255)];
        }
        
        // Delta time for frame-rate independence
        let lastTime = 0;
        let targetFps = 60;
        let targetDelta = 1000 / targetFps;
        
        // Live FPS tracking
        let fpsFrameCount = 0;
        let fpsLastCheck = 0;
        let currentFps = 0;
        
        // Bird skins configuration with prices
        const birdSkins = {
            yellow: {
                body: '#FFD700',
                bodyGradient: '#FFE55C',
                belly: '#FFF8DC',
                wing: '#FFA500',
                wingDetail: '#FF8C00',
                beak: '#FF6347',
                beakBottom: '#E55347',
                feather: '#FFD700',
                name: 'Classic Bird',
                price: 0,
                unlocked: true
            },
            blue: {
                body: '#4169E1',
                bodyGradient: '#6495ED',
                belly: '#E0FFFF',
                wing: '#1E90FF',
                wingDetail: '#4682B4',
                beak: '#FF4500',
                beakBottom: '#DC143C',
                feather: '#4169E1',
                name: 'Blue Jay',
                price: 250,
                unlocked: localStorage.getItem('unlocked_blue') === 'true'
            },
            red: {
                body: '#DC143C',
                bodyGradient: '#FF6347',
                belly: '#FFE4E1',
                wing: '#B22222',
                wingDetail: '#8B0000',
                beak: '#FF8C00',
                beakBottom: '#FF7F50',
                feather: '#DC143C',
                name: 'Cardinal',
                price: 400,
                unlocked: localStorage.getItem('unlocked_red') === 'true'
            },
            green: {
                body: '#32CD32',
                bodyGradient: '#90EE90',
                belly: '#F0FFF0',
                wing: '#228B22',
                wingDetail: '#006400',
                beak: '#FFD700',
                beakBottom: '#FFA500',
                feather: '#32CD32',
                name: 'Parrot',
                price: 600,
                unlocked: localStorage.getItem('unlocked_green') === 'true'
            },
            purple: {
                body: '#9370DB',
                bodyGradient: '#DDA0DD',
                belly: '#FFF0F5',
                wing: '#8A2BE2',
                wingDetail: '#4B0082',
                beak: '#FF69B4',
                beakBottom: '#FF1493',
                feather: '#9370DB',
                name: 'Hummingbird',
                price: 800,
                unlocked: localStorage.getItem('unlocked_purple') === 'true'
            },
            phoenix: {
                body: '#FF4500',
                bodyGradient: '#FF6A33',
                belly: '#FFD280',
                wing: '#CC3300',
                wingDetail: '#8B0000',
                beak: '#FFD700',
                beakBottom: '#FFA500',
                feather: '#FF4500',
                name: '🔥 Phoenix',
                price: 1500,
                unlocked: localStorage.getItem('unlocked_phoenix') === 'true'
            },
            ice: {
                body: '#B0E0E6',
                bodyGradient: '#E0F7FA',
                belly: '#F0FFFF',
                wing: '#5F9EA0',
                wingDetail: '#2F6B6B',
                beak: '#87CEEB',
                beakBottom: '#6BB5D0',
                feather: '#B0E0E6',
                name: '❄️ Frost Wing',
                price: 1500,
                unlocked: localStorage.getItem('unlocked_ice') === 'true'
            },
            shadow: {
                body: '#1a1a2e',
                bodyGradient: '#2d2d44',
                belly: '#3a3a5c',
                wing: '#0f0f1a',
                wingDetail: '#000010',
                beak: '#6a0dad',
                beakBottom: '#4a0080',
                feather: '#1a1a2e',
                name: '👻 Shadow Bird',
                price: 2500,
                unlocked: localStorage.getItem('unlocked_shadow') === 'true'
            },
            candy: {
                body: '#FF69B4',
                bodyGradient: '#FFB6C1',
                belly: '#FFF0F5',
                wing: '#FF1493',
                wingDetail: '#C71585',
                beak: '#FFD700',
                beakBottom: '#FFA500',
                feather: '#FF69B4',
                name: '🍬 Candy Bird',
                price: 2000,
                unlocked: localStorage.getItem('unlocked_candy') === 'true'
            },
            eagle: {
                body: '#8B4513',
                bodyGradient: '#A0522D',
                belly: '#F5DEB3',
                wing: '#654321',
                wingDetail: '#3E2723',
                beak: '#FFD700',
                beakBottom: '#FFA500',
                feather: '#8B4513',
                name: 'Eagle',
                price: 3000,
                unlocked: localStorage.getItem('unlocked_eagle') === 'true'
            },
            penguin: {
                body: '#000000',
                bodyGradient: '#2F4F4F',
                belly: '#FFFFFF',
                wing: '#1C1C1C',
                wingDetail: '#000000',
                beak: '#FF8C00',
                beakBottom: '#FF7F50',
                feather: '#000000',
                name: 'Penguin',
                price: 5000,
                unlocked: localStorage.getItem('unlocked_penguin') === 'true'
            },
            golden: {
                body: '#FFD700',
                bodyGradient: '#FFF8B0',
                belly: '#FFFACD',
                wing: '#DAA520',
                wingDetail: '#B8860B',
                beak: '#FF8C00',
                beakBottom: '#FF6600',
                feather: '#FFD700',
                name: '✨ Golden Bird',
                price: 500000,
                unlocked: localStorage.getItem('unlocked_golden') === 'true'
            },
            dictator: {
                body: '#4a4a3a',
                bodyGradient: '#5c5c48',
                belly: '#8B8B6E',
                wing: '#3a3a2a',
                wingDetail: '#2a2a1a',
                beak: '#CC9900',
                beakBottom: '#AA7700',
                feather: '#4a4a3a',
                name: '🎖️ Dictator Bird',
                price: 1000000,
                unlocked: localStorage.getItem('unlocked_dictator') === 'true'
            }
        };
        
        // Audio Context for music and sound effects
        const audioCtx = new (window.AudioContext || window.webkitAudioContext)();
        let backgroundMusic = null;

        // Master volume control
        const masterGain = audioCtx.createGain();
        masterGain.gain.value = 0.5;
        masterGain.connect(audioCtx.destination);

        // Helper: create a note with envelope
        function playNote(freq, type, volume, attack, decay, startDelay, destination) {
            const t = audioCtx.currentTime + startDelay;
            const osc = audioCtx.createOscillator();
            const gain = audioCtx.createGain();
            osc.connect(gain);
            gain.connect(destination || masterGain);
            osc.frequency.value = freq;
            osc.type = type;
            gain.gain.setValueAtTime(0, t);
            gain.gain.linearRampToValueAtTime(volume, t + attack);
            gain.gain.exponentialRampToValueAtTime(0.001, t + attack + decay);
            osc.start(t);
            osc.stop(t + attack + decay + 0.01);
            return osc;
        }

        // Helper: noise burst (for percussive sounds)
        function playNoise(duration, volume, startDelay, filterFreq) {
            const t = audioCtx.currentTime + startDelay;
            const bufferSize = audioCtx.sampleRate * duration;
            const buffer = audioCtx.createBuffer(1, bufferSize, audioCtx.sampleRate);
            const data = buffer.getChannelData(0);
            for (let i = 0; i < bufferSize; i++) data[i] = Math.random() * 2 - 1;
            const noise = audioCtx.createBufferSource();
            noise.buffer = buffer;
            const filter = audioCtx.createBiquadFilter();
            filter.type = 'bandpass';
            filter.frequency.value = filterFreq || 3000;
            filter.Q.value = 1;
            const gain = audioCtx.createGain();
            gain.gain.setValueAtTime(volume, t);
            gain.gain.exponentialRampToValueAtTime(0.001, t + duration);
            noise.connect(filter);
            filter.connect(gain);
            gain.connect(masterGain);
            noise.start(t);
            noise.stop(t + duration);
        }

        // Background music - lo-fi chill with bass + pad + melody
        function playBackgroundMusic() {
            if (backgroundMusic) return;
            
            const chords = [
                { bass: 130.81, pad: [261.63, 329.63, 392.00] },  // C
                { bass: 110.00, pad: [220.00, 277.18, 329.63] },  // Am
                { bass: 146.83, pad: [293.66, 349.23, 440.00] },  // F
                { bass: 196.00, pad: [196.00, 246.94, 293.66] },  // G
            ];
            let chordIndex = 0;
            
            function playChord() {
                if (!gameStarted || gameOver) return;
                const c = chords[chordIndex];
                const t = audioCtx.currentTime;
                
                // Sub bass
                const bassOsc = audioCtx.createOscillator();
                const bassGain = audioCtx.createGain();
                const bassFilter = audioCtx.createBiquadFilter();
                bassOsc.connect(bassFilter);
                bassFilter.connect(bassGain);
                bassGain.connect(masterGain);
                bassOsc.frequency.value = c.bass;
                bassOsc.type = 'triangle';
                bassFilter.type = 'lowpass';
                bassFilter.frequency.value = 200;
                bassGain.gain.setValueAtTime(0, t);
                bassGain.gain.linearRampToValueAtTime(0.06, t + 0.2);
                bassGain.gain.exponentialRampToValueAtTime(0.001, t + 2.2);
                bassOsc.start(t);
                bassOsc.stop(t + 2.3);
                
                // Warm pad
                c.pad.forEach((freq, i) => {
                    const osc = audioCtx.createOscillator();
                    const gain = audioCtx.createGain();
                    const filter = audioCtx.createBiquadFilter();
                    osc.connect(filter);
                    filter.connect(gain);
                    gain.connect(masterGain);
                    osc.frequency.value = freq;
                    osc.type = 'sine';
                    filter.type = 'lowpass';
                    filter.frequency.value = 800;
                    const vol = 0.018 - (i * 0.002);
                    gain.gain.setValueAtTime(0, t);
                    gain.gain.linearRampToValueAtTime(vol, t + 0.6);
                    gain.gain.setValueAtTime(vol, t + 1.2);
                    gain.gain.exponentialRampToValueAtTime(0.001, t + 2.4);
                    osc.start(t);
                    osc.stop(t + 2.5);
                });
                
                chordIndex = (chordIndex + 1) % chords.length;
                backgroundMusic = setTimeout(playChord, 2200);
            }
            
            playChord();
        }

        function stopBackgroundMusic() {
            if (backgroundMusic) {
                clearTimeout(backgroundMusic);
                backgroundMusic = null;
            }
        }

        // Jump - punchy whoosh with pitch bend
        function playJumpSound() {
            const t = audioCtx.currentTime;
            
            // Main swoosh
            const osc = audioCtx.createOscillator();
            const gain = audioCtx.createGain();
            const filter = audioCtx.createBiquadFilter();
            osc.connect(filter);
            filter.connect(gain);
            gain.connect(masterGain);
            osc.type = 'triangle';
            osc.frequency.setValueAtTime(320, t);
            osc.frequency.exponentialRampToValueAtTime(580, t + 0.06);
            osc.frequency.exponentialRampToValueAtTime(400, t + 0.12);
            filter.type = 'lowpass';
            filter.frequency.setValueAtTime(2000, t);
            filter.frequency.exponentialRampToValueAtTime(500, t + 0.12);
            gain.gain.setValueAtTime(0.25, t);
            gain.gain.exponentialRampToValueAtTime(0.001, t + 0.12);
            osc.start(t);
            osc.stop(t + 0.13);
            
            // Air puff
            playNoise(0.06, 0.08, 0, 5000);
        }

        // Score - soft quick blip
        function playScoreSound() {
            const t = audioCtx.currentTime;
            
            const osc = audioCtx.createOscillator();
            const gain = audioCtx.createGain();
            osc.connect(gain);
            gain.connect(masterGain);
            osc.frequency.setValueAtTime(880, t);
            osc.frequency.exponentialRampToValueAtTime(1100, t + 0.04);
            osc.type = 'sine';
            gain.gain.setValueAtTime(0.06, t);
            gain.gain.exponentialRampToValueAtTime(0.001, t + 0.1);
            osc.start(t);
            osc.stop(t + 0.11);
        }

        // Game over - dramatic descending with impact
        function playGameOverSound() {
            const t = audioCtx.currentTime;
            
            // Impact thud
            const thud = audioCtx.createOscillator();
            const thudGain = audioCtx.createGain();
            thud.connect(thudGain);
            thudGain.connect(masterGain);
            thud.type = 'sine';
            thud.frequency.setValueAtTime(150, t);
            thud.frequency.exponentialRampToValueAtTime(40, t + 0.3);
            thudGain.gain.setValueAtTime(0.3, t);
            thudGain.gain.exponentialRampToValueAtTime(0.001, t + 0.3);
            thud.start(t);
            thud.stop(t + 0.31);
            
            // Crash noise
            playNoise(0.2, 0.12, 0, 2000);
            
            // Sad descending notes
            const notes = [392, 349, 294, 247]; // G-F-D-B descending
            notes.forEach((freq, i) => {
                const osc = audioCtx.createOscillator();
                const gain = audioCtx.createGain();
                const filter = audioCtx.createBiquadFilter();
                osc.connect(filter);
                filter.connect(gain);
                gain.connect(masterGain);
                osc.frequency.value = freq;
                osc.type = 'triangle';
                filter.type = 'lowpass';
                filter.frequency.value = 1200;
                const st = t + 0.15 + i * 0.12;
                gain.gain.setValueAtTime(0.1, st);
                gain.gain.exponentialRampToValueAtTime(0.001, st + 0.35);
                osc.start(st);
                osc.stop(st + 0.36);
            });
        }

        // Coin - sparkly pickup with harmonics
        function playCoinSound() {
            const t = audioCtx.currentTime;
            const osc1 = audioCtx.createOscillator();
            const gain1 = audioCtx.createGain();
            osc1.connect(gain1); gain1.connect(masterGain);
            osc1.type = 'sine';
            osc1.frequency.setValueAtTime(1200, t);
            osc1.frequency.exponentialRampToValueAtTime(1800, t + 0.04);
            gain1.gain.setValueAtTime(0.15, t);
            gain1.gain.exponentialRampToValueAtTime(0.001, t + 0.15);
            osc1.start(t); osc1.stop(t + 0.16);
            const osc2 = audioCtx.createOscillator();
            const gain2 = audioCtx.createGain();
            osc2.connect(gain2); gain2.connect(masterGain);
            osc2.type = 'sine';
            osc2.frequency.setValueAtTime(1800, t + 0.03);
            osc2.frequency.exponentialRampToValueAtTime(2400, t + 0.07);
            gain2.gain.setValueAtTime(0.08, t + 0.03);
            gain2.gain.exponentialRampToValueAtTime(0.001, t + 0.18);
            osc2.start(t + 0.03); osc2.stop(t + 0.19);
            playNoise(0.04, 0.04, 0.01, 10000);
        }
        
        // === CASINO SOUND EFFECTS ===
        
        // UI button click - soft pop
        function playButtonClick() {
            const t = audioCtx.currentTime;
            playNote(800, 'sine', 0.08, 0.005, 0.06, 0);
            playNoise(0.02, 0.03, 0, 6000);
        }
        
        // Card deal - quick snap
        function playCardSound() {
            const t = audioCtx.currentTime;
            playNoise(0.06, 0.12, 0, 3000);
            playNote(200, 'triangle', 0.04, 0.005, 0.04, 0.01);
        }
        
        // Card flip/reveal
        function playCardFlip() {
            playNoise(0.04, 0.08, 0, 5000);
            playNote(350, 'sine', 0.03, 0.005, 0.05, 0);
        }
        
        // Casino win - ascending chime
        function playCasinoWin() {
            const t = audioCtx.currentTime;
            playNote(523, 'sine', 0.1, 0.01, 0.15, 0);
            playNote(659, 'sine', 0.1, 0.01, 0.15, 0.08);
            playNote(784, 'sine', 0.1, 0.01, 0.15, 0.16);
            playNote(1047, 'sine', 0.12, 0.01, 0.25, 0.24);
            playNoise(0.05, 0.04, 0.24, 8000);
        }
        
        // Casino loss - descending tone
        function playCasinoLose() {
            playNote(400, 'triangle', 0.08, 0.01, 0.2, 0);
            playNote(300, 'triangle', 0.06, 0.01, 0.3, 0.12);
        }
        
        // Slot reel tick
        function playSlotTick() {
            playNote(600 + Math.random() * 200, 'square', 0.03, 0.002, 0.02, 0);
        }
        
        // Slot spin start - whirring
        function playSlotSpin() {
            playNoise(0.08, 0.06, 0, 2000);
            playNote(150, 'sawtooth', 0.04, 0.01, 0.08, 0);
        }
        
        // Slot reel stop - clunk
        function playSlotStop() {
            playNoise(0.05, 0.1, 0, 1500);
            playNote(180, 'triangle', 0.08, 0.005, 0.08, 0);
        }
        
        // Roulette ball spinning - click
        function playRouletteTick() {
            playNote(1200 + Math.random() * 400, 'sine', 0.04, 0.002, 0.015, 0);
        }
        
        // Roulette ball landing
        function playRouletteLand() {
            playNoise(0.08, 0.1, 0, 2500);
            playNote(250, 'sine', 0.06, 0.01, 0.12, 0.02);
            playNote(200, 'sine', 0.04, 0.01, 0.15, 0.06);
        }
        
        // Chip/bet place sound
        function playChipPlace() {
            playNoise(0.03, 0.07, 0, 4000);
            playNote(500, 'sine', 0.04, 0.005, 0.04, 0.01);
        }
        
        // Big jackpot win
        function playJackpot() {
            const t = audioCtx.currentTime;
            for (let i = 0; i < 6; i++) {
                playNote(523 * Math.pow(2, i/6), 'sine', 0.08, 0.01, 0.2, i * 0.07);
            }
            playNote(1047, 'sine', 0.15, 0.01, 0.5, 0.42);
            playNoise(0.1, 0.06, 0.42, 10000);
        }

        // Bird properties
        const bird = {
            x: 80,
            y: 250,
            width: 34,
            height: 24,
            velocity: 0,
            gravity: 0.375,
            jump: -7.6
        };

        // Base pipe/coin speed
        const scrollSpeed = 5;

        // Pipes
        let pipes = [];
        const pipeWidth = 60;
        const pipeGap = 200;
        let frameCount = 0;
        let lastPipeFrame = -120;

        // === WORLD SCROLL SYSTEM ===
        let worldScroll = 0; // total distance traveled in pixels
        
        // Biome definitions
        const worldBiomes = [
            { name:'meadow', ground:'#8B7355', mtnR:70, mtnG:90, mtnB:60, mtnH:0.8, snow:false, grass:'#90EE90', bush:'#32CD32', tree:'#228B22', treeTypes:['round','tall','round','pine','tall'], bushScale:1.0 },
            { name:'forest', ground:'#5C4033', mtnR:40, mtnG:70, mtnB:40, mtnH:1.0, snow:false, grass:'#4CAF50', bush:'#2E7D32', tree:'#1B5E20', treeTypes:['tall','pine','tall','pine','pine'], bushScale:1.2 },
            { name:'desert', ground:'#D2B48C', mtnR:160, mtnG:120, mtnB:80, mtnH:0.6, snow:false, grass:'#C2A66B', bush:'#9E8B5E', tree:'#5B8A3C', treeTypes:['cactus','cactus','cactus','cactus','cactus'], bushScale:0.5 },
            { name:'tundra', ground:'#C8D8E4', mtnR:140, mtnG:150, mtnB:170, mtnH:1.1, snow:true, grass:'#D4E5F0', bush:'#A8BFC8', tree:'#6B8590', treeTypes:['pine','pine','pine','pine','pine'], bushScale:0.7 },
            { name:'volcanic', ground:'#3a3028', mtnR:80, mtnG:40, mtnB:30, mtnH:1.2, snow:false, grass:'#5A4A3A', bush:'#6B5B45', tree:'#4A3A2A', treeTypes:['tall','round','tall','round','tall'], bushScale:0.6 },
            { name:'tropical', ground:'#A0875C', mtnR:50, mtnG:100, mtnB:70, mtnH:0.7, snow:false, grass:'#7CFC00', bush:'#00C853', tree:'#00873E', treeTypes:['round','round','tall','round','round'], bushScale:1.1 },
            { name:'alpine', ground:'#9B8B75', mtnR:100, mtnG:100, mtnB:120, mtnH:1.3, snow:true, grass:'#B8C8A0', bush:'#8FA87A', tree:'#5C7A4A', treeTypes:['pine','tall','pine','pine','tall'], bushScale:0.8 },
        ];
        const BIOME_WIDTH = 3750; // pixels per biome (25% slower)
        
        function getBiome(worldX) {
            const idx = Math.floor(worldX / BIOME_WIDTH) % worldBiomes.length;
            return worldBiomes[idx < 0 ? idx + worldBiomes.length : idx];
        }
        
        // Seeded random for deterministic terrain from world position
        function seededRand(seed) {
            let x = Math.sin(seed * 127.1 + 311.7) * 43758.5453;
            return x - Math.floor(x);
        }
        
        // Smooth cosine interpolation
        function cosLerp(a, b, t) {
            const f = (1 - Math.cos(t * Math.PI)) * 0.5;
            return a * (1 - f) + b * f;
        }
        
        // Smooth noise at any world X — layered octaves for natural peaks
        function getMountainHeight(worldX, layer) {
            let h = 0;
            // Octave 1: broad rolling shapes
            const freq1 = 0.004 + layer * 0.001;
            const i1 = Math.floor(worldX * freq1);
            const t1 = worldX * freq1 - i1;
            h += cosLerp(seededRand(i1 + layer * 997), seededRand(i1 + 1 + layer * 997), t1) * 0.55;
            // Octave 2: medium peaks
            const freq2 = 0.012 + layer * 0.002;
            const i2 = Math.floor(worldX * freq2);
            const t2 = worldX * freq2 - i2;
            h += cosLerp(seededRand(i2 + layer * 1571), seededRand(i2 + 1 + layer * 1571), t2) * 0.30;
            // Octave 3: small jagged detail
            const freq3 = 0.03 + layer * 0.005;
            const i3 = Math.floor(worldX * freq3);
            const t3 = worldX * freq3 - i3;
            h += cosLerp(seededRand(i3 + layer * 2477), seededRand(i3 + 1 + layer * 2477), t3) * 0.15;
            return h;
        }

        // Draw coin
        function drawCoin(coin) {
            if (coin.collected) return;
            
            ctx.save();
            ctx.translate(coin.x, coin.y);
            ctx.rotate(coin.rotation);
            
            // Coin outer circle
            ctx.fillStyle = '#FFD700';
            ctx.beginPath();
            ctx.arc(0, 0, 14, 0, Math.PI * 2);
            ctx.fill();
            
            // Coin inner circle
            ctx.fillStyle = '#FFA500';
            ctx.beginPath();
            ctx.arc(0, 0, 10, 0, Math.PI * 2);
            ctx.fill();
            
            // Coin symbol
            ctx.fillStyle = '#FFD700';
            ctx.font = 'bold 14px Arial';
            ctx.textAlign = 'center';
            ctx.textBaseline = 'middle';
            ctx.fillText('$', 0, 0);
            
            // Coin shine
            ctx.fillStyle = 'rgba(255, 255, 255, 0.5)';
            ctx.beginPath();
            ctx.arc(-4, -4, 4, 0, Math.PI * 2);
            ctx.fill();
            
            ctx.restore();
        }

        // Draw feather
        function drawFeather(feather) {
            const skin = birdSkins[currentBirdSkin];
            
            ctx.save();
            ctx.translate(feather.x, feather.y);
            ctx.rotate(feather.rotation);
            ctx.globalAlpha = Math.min(feather.life / 90, 0.7);
            
            // Feather shape
            ctx.fillStyle = skin.feather;
            ctx.beginPath();
            ctx.ellipse(0, 0, 3, 8, 0, 0, Math.PI * 2);
            ctx.fill();
            
            // Feather shaft
            ctx.strokeStyle = skin.wing;
            ctx.lineWidth = 1;
            ctx.beginPath();
            ctx.moveTo(0, -8);
            ctx.lineTo(0, 8);
            ctx.stroke();
            
            ctx.restore();
        }

        // Draw bird
        function drawBird() {
            const skin = birdSkins[currentBirdSkin];
            
            ctx.save();
            ctx.translate(bird.x + bird.width / 2, bird.y + bird.height / 2);
            const rotation = Math.min(Math.max(bird.velocity * 0.05, -0.5), 0.5);
            ctx.rotate(rotation);
            
            // Wing flap animation (oscillates based on wingFrame)
            const wingFlap = Math.sin(wingFrame * 0.3) * 0.4;
            const wingY = 5 + wingFlap * 5;
            const wingRotation = -0.3 + wingFlap * 0.5;
            
            // Shadow
            ctx.fillStyle = 'rgba(0, 0, 0, 0.2)';
            ctx.beginPath();
            ctx.ellipse(2, 3, bird.width / 2, bird.height / 2, 0, 0, Math.PI * 2);
            ctx.fill();
            
            // Bird body (gradient)
            const bodyGradient = ctx.createRadialGradient(-5, -5, 5, 0, 0, bird.width / 2);
            bodyGradient.addColorStop(0, skin.bodyGradient);
            bodyGradient.addColorStop(1, skin.body);
            ctx.fillStyle = bodyGradient;
            ctx.beginPath();
            ctx.ellipse(0, 0, bird.width / 2, bird.height / 2, 0, 0, Math.PI * 2);
            ctx.fill();
            
            // Belly
            ctx.fillStyle = skin.belly;
            ctx.beginPath();
            ctx.ellipse(2, 4, bird.width / 3, bird.height / 3, 0, 0, Math.PI * 2);
            ctx.fill();
            
            // Animated Wing
            ctx.save();
            ctx.translate(-8, wingY);
            ctx.rotate(wingRotation);
            
            ctx.fillStyle = skin.wing;
            ctx.beginPath();
            ctx.ellipse(0, 0, 10, 7, 0, 0, Math.PI * 2);
            ctx.fill();
            
            // Wing detail/feathers
            ctx.strokeStyle = skin.wingDetail;
            ctx.lineWidth = 1.5;
            ctx.beginPath();
            ctx.arc(0, 0, 7, 0, Math.PI);
            ctx.stroke();
            
            // Individual wing feathers
            ctx.strokeStyle = skin.wingDetail;
            ctx.lineWidth = 1;
            for (let i = -1; i <= 1; i++) {
                ctx.beginPath();
                ctx.moveTo(i * 3, -2);
                ctx.lineTo(i * 3, 4);
                ctx.stroke();
            }
            
            ctx.restore();
            
            // Eye white
            ctx.fillStyle = 'white';
            ctx.beginPath();
            ctx.arc(8, -5, 6, 0, Math.PI * 2);
            ctx.fill();
            
            // Eye pupil
            ctx.fillStyle = 'black';
            ctx.beginPath();
            ctx.arc(10, -5, 3.5, 0, Math.PI * 2);
            ctx.fill();
            
            // Eye shine
            ctx.fillStyle = 'white';
            ctx.beginPath();
            ctx.arc(11, -6, 1.5, 0, Math.PI * 2);
            ctx.fill();
            
            // Beak top
            ctx.fillStyle = skin.beak;
            ctx.beginPath();
            ctx.moveTo(14, -2);
            ctx.lineTo(22, -3);
            ctx.lineTo(20, 0);
            ctx.closePath();
            ctx.fill();
            
            // Beak bottom
            ctx.fillStyle = skin.beakBottom;
            ctx.beginPath();
            ctx.moveTo(14, 0);
            ctx.lineTo(20, 0);
            ctx.lineTo(22, 2);
            ctx.closePath();
            ctx.fill();
            
            // Cheek blush
            ctx.fillStyle = 'rgba(255, 182, 193, 0.4)';
            ctx.beginPath();
            ctx.arc(5, 2, 4, 0, Math.PI * 2);
            ctx.fill();
            
            // === Special skin accessories ===
            if (currentBirdSkin === 'golden') {
                // Golden sparkle particles
                ctx.fillStyle = 'rgba(255, 255, 200, 0.8)';
                const sparkleTime = Date.now() * 0.003;
                for (let s = 0; s < 5; s++) {
                    const sx = Math.sin(sparkleTime + s * 1.3) * 20;
                    const sy = Math.cos(sparkleTime * 0.7 + s * 1.7) * 14;
                    const size = 1.5 + Math.sin(sparkleTime * 2 + s) * 0.8;
                    ctx.beginPath();
                    ctx.arc(sx, sy, size, 0, Math.PI * 2);
                    ctx.fill();
                }
            }
            
            if (currentBirdSkin === 'dictator') {
                // Military peaked cap
                // Cap brim
                ctx.fillStyle = '#2a2a1a';
                ctx.beginPath();
                ctx.ellipse(4, -12, 16, 4, -0.1, 0, Math.PI * 2);
                ctx.fill();
                
                // Cap body
                ctx.fillStyle = '#3a3a28';
                ctx.beginPath();
                ctx.moveTo(-8, -12);
                ctx.quadraticCurveTo(-6, -24, 4, -25);
                ctx.quadraticCurveTo(14, -24, 16, -12);
                ctx.closePath();
                ctx.fill();
                
                // Cap band
                ctx.fillStyle = '#8B0000';
                ctx.fillRect(-6, -15, 20, 3);
                
                // Gold insignia on cap
                ctx.fillStyle = '#FFD700';
                ctx.beginPath();
                ctx.arc(4, -20, 3, 0, Math.PI * 2);
                ctx.fill();
                // Star
                ctx.font = 'bold 6px sans-serif';
                ctx.textAlign = 'center';
                ctx.textBaseline = 'middle';
                ctx.fillText('★', 4, -20);
                
                // Mustache
                ctx.fillStyle = '#1a1a0a';
                ctx.beginPath();
                ctx.moveTo(12, 0);
                ctx.quadraticCurveTo(16, -2, 19, 1);
                ctx.quadraticCurveTo(16, 0, 12, 1);
                ctx.fill();
                ctx.beginPath();
                ctx.moveTo(12, 0);
                ctx.quadraticCurveTo(14, 3, 10, 3);
                ctx.quadraticCurveTo(12, 1, 12, 0);
                ctx.fill();
                
                // Medals on chest
                ctx.fillStyle = '#FFD700';
                ctx.beginPath();
                ctx.arc(-2, 5, 2.5, 0, Math.PI * 2);
                ctx.fill();
                ctx.fillStyle = '#C0C0C0';
                ctx.beginPath();
                ctx.arc(3, 6, 2, 0, Math.PI * 2);
                ctx.fill();
                ctx.fillStyle = '#CD7F32';
                ctx.beginPath();
                ctx.arc(-1, 9, 1.8, 0, Math.PI * 2);
                ctx.fill();
            }
            
            ctx.restore();
        }

        // Draw pipe
        function drawPipe(x, y, height, isTop) {
            // Main pipe body - flat colors instead of gradient per pipe
            ctx.fillStyle = '#4CAF50';
            ctx.fillRect(x, y, pipeWidth, height);
            
            // Pipe highlight
            ctx.fillStyle = '#5CB85C';
            ctx.fillRect(x + 4, y, 12, height);
            
            // Pipe shadow
            ctx.fillStyle = '#2d6b30';
            ctx.fillRect(x + pipeWidth - 8, y, 8, height);
            
            // Pipe rim (cap)
            const rimHeight = 30;
            const rimWidth = pipeWidth + 10;
            const rimX = x - 5;
            const rimY = isTop ? y + height - rimHeight : y;
            
            ctx.fillStyle = '#4CAF50';
            ctx.fillRect(rimX, rimY, rimWidth, rimHeight);
            
            // Rim highlight
            ctx.fillStyle = '#5CB85C';
            ctx.fillRect(rimX + 4, rimY, 12, rimHeight);
            
            // Rim edges
            ctx.fillStyle = '#2d6b30';
            ctx.fillRect(rimX + rimWidth - 6, rimY, 6, rimHeight);
            
            if (!isTop) {
                ctx.fillStyle = 'rgba(255, 255, 255, 0.25)';
                ctx.fillRect(rimX, rimY, rimWidth, 3);
            }
            if (isTop) {
                ctx.fillStyle = 'rgba(0, 0, 0, 0.25)';
                ctx.fillRect(rimX, rimY + rimHeight - 3, rimWidth, 3);
            }
        }

        // Draw background
        function drawBackground() {
            const cycleLength = 4500;
            const timeProgress = (frameCount % cycleLength) / cycleLength;
            
            let skyColor1, skyColor2, skyColor3, celestialX, celestialY, celestialRadius, celestialColor, showStars;
            
            // Time of day colors
            if (timeProgress < 0.25) {
                // Dawn
                skyColor1 = '#FFB6C1';
                skyColor2 = '#FFD4E5';
                skyColor3 = '#E6F3FF';
                celestialX = 80 + (canvas.width / 2 - 80) * (timeProgress / 0.25);
                celestialY = 200 - 100 * (timeProgress / 0.25);
                celestialRadius = 50;
                celestialColor = '#FFA500';
                showStars = false;
            } else if (timeProgress < 0.5) {
                // Day
                skyColor1 = '#87CEEB';
                skyColor2 = '#B0E0E6';
                skyColor3 = '#E0F6FF';
                celestialX = canvas.width / 2 + (canvas.width - 100 - canvas.width / 2) * ((timeProgress - 0.25) / 0.25);
                celestialY = 80 + 30 * ((timeProgress - 0.25) / 0.25);
                celestialRadius = 55;
                celestialColor = '#FFD700';
                showStars = false;
            } else if (timeProgress < 0.75) {
                // Sunset to Night
                const t = (timeProgress - 0.5) / 0.25;
                skyColor1 = t < 0.5 ? '#FF6B6B' : '#1a1a2e';
                skyColor2 = t < 0.5 ? '#FF8C69' : '#2a2a4e';
                skyColor3 = t < 0.5 ? '#FFA07A' : '#3a3a6e';
                celestialX = canvas.width - 100 - (canvas.width - 100 - canvas.width / 2) * t;
                celestialY = 110 - 30 * t;
                celestialRadius = 40;
                celestialColor = t < 0.5 ? '#FF4500' : '#E0E0E0';
                showStars = t > 0.5;
            } else {
                // Night to Dawn
                skyColor1 = '#0a0a1a';
                skyColor2 = '#1a1a3e';
                skyColor3 = '#2a2a5e';
                celestialX = canvas.width / 2 - (canvas.width / 2 - 80) * ((timeProgress - 0.75) / 0.25);
                celestialY = 80 + 70 * ((timeProgress - 0.75) / 0.25);
                celestialRadius = 38;
                celestialColor = '#F0F0F0';
                showStars = true;
            }
            
            // Sky gradient
            const gradient = ctx.createLinearGradient(0, 0, 0, canvas.height - 50);
            gradient.addColorStop(0, skyColor1);
            gradient.addColorStop(0.5, skyColor2);
            gradient.addColorStop(1, skyColor3);
            ctx.fillStyle = gradient;
            ctx.fillRect(0, 0, canvas.width, canvas.height - 50);
            
            // === SCROLLING PROCEDURAL MOUNTAINS ===
            const bH = canvas.height;
            const biome = getBiome(worldScroll);
            let groundColor = biome.ground;
            const mH = biome.mtnH;
            
            // Three parallax mountain layers (far=slow, near=faster)
            const layers = [
                { speed: 0.08, base: 170, scale: 150, opacity: 0.2, colorShift: 0 },
                { speed: 0.15, base: 150, scale: 120, opacity: 0.28, colorShift: 20 },
                { speed: 0.25, base: 140, scale: 70, opacity: 0.22, colorShift: 40 },
            ];
            
            layers.forEach((layer, li) => {
                const scrollX = worldScroll * layer.speed;
                const r = Math.min(biome.mtnR + layer.colorShift, 255);
                const g = Math.min(biome.mtnG + layer.colorShift * 0.7, 255);
                const b = Math.min(biome.mtnB + layer.colorShift * 0.8, 255);
                ctx.fillStyle = `rgba(${r|0},${g|0},${b|0},${layer.opacity})`;
                
                ctx.beginPath();
                ctx.moveTo(0, bH - layer.base);
                for (let sx = 0; sx <= canvas.width; sx += 6) {
                    const wx = scrollX + sx;
                    const h = getMountainHeight(wx, li) * layer.scale * mH;
                    ctx.lineTo(sx, bH - layer.base - h);
                }
                ctx.lineTo(canvas.width, bH - layer.base);
                ctx.closePath();
                ctx.fill();
            });
            
            // Snow caps on tallest far-layer peaks
            if (biome.snow || showStars) {
                const scrollX = worldScroll * 0.08;
                ctx.fillStyle = 'rgba(255,255,255,0.5)';
                for (let sx = 0; sx <= canvas.width; sx += 6) {
                    const wx = scrollX + sx;
                    const h = getMountainHeight(wx, 0) * 150 * mH;
                    if (h > 110) {
                        const py = bH - 170 - h;
                        ctx.beginPath();
                        ctx.moveTo(sx - 6, py + 8);
                        ctx.lineTo(sx, py);
                        ctx.lineTo(sx + 6, py + 8);
                        ctx.closePath();
                        ctx.fill();
                    }
                }
            }
            
            // Volcanic glow
            if (biome.name === 'volcanic') {
                const scrollX = worldScroll * 0.08;
                ctx.fillStyle = 'rgba(255,60,10,0.1)';
                for (let sx = 0; sx <= canvas.width; sx += 30) {
                    const wx = scrollX + sx;
                    const h = getMountainHeight(wx, 0) * 150 * mH;
                    if (h > 120) {
                        ctx.beginPath();
                        ctx.arc(sx, bH - 170 - h + 8, 10, 0, Math.PI * 2);
                        ctx.fill();
                    }
                }
            }
            
            // Water/lake at the base (between mountains and ground)
            const waterGradient = ctx.createLinearGradient(0, canvas.height - 150, 0, canvas.height - 50);
            const waterColor1 = showStars ? 'rgba(30, 40, 80, 0.4)' : 'rgba(100, 180, 220, 0.3)';
            const waterColor2 = showStars ? 'rgba(20, 30, 60, 0.3)' : 'rgba(120, 200, 240, 0.2)';
            waterGradient.addColorStop(0, waterColor1);
            waterGradient.addColorStop(1, waterColor2);
            ctx.fillStyle = waterGradient;
            ctx.fillRect(0, canvas.height - 150, canvas.width, 100);
            
            // Water ripples/waves
            ctx.strokeStyle = showStars ? 'rgba(150, 180, 200, 0.15)' : 'rgba(255, 255, 255, 0.3)';
            ctx.lineWidth = 2;
            for (let y = canvas.height - 140; y < canvas.height - 50; y += 30) {
                ctx.beginPath();
                for (let x = 0; x < canvas.width; x += 40) {
                    const waveY = y + Math.sin((x + frameCount * 0.5) * 0.1) * 2;
                    if (x === 0) {
                        ctx.moveTo(x, waveY);
                    } else {
                        ctx.lineTo(x, waveY);
                    }
                }
                ctx.stroke();
            }
            
            // Water reflection shimmer
            if (!showStars) {
                ctx.fillStyle = 'rgba(255, 255, 255, 0.1)';
                for (let i = 0; i < 5; i++) {
                    const shimmerX = (i * 100 + frameCount * 0.3) % canvas.width;
                    const shimmerY = canvas.height - 140 + (i * 20);
                    ctx.beginPath();
                    ctx.ellipse(shimmerX, shimmerY, 15, 5, 0, 0, Math.PI * 2);
                    ctx.fill();
                }
            }
            
            // Celestial body (sun or moon)
            ctx.fillStyle = celestialColor;
            ctx.beginPath();
            ctx.arc(celestialX, celestialY, celestialRadius, 0, Math.PI * 2);
            ctx.fill();
            
            // Glow
            const glow = ctx.createRadialGradient(celestialX, celestialY, celestialRadius, celestialX, celestialY, celestialRadius * 2);
            glow.addColorStop(0, celestialColor + '40');
            glow.addColorStop(1, 'rgba(255, 223, 0, 0)');
            ctx.fillStyle = glow;
            ctx.beginPath();
            ctx.arc(celestialX, celestialY, celestialRadius * 2, 0, Math.PI * 2);
            ctx.fill();
            
            // Stars
            if (showStars) {
                ctx.fillStyle = 'rgba(255, 255, 255, 0.9)';
                const stars = [[50, 50], [150, 80], [250, 60], [350, 90], [450, 70], [80, 150], [200, 180], [300, 140], [400, 160], [100, 200], [180, 100], [280, 120], [380, 80]];
                stars.forEach(([x, y]) => {
                    ctx.beginPath();
                    ctx.arc(x, y, 1.5, 0, Math.PI * 2);
                    ctx.fill();
                });
            }
            
            // Clouds - scroll with parallax
            const cloudOpacity = showStars ? 0.2 : 0.7;
            ctx.fillStyle = `rgba(255, 255, 255, ${cloudOpacity})`;
            
            const cloudScroll = worldScroll * 0.04;
            ctx.beginPath();
            ctx.arc(((100 - cloudScroll) % (canvas.width + 200)) + 100, 90, 25, 0, Math.PI * 2);
            ctx.arc(((125 - cloudScroll) % (canvas.width + 200)) + 100, 85, 35, 0, Math.PI * 2);
            ctx.arc(((155 - cloudScroll) % (canvas.width + 200)) + 100, 90, 25, 0, Math.PI * 2);
            ctx.fill();
            
            const cloudScroll2 = worldScroll * 0.025;
            ctx.beginPath();
            ctx.arc(((280 - cloudScroll2) % (canvas.width + 300)) + 150, 170, 30, 0, Math.PI * 2);
            ctx.arc(((315 - cloudScroll2) % (canvas.width + 300)) + 150, 165, 40, 0, Math.PI * 2);
            ctx.arc(((350 - cloudScroll2) % (canvas.width + 300)) + 150, 170, 30, 0, Math.PI * 2);
            ctx.fill();
            
            // Ground
            const groundGradient = ctx.createLinearGradient(0, canvas.height - 50, 0, canvas.height);
            groundGradient.addColorStop(0, groundColor);
            groundGradient.addColorStop(1, darkenColor(groundColor, 20));
            ctx.fillStyle = groundGradient;
            ctx.fillRect(0, canvas.height - 50, canvas.width, 50);
        }
        
        // Draw foreground elements (grass, bushes, trees) - called after pipes
        function drawForeground() {
            const biome = getBiome(worldScroll);
            let grassColor = biome.grass;
            let bushColor = biome.bush;
            let treeColor = biome.tree;
            
            // Varied grass blades - different heights, widths, and angles
            const groundY = canvas.height - 50;
            ctx.fillStyle = grassColor;
            
            // Scrolling grass pattern
            const grassOffset = worldScroll * 0.95;
            const grassPattern = [
                {dx:0, h:14, w:2.5, lean:-0.1},
                {dx:5, h:8, w:1.5, lean:0.05},
                {dx:9, h:18, w:2, lean:-0.15},
                {dx:14, h:6, w:1.5, lean:0.1},
                {dx:17, h:12, w:2, lean:-0.05},
                {dx:22, h:20, w:2.5, lean:-0.2},
                {dx:26, h:9, w:1.5, lean:0.08},
                {dx:30, h:15, w:2, lean:0.12},
                {dx:34, h:7, w:1.5, lean:-0.06},
                {dx:38, h:22, w:3, lean:-0.1},
            ];
            const patternWidth = 42;
            
            const grassStartX = -(grassOffset % patternWidth) - patternWidth;
            for (let baseX = grassStartX; baseX < canvas.width + patternWidth; baseX += patternWidth) {
                grassPattern.forEach(g => {
                    const x = baseX + g.dx;
                    const tipX = x + g.h * g.lean;
                    ctx.beginPath();
                    ctx.moveTo(x - g.w * 0.5, groundY);
                    ctx.quadraticCurveTo(tipX - g.w * 0.3, groundY - g.h * 0.6, tipX, groundY - g.h);
                    ctx.quadraticCurveTo(tipX + g.w * 0.3, groundY - g.h * 0.6, x + g.w * 0.5, groundY);
                    ctx.fill();
                });
            }
            
            // Darker accent blades for depth
            ctx.fillStyle = darkenColor(grassColor, 15);
            for (let baseX = 10; baseX < canvas.width; baseX += 55) {
                const h = 16 + (baseX % 7) * 2;
                ctx.beginPath();
                ctx.moveTo(baseX - 1, groundY);
                ctx.quadraticCurveTo(baseX - 3, groundY - h * 0.6, baseX - 2, groundY - h);
                ctx.quadraticCurveTo(baseX, groundY - h * 0.5, baseX + 1, groundY);
                ctx.fill();
            }
            
            // Scrolling bushes - procedurally placed in world space
            const bushSpacing = 70;
            const bushScroll = worldScroll * 0.95;
            const firstBushW = Math.floor((bushScroll - 50) / bushSpacing) * bushSpacing;
            const gY = canvas.height - 50;
            
            for (let bwx = firstBushW; bwx < bushScroll + canvas.width + 50; bwx += bushSpacing) {
                const screenX = bwx - bushScroll;
                const bSeed = seededRand(bwx * 0.013 + 7.7);
                const localBiome = getBiome(bwx / 0.95);
                const s = (0.6 + bSeed * 0.7) * localBiome.bushScale;
                if (s < 0.3) continue;
                const x = screenX + (bSeed - 0.5) * 20;
                
                // Ground shadow
                ctx.fillStyle = 'rgba(0,0,0,0.15)';
                ctx.beginPath();
                ctx.ellipse(x, gY - 1, 20 * s, 4, 0, 0, Math.PI * 2);
                ctx.fill();
                
                // Back layer (darker, wider)
                ctx.fillStyle = darkenColor(bushColor, 18);
                ctx.beginPath();
                ctx.arc(x - 10 * s, gY - 8, 12 * s, Math.PI, 0);
                ctx.arc(x + 10 * s, gY - 8, 12 * s, Math.PI, 0);
                ctx.closePath();
                ctx.fill();
                
                // Main bush body - multiple overlapping lobes
                ctx.fillStyle = bushColor;
                ctx.beginPath();
                ctx.arc(x, gY - 14 * s, 14 * s, 0, Math.PI * 2);
                ctx.fill();
                ctx.beginPath();
                ctx.arc(x - 12 * s, gY - 8 * s, 11 * s, 0, Math.PI * 2);
                ctx.fill();
                ctx.beginPath();
                ctx.arc(x + 12 * s, gY - 8 * s, 11 * s, 0, Math.PI * 2);
                ctx.fill();
                ctx.beginPath();
                ctx.arc(x - 6 * s, gY - 18 * s, 9 * s, 0, Math.PI * 2);
                ctx.fill();
                ctx.beginPath();
                ctx.arc(x + 7 * s, gY - 17 * s, 10 * s, 0, Math.PI * 2);
                ctx.fill();
                
                // Light highlights (top-left lit)
                const hlColor = lightenColor(bushColor, 28);
                ctx.fillStyle = hlColor;
                ctx.beginPath();
                ctx.arc(x - 5 * s, gY - 18 * s, 5 * s, 0, Math.PI * 2);
                ctx.fill();
                ctx.beginPath();
                ctx.arc(x + 4 * s, gY - 20 * s, 4 * s, 0, Math.PI * 2);
                ctx.fill();
                ctx.beginPath();
                ctx.arc(x - 14 * s, gY - 10 * s, 4 * s, 0, Math.PI * 2);
                ctx.fill();
                
                // Dark depth (bottom-right)
                const dkColor = darkenColor(bushColor, 22);
                ctx.fillStyle = dkColor;
                ctx.beginPath();
                ctx.arc(x + 10 * s, gY - 6 * s, 5 * s, 0, Math.PI * 2);
                ctx.fill();
                ctx.beginPath();
                ctx.arc(x - 2 * s, gY - 5 * s, 4 * s, 0, Math.PI * 2);
                ctx.fill();
                
                // Tiny leaf detail dots
                ctx.fillStyle = lightenColor(bushColor, 40);
                for (let d = 0; d < 3; d++) {
                    const dx = x + (d - 1) * 7 * s;
                    const dy = gY - (14 + d * 3) * s;
                    ctx.beginPath();
                    ctx.arc(dx, dy, 1.5, 0, Math.PI * 2);
                    ctx.fill();
                }
            }
            
            // Scrolling trees - procedurally placed in world space
            const treeSpacing = 100;
            const treeScroll = worldScroll * 0.95;
            const firstTreeW = Math.floor((treeScroll - 50) / treeSpacing) * treeSpacing;
            const treeTypeList = ['round','tall','pine','cactus'];
            
            for (let twx = firstTreeW; twx < treeScroll + canvas.width + 50; twx += treeSpacing) {
                const screenX = twx - treeScroll;
                const tSeed = seededRand(twx * 0.017 + 3.3);
                const tSeed2 = seededRand(twx * 0.031 + 11.1);
                const localBiome = getBiome(twx / 0.95);
                const typeIdx = Math.floor(tSeed * localBiome.treeTypes.length);
                const tType = localBiome.treeTypes[typeIdx];
                const x = screenX + (tSeed2 - 0.5) * 30;
                const th = 42 + tSeed2 * 25;
                const tw = 6 + tSeed * 3;
                const trunkTop = gY - th * 0.55;
                
                // Ground shadow
                ctx.fillStyle = 'rgba(0,0,0,0.12)';
                ctx.beginPath();
                ctx.ellipse(x + 2, gY - 1, tw + 4, 3, 0, 0, Math.PI * 2);
                ctx.fill();
                
                // Trunk
                ctx.fillStyle = '#5C4033';
                ctx.beginPath();
                ctx.moveTo(x - tw / 2, gY);
                ctx.lineTo(x - tw / 2 - 1, trunkTop + 5);
                ctx.lineTo(x + tw / 2 + 1, trunkTop + 5);
                ctx.lineTo(x + tw / 2, gY);
                ctx.closePath();
                ctx.fill();
                
                // Trunk highlight
                ctx.fillStyle = '#6B5240';
                ctx.fillRect(x - tw / 2 + 1, trunkTop + 5, 3, gY - trunkTop - 5);
                
                // Trunk bark lines
                ctx.strokeStyle = '#4A3526';
                ctx.lineWidth = 0.5;
                for (let by = trunkTop + 12; by < gY - 3; by += 8) {
                    ctx.beginPath();
                    ctx.moveTo(x - tw / 2 + 1, by);
                    ctx.lineTo(x + tw / 2 - 1, by + 2);
                    ctx.stroke();
                }
                
                // Branch stubs
                ctx.strokeStyle = '#5C4033';
                ctx.lineWidth = 2;
                ctx.beginPath();
                ctx.moveTo(x - tw / 2, trunkTop + 15);
                ctx.lineTo(x - tw / 2 - 6, trunkTop + 10);
                ctx.stroke();
                ctx.beginPath();
                ctx.moveTo(x + tw / 2, trunkTop + 22);
                ctx.lineTo(x + tw / 2 + 5, trunkTop + 17);
                ctx.stroke();
                
                // Foliage based on type
                if (tType === 'round') {
                    // Lush round canopy
                    const cy = gY - th + 8;
                    const r = th * 0.42;
                    
                    // Shadow layer
                    ctx.fillStyle = darkenColor(treeColor, 20);
                    ctx.beginPath();
                    ctx.arc(x + 2, cy + 4, r, 0, Math.PI * 2);
                    ctx.fill();
                    
                    // Main canopy
                    ctx.fillStyle = treeColor;
                    ctx.beginPath();
                    ctx.arc(x, cy, r, 0, Math.PI * 2);
                    ctx.arc(x - r * 0.65, cy + r * 0.4, r * 0.7, 0, Math.PI * 2);
                    ctx.arc(x + r * 0.65, cy + r * 0.4, r * 0.7, 0, Math.PI * 2);
                    ctx.arc(x, cy - r * 0.35, r * 0.6, 0, Math.PI * 2);
                    ctx.fill();
                    
                    // Highlights
                    ctx.fillStyle = lightenColor(treeColor, 22);
                    ctx.beginPath();
                    ctx.arc(x - r * 0.3, cy - r * 0.3, r * 0.35, 0, Math.PI * 2);
                    ctx.fill();
                    ctx.beginPath();
                    ctx.arc(x + r * 0.2, cy - r * 0.5, r * 0.25, 0, Math.PI * 2);
                    ctx.fill();
                    
                    // Dark underside
                    ctx.fillStyle = darkenColor(treeColor, 15);
                    ctx.beginPath();
                    ctx.arc(x + r * 0.3, cy + r * 0.5, r * 0.3, 0, Math.PI * 2);
                    ctx.fill();
                    
                } else if (tType === 'tall') {
                    // Tall oval/columnar tree
                    const cy = gY - th + 14;
                    const rx = th * 0.22;
                    const ry = th * 0.45;
                    
                    ctx.fillStyle = darkenColor(treeColor, 15);
                    ctx.beginPath();
                    ctx.ellipse(x + 1, cy + 3, rx, ry, 0, 0, Math.PI * 2);
                    ctx.fill();
                    
                    ctx.fillStyle = treeColor;
                    ctx.beginPath();
                    ctx.ellipse(x, cy, rx, ry, 0, 0, Math.PI * 2);
                    ctx.fill();
                    
                    // Highlight
                    ctx.fillStyle = lightenColor(treeColor, 20);
                    ctx.beginPath();
                    ctx.ellipse(x - rx * 0.3, cy - ry * 0.3, rx * 0.5, ry * 0.4, 0, 0, Math.PI * 2);
                    ctx.fill();
                    
                } else if (tType === 'pine') {
                    // Triangular pine / evergreen
                    const tip = gY - th;
                    const baseW = th * 0.45;
                    
                    // Three layered triangles
                    for (let layer = 0; layer < 3; layer++) {
                        const ly = tip + layer * 12;
                        const lw = baseW * (0.5 + layer * 0.25);
                        const lh = 22 + layer * 4;
                        
                        ctx.fillStyle = darkenColor(treeColor, layer * 5);
                        ctx.beginPath();
                        ctx.moveTo(x, ly);
                        ctx.lineTo(x - lw / 2, ly + lh);
                        ctx.lineTo(x + lw / 2, ly + lh);
                        ctx.closePath();
                        ctx.fill();
                        
                        // Highlight edge
                        ctx.fillStyle = lightenColor(treeColor, 18 - layer * 5);
                        ctx.beginPath();
                        ctx.moveTo(x, ly);
                        ctx.lineTo(x - lw * 0.25, ly + lh * 0.6);
                        ctx.lineTo(x - lw * 0.1, ly + lh * 0.3);
                        ctx.closePath();
                        ctx.fill();
                    }
                } else if (tType === 'cactus') {
                    // Desert cactus
                    const cw = 10, ch = th * 0.7, cTop = gY - ch;
                    ctx.fillStyle = treeColor;
                    ctx.beginPath();
                    ctx.roundRect(x - cw/2, cTop, cw, ch, 4);
                    ctx.fill();
                    ctx.beginPath();
                    ctx.roundRect(x - cw/2 - 12, cTop + ch*0.3, 13, 8, 3);
                    ctx.fill();
                    ctx.beginPath();
                    ctx.roundRect(x - cw/2 - 12, cTop + ch*0.12, 8, ch*0.22, 3);
                    ctx.fill();
                    ctx.beginPath();
                    ctx.roundRect(x + cw/2, cTop + ch*0.45, 11, 8, 3);
                    ctx.fill();
                    ctx.beginPath();
                    ctx.roundRect(x + cw/2 + 3, cTop + ch*0.28, 8, ch*0.22, 3);
                    ctx.fill();
                    ctx.fillStyle = lightenColor(treeColor, 22);
                    ctx.fillRect(x - cw/2 + 2, cTop + 3, 3, ch - 6);
                }
            }
            
            // Snow effect - based on biome (tundra, alpine) instead of season
            if (getBiome(worldScroll).snow) {
                // Pre-seeded snowflake parameters (50 flakes, computed once via index)
                for (let i = 0; i < 50; i++) {
                    // Each flake has unique: start X, fall speed, drift, size, opacity
                    const seed1 = (i * 173 + 71) % 500;  // pseudo-random spread
                    const seed2 = (i * 239 + 53) % 400;
                    const size = 1 + (i % 5) * 0.5;       // 1 to 3.5 radius
                    const fallSpeed = 0.3 + (i % 7) * 0.12; // varied fall rates
                    const driftAmp = 15 + (i % 4) * 10;    // horizontal sway amplitude
                    const driftSpeed = 0.008 + (i % 3) * 0.004; // sway speed
                    const opacity = 0.4 + (i % 5) * 0.12;
                    
                    const baseX = (seed1 / 500) * (canvas.width + 40) - 20;
                    const snowX = baseX + Math.sin(frameCount * driftSpeed + seed2) * driftAmp;
                    const snowY = (seed2 + frameCount * fallSpeed) % (canvas.height - 40);
                    
                    ctx.globalAlpha = opacity;
                    ctx.fillStyle = '#fff';
                    ctx.beginPath();
                    ctx.arc(snowX, snowY, size, 0, Math.PI * 2);
                    ctx.fill();
                }
                ctx.globalAlpha = 1;
            }
        }
        
        // Helper functions for colors
        function darkenColor(color, percent) {
            const num = parseInt(color.replace('#', ''), 16);
            const amt = Math.round(2.55 * percent);
            const R = Math.max((num >> 16) - amt, 0);
            const G = Math.max((num >> 8 & 0x00FF) - amt, 0);
            const B = Math.max((num & 0x0000FF) - amt, 0);
            return '#' + (0x1000000 + R * 0x10000 + G * 0x100 + B).toString(16).slice(1);
        }
        
        function lightenColor(color, percent) {
            const num = parseInt(color.replace('#', ''), 16);
            const amt = Math.round(2.55 * percent);
            const R = Math.min((num >> 16) + amt, 255);
            const G = Math.min((num >> 8 & 0x00FF) + amt, 255);
            const B = Math.min((num & 0x0000FF) + amt, 255);
            return '#' + (0x1000000 + R * 0x10000 + G * 0x100 + B).toString(16).slice(1);
        }
        
        // Update game
        function update(deltaMultiplier = 1) {
            if (!gameStarted) {
                // Keep bird stationary at start
                bird.velocity = 0;
                return;
            }
            
            if (gameOver) return;

            // Animate wing flapping
            wingFrame++;

            // Only apply physics after first jump
            if (firstJump) {
                // Update bird with delta time and game speed
                bird.velocity += bird.gravity * deltaMultiplier;
                bird.y += bird.velocity * deltaMultiplier;
            }

            // Check ground collision
            if (bird.y + bird.height >= canvas.height - 50) {
                endGame();
                return;
            }

            // Check ceiling collision
            if (bird.y <= 0) {
                bird.y = 0;
                bird.velocity = 0;
            }

            // Update feathers with delta time
            for (let i = feathers.length - 1; i >= 0; i--) {
                feathers[i].y += feathers[i].vy * deltaMultiplier;
                feathers[i].x += feathers[i].vx * deltaMultiplier;
                feathers[i].rotation += feathers[i].rotSpeed * deltaMultiplier;
                feathers[i].vy += 0.15 * deltaMultiplier;
                feathers[i].life -= deltaMultiplier;
                
                // Remove old feathers
                if (feathers[i].life <= 0 || feathers[i].y > canvas.height) {
                    feathers.splice(i, 1);
                }
            }
            
            // Update coins
            if (firstJump) {
                for (let i = coinObjects.length - 1; i >= 0; i--) {
                    coinObjects[i].x -= scrollSpeed * deltaMultiplier;
                    coinObjects[i].rotation += 0.1 * deltaMultiplier;
                    
                    // Check coin collection - improved hitbox
                    if (!coinObjects[i].collected) {
                        const birdCenterX = bird.x + bird.width / 2;
                        const birdCenterY = bird.y + bird.height / 2;
                        const dist = Math.sqrt(
                            Math.pow(birdCenterX - coinObjects[i].x, 2) +
                            Math.pow(birdCenterY - coinObjects[i].y, 2)
                        );
                        
                        // Larger collision radius for easier collection
                        if (dist < 30) {
                            coinObjects[i].collected = true;
                            
                            // Coin value increases with score, max 5
                            const coinValue = Math.min(Math.floor(score / 5) + 1, 5);
                            coinsThisRun += coinValue;
                            coins += coinValue;
                            
                            localStorage.setItem('coins', coins);
                            playCoinSound();
                            updateCoinDisplay();
                            
                            console.log(`Collected ${coinValue} coins! Total: ${coins}, This run: ${coinsThisRun}`);
                        }
                    }
                    
                    // Remove off-screen coins
                    if (coinObjects[i].x < -20) {
                        coinObjects.splice(i, 1);
                    }
                }
            }

            // Add new pipes (frameCount accumulates at 60fps-equivalent rate)
            frameCount += deltaMultiplier * 2.5;
            worldScroll += scrollSpeed * deltaMultiplier;
            if (firstJump && frameCount - lastPipeFrame >= 150) {
                lastPipeFrame = frameCount;
                // Constrain pipe height to ensure gap is always reachable
                const minHeight = 100; // Minimum distance from top
                const maxHeight = canvas.height - pipeGap - 200; // Minimum distance from bottom
                const pipeHeight = Math.random() * (maxHeight - minHeight) + minHeight;
                
                pipes.push({
                    x: canvas.width,
                    topHeight: pipeHeight,
                    scored: false
                });
                
                // Add coin in the middle of the pipe gap (50% chance)
                if (Math.random() < 0.5) {
                    coinObjects.push({
                        x: canvas.width + 30,
                        y: pipeHeight + pipeGap / 2,
                        collected: false,
                        rotation: 0
                    });
                }
            }

            // Update pipes only after first jump
            if (firstJump) {
                for (let i = pipes.length - 1; i >= 0; i--) {
                    pipes[i].x -= scrollSpeed * deltaMultiplier;

                // Check collision
                if (
                    bird.x + bird.width > pipes[i].x &&
                    bird.x < pipes[i].x + pipeWidth &&
                    (bird.y < pipes[i].topHeight || bird.y + bird.height > pipes[i].topHeight + pipeGap)
                ) {
                    endGame();
                    return;
                }

                // Score point
                if (!pipes[i].scored && bird.x > pipes[i].x + pipeWidth) {
                    pipes[i].scored = true;
                    score++;
                    playScoreSound();
                    document.getElementById('score').textContent = score;
                    
                    // Spawn egg every 15 points
                    if (score > 0 && score % 15 === 0 && score !== lastEggScore) {
                        lastEggScore = score;
                        eggs.push({
                            x: bird.x,
                            y: bird.y + 15,
                            vy: 0,
                            collected: false,
                            alpha: 1,
                            bounced: false
                        });
                    }
                    
                    if (score > highScore) {
                        highScore = score;
                        localStorage.setItem('flappyHighScore', highScore);
                        document.getElementById('highScore').textContent = 'High Score: ' + highScore;
                    }
                }

                // Remove off-screen pipes
                if (pipes[i].x + pipeWidth < 0) {
                    pipes.splice(i, 1);
                }
            }
            }
            
            // Update trail particles
            if (currentTrail !== 'none' && firstJump) {
                const trail = birdTrails[currentTrail];
                for (let tp = 0; tp < 2; tp++) {
                    trailParticles.push({
                        x: bird.x - 5 + Math.random() * 4,
                        y: bird.y + 8 + Math.random() * 8,
                        vx: -1.5 - Math.random() * 1.5,
                        vy: (Math.random() - 0.5) * 0.8,
                        life: 1,
                        size: 2 + Math.random() * 3,
                        color: trail.color
                    });
                }
            }
            for (let tp = trailParticles.length - 1; tp >= 0; tp--) {
                const p = trailParticles[tp];
                p.x += p.vx * deltaMultiplier;
                p.y += p.vy * deltaMultiplier;
                p.life -= 0.03 * deltaMultiplier;
                p.size *= 0.98;
                if (p.life <= 0) trailParticles.splice(tp, 1);
            }
            
            // Update eggs
            const eggGroundY = canvas.height - 50;
            for (let ei = eggs.length - 1; ei >= 0; ei--) {
                const egg = eggs[ei];
                if (!egg.collected) {
                    egg.vy += 0.35 * deltaMultiplier;
                    egg.y += egg.vy * deltaMultiplier;
                    egg.x -= scrollSpeed * 0.3 * deltaMultiplier;
                    if (egg.y >= eggGroundY - 8) {
                        egg.y = eggGroundY - 8;
                        if (!egg.bounced) {
                            egg.bounced = true;
                            egg.vy = -3;
                        } else {
                            egg.vy = 0;
                            egg.collected = true;
                            coins += 5;
                            coinsThisRun += 5;
                            localStorage.setItem('coins', coins);
                            updateCoinDisplay();
                            playScoreSound();
                        }
                    }
                } else {
                    egg.alpha -= 0.04 * deltaMultiplier;
                    if (egg.alpha <= 0) eggs.splice(ei, 1);
                }
            }
        }

        // Draw game
        function draw() {
            ctx.clearRect(0, 0, canvas.width, canvas.height);
            drawBackground();
            
            // Update body background to match sky (simplified)
            const cycleLength = 4500; // Match the slower cycle
            const timeProgress = (frameCount % cycleLength) / cycleLength;
            let bodyColor = '#87CEEB'; // Default day color
            
            if (timeProgress < 0.25) {
                bodyColor = '#FFD4E5'; // Dawn
            } else if (timeProgress < 0.5) {
                bodyColor = '#87CEEB'; // Day
            } else if (timeProgress < 0.75) {
                bodyColor = timeProgress < 0.625 ? '#FF8C69' : '#1a1a2e'; // Sunset to Night
            } else {
                bodyColor = '#0a0a1a'; // Night
            }
            document.body.style.background = bodyColor;

            // Draw pipes BEFORE foreground elements
            pipes.forEach(pipe => {
                drawPipe(pipe.x, 0, pipe.topHeight, true);
                drawPipe(pipe.x, pipe.topHeight + pipeGap, canvas.height - pipe.topHeight - pipeGap - 50, false);
            });

            // Draw coins
            coinObjects.forEach(coin => drawCoin(coin));

            // Draw foreground scenery (bushes, grass, trees) on top of pipes
            drawForeground();

            // Draw feathers
            feathers.forEach(feather => drawFeather(feather));

            // Draw trail particles
            trailParticles.forEach(p => {
                let c = p.color;
                if (c === 'rainbow') {
                    const hue = (Date.now() * 0.3 + p.x * 2) % 360;
                    const rgb = hslToRgb(hue / 360, 1, 0.6);
                    c = `${rgb[0]},${rgb[1]},${rgb[2]}`;
                }
                ctx.fillStyle = `rgba(${c},${p.life * 0.45})`;
                ctx.beginPath();
                ctx.arc(p.x, p.y, p.size, 0, Math.PI * 2);
                ctx.fill();
            });
            
            // Draw eggs
            eggs.forEach(egg => {
                ctx.save();
                ctx.globalAlpha = egg.alpha;
                // Egg shadow on ground
                if (egg.bounced || egg.collected) {
                    ctx.fillStyle = 'rgba(0,0,0,0.15)';
                    ctx.beginPath();
                    ctx.ellipse(egg.x, canvas.height - 49, 7, 3, 0, 0, Math.PI * 2);
                    ctx.fill();
                }
                // Egg body
                ctx.fillStyle = '#FFF8E7';
                ctx.beginPath();
                ctx.ellipse(egg.x, egg.y, 7, 9, 0, 0, Math.PI * 2);
                ctx.fill();
                ctx.strokeStyle = '#E8D9C0';
                ctx.lineWidth = 1;
                ctx.stroke();
                // Egg speckles
                ctx.fillStyle = '#D4C5A0';
                ctx.beginPath();
                ctx.arc(egg.x - 2, egg.y - 2, 1, 0, Math.PI * 2);
                ctx.arc(egg.x + 3, egg.y + 1, 0.8, 0, Math.PI * 2);
                ctx.arc(egg.x - 1, egg.y + 3, 0.8, 0, Math.PI * 2);
                ctx.fill();
                // Egg shine
                ctx.fillStyle = 'rgba(255,255,255,0.6)';
                ctx.beginPath();
                ctx.ellipse(egg.x - 2, egg.y - 3, 2.5, 1.5, -0.3, 0, Math.PI * 2);
                ctx.fill();
                // +5 text floating up when collected
                if (egg.collected) {
                    ctx.fillStyle = `rgba(255,215,0,${egg.alpha})`;
                    ctx.font = 'bold 14px Arial';
                    ctx.textAlign = 'center';
                    ctx.fillText('+5 🪙', egg.x, egg.y - 15 + (1 - egg.alpha) * -20);
                }
                ctx.restore();
            });

            drawBird();
            
            // Start prompt
            if (!gameStarted) {
                const pulse = 0.6 + Math.sin(Date.now() * 0.003) * 0.4;
                ctx.save();
                ctx.globalAlpha = pulse;
                ctx.fillStyle = '#fff';
                ctx.font = 'bold 18px Arial, sans-serif';
                ctx.textAlign = 'center';
                ctx.textBaseline = 'middle';
                ctx.strokeStyle = 'rgba(0,0,0,0.5)';
                ctx.lineWidth = 3;
                ctx.strokeText('Tap or press Space to fly!', canvas.width / 2, canvas.height / 2 + 40);
                ctx.fillText('Tap or press Space to fly!', canvas.width / 2, canvas.height / 2 + 40);
                ctx.restore();
            }
        }

        const liveFpsEl = document.getElementById('liveFps');

        // Game loop with delta time
        function gameLoop(currentTime) {
            requestAnimationFrame(gameLoop);
            
            if (!lastTime) { lastTime = currentTime; fpsLastCheck = currentTime; }
            const elapsed = currentTime - lastTime;
            
            // Skip if no time has passed
            if (elapsed <= 0) return;
            
            const deltaMultiplier = Math.min(elapsed / (1000 / 60), 3); // Normalize to 60fps, cap at 3 to prevent spikes
            lastTime = currentTime;
            
            // Live FPS counter
            fpsFrameCount++;
            if (currentTime - fpsLastCheck >= 500) {
                currentFps = Math.round(fpsFrameCount / ((currentTime - fpsLastCheck) / 1000));
                fpsFrameCount = 0;
                fpsLastCheck = currentTime;
                liveFpsEl.textContent = currentFps + ' FPS';
                liveFpsEl.style.color = currentFps >= targetFps * 0.9 ? '#0f0' : currentFps >= targetFps * 0.5 ? '#ff0' : '#f00';
            }
            
            update(deltaMultiplier);
            draw();
        }

        // Cache modal elements
        const modalElements = [
            document.getElementById('gamblingHub'),
            document.getElementById('blackjackGame'),
            document.getElementById('baccaratGame'),
            document.getElementById('rouletteGame'),
            document.getElementById('slotsGame'),
            document.getElementById('skinSelector'),
            document.getElementById('shopMenu')
        ];

        function isModalOpen() {
            for (let i = 0; i < modalElements.length; i++) {
                if (modalElements[i].classList.contains('show')) return true;
            }
            return false;
        }

        // Jump
        function jump() {
            if (isModalOpen()) return;
            if (!gameStarted) {
                startGame();
                return;
            }
            
            if (gameOver) return;
            
            // Mark that first jump has occurred and start music
            if (!firstJump) {
                firstJump = true;
                playBackgroundMusic();
            }
            
            bird.velocity = bird.jump;
            playJumpSound();
            
            // Create feather every 3 jumps - shoots upward/outward
            jumpCount++;
            if (jumpCount % 3 === 0) {
                feathers.push({
                    x: bird.x + bird.width / 2 - 10,
                    y: bird.y + bird.height / 2,
                    vx: -2 - Math.random() * 2, // Shoot backward
                    vy: -3 - Math.random() * 2, // Shoot upward
                    rotation: Math.random() * Math.PI * 2,
                    rotSpeed: (Math.random() - 0.5) * 0.3,
                    life: 90 // Longer life for better trail effect
                });
            }
        }

        // Event listeners
        canvas.addEventListener('click', jump);
        document.addEventListener('keydown', (e) => {
            if (e.code === 'Space') {
                e.preventDefault();
                if (isModalOpen()) return;
                if (gameOver) {
                    restartGame();
                } else {
                    jump();
                }
            }
        });

        // Baccarat Game
        let bacDeck = [];
        let bacPlayerHand = [];
        let bacBankerHand = [];
        let bacCurrentBet = 0;
        let bacBetOn = ''; // 'player', 'banker', or 'tie'
        let bacLastBet = 0; // Track last bet amount for rebet
        let bacLastBetOn = ''; // Track last bet type for rebet
        
        // Track card counts for animation
        let bacPrevPlayerCount = 0;
        let bacPrevBankerCount = 0;

        // Roulette Game  
        let rouBets = []; // Array of {type, value, amount}
        const rouReds = [1,3,5,7,9,12,14,16,18,19,21,23,25,27,30,32,34,36];
        const rouBlacks = [2,4,6,8,10,11,13,15,17,20,22,24,26,28,29,31,33,35];

        // Blackjack Game
        let bjDeck = [];
        let bjPlayerHand = [];
        let bjPlayerSplitHand = []; // Second hand after split
        let bjDealerHand = [];
        let bjCurrentBet = 0;
        let bjGameActive = false;
        let bjDealerRevealed = false;
        let bjIsSplit = false;
        let bjActiveHand = 'main'; // 'main' or 'split'
        let bjSplitBet = 0;
        let bjLastBet = 0; // Track last bet amount for rebet
        
        // Track card counts for animation
        let bjPrevPlayerCount = 0;
        let bjPrevDealerCount = 0;
        let bjPrevSplitCount = 0;

        function createDeck() {
            const suits = ['♠', '♥', '♦', '♣'];
            const values = ['A', '2', '3', '4', '5', '6', '7', '8', '9', '10', 'J', 'Q', 'K'];
            const deck = [];
            
            // 6-deck shoe like real casinos — more variance, less streaky
            const numDecks = 6;
            for (let d = 0; d < numDecks; d++) {
                for (let suit of suits) {
                    for (let value of values) {
                        deck.push({
                            suit: suit,
                            value: value,
                            numValue: value === 'A' ? 11 : ['J', 'Q', 'K'].includes(value) ? 10 : parseInt(value)
                        });
                    }
                }
            }
            
            // Triple Fisher-Yates shuffle for thorough randomization
            for (let pass = 0; pass < 3; pass++) {
                for (let i = deck.length - 1; i > 0; i--) {
                    const j = Math.floor(Math.random() * (i + 1));
                    [deck[i], deck[j]] = [deck[j], deck[i]];
                }
            }
            
            // Cut the deck at a random point (simulates casino cut card)
            const cutPoint = Math.floor(deck.length * 0.15 + Math.random() * deck.length * 0.7);
            const cutDeck = [...deck.slice(cutPoint), ...deck.slice(0, cutPoint)];
            
            return cutDeck;
        }

        function calculateScore(hand) {
            let score = 0;
            let aces = 0;
            
            for (let card of hand) {
                score += card.numValue;
                if (card.value === 'A') aces++;
            }
            
            // Adjust for aces
            while (score > 21 && aces > 0) {
                score -= 10;
                aces--;
            }
            
            return score;
        }
        
        function isBlackjack(hand) {
            // True blackjack is exactly 2 cards totaling 21 (Ace + 10-value card)
            if (hand.length !== 2) return false;
            const score = calculateScore(hand);
            return score === 21;
        }

        function renderCard(card, hidden = false, isNew = false) {
            const isRed = card.suit === '♥' || card.suit === '♦';
            const newClass = isNew ? ' new-card' : '';
            if (hidden) {
                return `<div class="bj-card bj-card-back${newClass}">🂠</div>`;
            }
            return `<div class="bj-card ${isRed ? 'red' : 'black'}${newClass}">${card.value}${card.suit}</div>`;
        }

        function updateBlackjackDisplay() {
            document.getElementById('bjCoins').textContent = coins;
            document.getElementById('currentBet').textContent = bjCurrentBet;
            
            if (bjIsSplit) {
                document.getElementById('splitBet').textContent = bjSplitBet;
            }
            
            // Also update total balance on game over screen if it's visible
            const totalCoinsDisplay = document.getElementById('totalCoinsDisplay');
            if (totalCoinsDisplay) {
                totalCoinsDisplay.textContent = coins;
            }
            
            // Update shop coin displays
            document.getElementById('shopCoins').textContent = coins;
            document.getElementById('shopCoinCount').textContent = coins;
            
            // Render dealer cards
            const dealerCardsHTML = bjDealerHand.map((card, i) => {
                const isNew = i >= bjPrevDealerCount;
                if (i === 1 && !bjDealerRevealed) {
                    return renderCard(card, true, isNew);
                }
                return renderCard(card, false, isNew);
            }).join('');
            document.getElementById('dealerCards').innerHTML = dealerCardsHTML;
            
            // Render main player cards
            const playerCardsHTML = bjPlayerHand.map((card, i) => {
                const isNew = i >= bjPrevPlayerCount;
                return renderCard(card, false, isNew);
            }).join('');
            document.getElementById('playerCards').innerHTML = playerCardsHTML;
            
            // Render split hand if exists
            if (bjIsSplit) {
                const splitCardsHTML = bjPlayerSplitHand.map((card, i) => {
                    const isNew = i >= bjPrevSplitCount;
                    return renderCard(card, false, isNew);
                }).join('');
                document.getElementById('splitCards').innerHTML = splitCardsHTML;
                document.getElementById('splitScore').textContent = `Score: ${calculateScore(bjPlayerSplitHand)}`;
            }
            
            // Update card counts after rendering
            bjPrevPlayerCount = bjPlayerHand.length;
            bjPrevDealerCount = bjDealerHand.length;
            bjPrevSplitCount = bjPlayerSplitHand.length;
            
            // Update scores
            const playerScore = calculateScore(bjPlayerHand);
            document.getElementById('playerScore').textContent = `Score: ${playerScore}`;
            
            if (bjDealerRevealed) {
                const dealerScore = calculateScore(bjDealerHand);
                document.getElementById('dealerScore').textContent = `Score: ${dealerScore}`;
            } else {
                document.getElementById('dealerScore').textContent = '';
            }
            
            // Highlight active hand
            const mainHandDiv = document.getElementById('playerCards').parentElement;
            const splitHandDiv = document.getElementById('splitCards').parentElement;
            mainHandDiv.classList.remove('active');
            splitHandDiv.classList.remove('active');
            
            if (bjIsSplit && bjGameActive) {
                if (bjActiveHand === 'main') {
                    mainHandDiv.classList.add('active');
                } else {
                    splitHandDiv.classList.add('active');
                }
            }
        }

        function startBlackjackRound(bet) {
            if (coins < bet) {
                alert('Not enough coins!');
                return;
            }
            
            bjCurrentBet = bet;
            bjLastBet = bet; // Track this bet for rebet
            coins -= bet;
            localStorage.setItem('coins', coins);
            updateCoinDisplay();
            
            bjDeck = createDeck();
            bjPlayerHand = [];
            bjPlayerSplitHand = [];
            bjDealerHand = [];
            bjGameActive = true;
            bjDealerRevealed = false;
            bjIsSplit = false;
            bjActiveHand = 'main';
            bjSplitBet = 0;
            
            // Reset card counts for animation tracking
            bjPrevPlayerCount = 0;
            bjPrevDealerCount = 0;
            bjPrevSplitCount = 0;
            
            document.getElementById('bjBetSection').style.display = 'none';
            playChipPlace();
            document.getElementById('bjTable').style.display = 'block';
            document.getElementById('bjActions').style.display = 'none';
            document.getElementById('bjReplayActions').style.display = 'none';
            document.getElementById('bjMessage').textContent = 'Dealing cards...';
            document.getElementById('splitHandContainer').style.display = 'none';
            
            // Clear displays
            document.getElementById('dealerCards').innerHTML = '';
            document.getElementById('playerCards').innerHTML = '';
            document.getElementById('dealerScore').textContent = '';
            document.getElementById('playerScore').textContent = '';
            
            // Deal cards with animation delays
            setTimeout(() => {
                bjPlayerHand.push(bjDeck.pop());
                updateBlackjackDisplay();
                playCardSound();
            }, 300);
            
            setTimeout(() => {
                bjDealerHand.push(bjDeck.pop());
                updateBlackjackDisplay();
                playCardSound();
            }, 600);
            
            setTimeout(() => {
                bjPlayerHand.push(bjDeck.pop());
                updateBlackjackDisplay();
                playCardSound();
            }, 900);
            
            setTimeout(() => {
                bjDealerHand.push(bjDeck.pop());
                updateBlackjackDisplay();
                playCardFlip();
                document.getElementById('bjMessage').textContent = '';
                
                // Check for blackjack
                if (calculateScore(bjPlayerHand) === 21) {
                    setTimeout(() => stand(), 500);
                } else {
                    // Enable action buttons
                    document.getElementById('bjActions').style.display = 'block';
                    
                    // Enable all buttons initially
                    document.getElementById('bjHit').disabled = false;
                    document.getElementById('bjStand').disabled = false;
                    document.getElementById('bjDouble').disabled = coins < bjCurrentBet;
                    
                    // Enable split if cards have same value and player can afford it
                    const canSplit = bjPlayerHand.length === 2 && 
                                   bjPlayerHand[0].numValue === bjPlayerHand[1].numValue &&
                                   coins >= bjCurrentBet;
                    document.getElementById('bjSplit').disabled = !canSplit;
                }
            }, 1200);
        }

        function hit() {
            if (!bjGameActive) return;
            
            const currentHand = bjActiveHand === 'main' ? bjPlayerHand : bjPlayerSplitHand;
            const currentBet = bjActiveHand === 'main' ? bjCurrentBet : bjSplitBet;
            
            // Disable buttons during animation
            document.getElementById('bjHit').disabled = true;
            document.getElementById('bjDouble').disabled = true;
            document.getElementById('bjSplit').disabled = true;
            document.getElementById('bjStand').disabled = true;
            document.getElementById('bjMessage').textContent = 'Drawing card...';
            
            setTimeout(() => {
                currentHand.push(bjDeck.pop());
                updateBlackjackDisplay();
                playCardSound();
                
                // Calculate score AFTER adding the card
                const playerScore = calculateScore(currentHand);
                
                if (playerScore > 21) {
                    // Player busted
                    if (bjIsSplit && bjActiveHand === 'main') {
                        // Move to split hand
                        document.getElementById('bjMessage').textContent = 'First hand busted! Playing second hand...';
                        bjActiveHand = 'split';
                        setTimeout(() => {
                            document.getElementById('bjHit').disabled = false;
                            document.getElementById('bjDouble').disabled = coins < bjSplitBet;
                            document.getElementById('bjSplit').disabled = true;
                            document.getElementById('bjStand').disabled = false;
                            document.getElementById('bjMessage').textContent = '';
                            updateBlackjackDisplay();
                        }, 800);
                    } else {
                        // Game over - player busted
                        bjGameActive = false;
                        bjDealerRevealed = true;
                        document.getElementById('bjActions').style.display = 'none';
                        updateBlackjackDisplay();
                        
                        if (bjIsSplit) {
                            evaluateSplitResults();
                        } else {
                            endBlackjackRound('You busted! Dealer wins.');
                        }
                    }
                } else if (playerScore === 21) {
                    // Auto-stand on 21
                    document.getElementById('bjMessage').textContent = '';
                    stand();
                } else {
                    // Re-enable buttons (but disable double and split after first hit)
                    document.getElementById('bjHit').disabled = false;
                    document.getElementById('bjDouble').disabled = true;
                    document.getElementById('bjSplit').disabled = true;
                    document.getElementById('bjStand').disabled = false;
                    document.getElementById('bjMessage').textContent = '';
                }
            }, 400);
        }

        function split() {
            if (!bjGameActive) return;
            
            // Check if player can afford split
            if (coins < bjCurrentBet) {
                alert('Not enough coins to split!');
                return;
            }
            
            // Check if split is valid (two cards of same value)
            if (bjPlayerHand.length !== 2 || bjPlayerHand[0].numValue !== bjPlayerHand[1].numValue) {
                return;
            }
            
            // Deduct split bet
            coins -= bjCurrentBet;
            bjSplitBet = bjCurrentBet;
            localStorage.setItem('coins', coins);
            
            // Split the cards
            bjIsSplit = true;
            bjPlayerSplitHand = [bjPlayerHand.pop()];
            bjActiveHand = 'main';
            
            // Show split hand container
            document.getElementById('splitHandContainer').style.display = 'block';
            
            // Deal one card to each hand
            document.getElementById('bjMessage').textContent = 'Dealing cards to split hands...';
            document.getElementById('bjActions').style.display = 'none';
            
            setTimeout(() => {
                bjPlayerHand.push(bjDeck.pop());
                updateBlackjackDisplay();
                
                setTimeout(() => {
                    bjPlayerSplitHand.push(bjDeck.pop());
                    updateBlackjackDisplay();
                    document.getElementById('bjMessage').textContent = 'Playing first hand...';
                    
                    setTimeout(() => {
                        document.getElementById('bjActions').style.display = 'block';
                        document.getElementById('bjDouble').disabled = coins < bjCurrentBet;
                        document.getElementById('bjSplit').disabled = true;
                        document.getElementById('bjMessage').textContent = '';
                        updateCoinDisplay();
                        updateBlackjackDisplay();
                    }, 400);
                }, 400);
            }, 400);
        }

        function stand() {
            if (!bjGameActive) return;
            
            if (bjIsSplit && bjActiveHand === 'main') {
                // Move to second hand
                bjActiveHand = 'split';
                document.getElementById('bjMessage').textContent = 'Playing second hand...';
                // Re-enable all action buttons for the second hand
                document.getElementById('bjHit').disabled = false;
                document.getElementById('bjStand').disabled = false;
                document.getElementById('bjDouble').disabled = coins < bjSplitBet;
                document.getElementById('bjSplit').disabled = true;
                updateBlackjackDisplay();
                return;
            }
            
            bjDealerRevealed = true;
            bjGameActive = false;
            document.getElementById('bjActions').style.display = 'none';
            document.getElementById('bjMessage').textContent = 'Dealer is drawing...';
            
            const playerScore = calculateScore(bjPlayerHand);
            
            // Check if player already busted (shouldn't happen here, but safety check)
            if (playerScore > 21 && (!bjIsSplit || calculateScore(bjPlayerSplitHand) > 21)) {
                updateBlackjackDisplay();
                if (bjIsSplit) {
                    evaluateSplitResults();
                } else {
                    endBlackjackRound('You busted! Dealer wins.');
                }
                return;
            }
            
            // Reveal dealer's hidden card first
            updateBlackjackDisplay();
            playCardFlip();
            
            // Dealer draws cards with delays for suspense
            let delay = 800;
            const dealerDraw = () => {
                if (calculateScore(bjDealerHand) < 17) {
                    setTimeout(() => {
                        bjDealerHand.push(bjDeck.pop());
                        updateBlackjackDisplay();
                        playCardSound();
                        dealerDraw();
                    }, delay);
                } else {
                    // Determine winner after final card
                    setTimeout(() => {
                        if (bjIsSplit) {
                            evaluateSplitResults();
                        } else {
                            const dealerScore = calculateScore(bjDealerHand);
                            const playerHasBlackjack = isBlackjack(bjPlayerHand);
                            const dealerHasBlackjack = isBlackjack(bjDealerHand);
                            
                            // Check for blackjack scenarios
                            if (playerHasBlackjack && dealerHasBlackjack) {
                                endBlackjackRound('Both have Blackjack! Push.', bjCurrentBet);
                            } else if (playerHasBlackjack) {
                                // Blackjack pays 3:2 (bet + bet * 1.5)
                                const blackjackPayout = bjCurrentBet + Math.floor(bjCurrentBet * 1.5);
                                endBlackjackRound('🎉 BLACKJACK! 🎉', blackjackPayout);
                            } else if (dealerHasBlackjack) {
                                endBlackjackRound('Dealer has Blackjack. You lose.');
                            } else if (dealerScore > 21) {
                                endBlackjackRound('Dealer busts! You win!', bjCurrentBet * 2);
                            } else if (playerScore > dealerScore) {
                                endBlackjackRound('You win!', bjCurrentBet * 2);
                            } else if (playerScore === dealerScore) {
                                endBlackjackRound('Push! It\'s a tie.', bjCurrentBet);
                            } else {
                                endBlackjackRound('Dealer wins.');
                            }
                        }
                    }, 500);
                }
            };
            
            dealerDraw();
        }

        function evaluateSplitResults() {
            const dealerScore = calculateScore(bjDealerHand);
            const mainScore = calculateScore(bjPlayerHand);
            const splitScore = calculateScore(bjPlayerSplitHand);
            
            let totalWinnings = 0;
            let results = [];
            
            // Evaluate main hand
            if (mainScore > 21) {
                results.push('First hand busted');
            } else if (dealerScore > 21 || mainScore > dealerScore) {
                results.push('First hand wins!');
                totalWinnings += bjCurrentBet * 2;
            } else if (mainScore === dealerScore) {
                results.push('First hand pushes');
                totalWinnings += bjCurrentBet;
            } else {
                results.push('First hand loses');
            }
            
            // Evaluate split hand
            if (splitScore > 21) {
                results.push('Second hand busted');
            } else if (dealerScore > 21 || splitScore > dealerScore) {
                results.push('Second hand wins!');
                totalWinnings += bjSplitBet * 2;
            } else if (splitScore === dealerScore) {
                results.push('Second hand pushes');
                totalWinnings += bjSplitBet;
            } else {
                results.push('Second hand loses');
            }
            
            const message = results.join(', ');
            endBlackjackRound(message, totalWinnings);
        }

        function doubleDown() {
            if (!bjGameActive) return;
            
            const currentHand = bjActiveHand === 'main' ? bjPlayerHand : bjPlayerSplitHand;
            const isMainHand = bjActiveHand === 'main';
            const currentBet = isMainHand ? bjCurrentBet : bjSplitBet;
            
            // Check if player has enough coins to double
            if (coins < currentBet) {
                alert('Not enough coins to double down!');
                return;
            }
            
            // Disable all buttons during animation
            document.getElementById('bjHit').disabled = true;
            document.getElementById('bjDouble').disabled = true;
            document.getElementById('bjStand').disabled = true;
            document.getElementById('bjMessage').textContent = 'Doubling bet and drawing one card...';
            
            // Double the bet
            coins -= currentBet;
            if (isMainHand) {
                bjCurrentBet *= 2;
            } else {
                bjSplitBet *= 2;
            }
            localStorage.setItem('coins', coins);
            updateCoinDisplay();
            updateBlackjackDisplay();
            
            // Draw one card and automatically stand
            setTimeout(() => {
                currentHand.push(bjDeck.pop());
                updateBlackjackDisplay();
                playCardSound();
                
                const playerScore = calculateScore(currentHand);
                
                if (playerScore > 21) {
                    // Hand busted
                    if (bjIsSplit && bjActiveHand === 'main') {
                        // Move to split hand
                        document.getElementById('bjMessage').textContent = 'First hand busted! Playing second hand...';
                        bjActiveHand = 'split';
                        setTimeout(() => {
                            document.getElementById('bjHit').disabled = false;
                            document.getElementById('bjDouble').disabled = coins < bjSplitBet;
                            document.getElementById('bjSplit').disabled = true;
                            document.getElementById('bjStand').disabled = false;
                            document.getElementById('bjMessage').textContent = '';
                            updateBlackjackDisplay();
                        }, 800);
                    } else {
                        // Game over
                        bjGameActive = false;
                        bjDealerRevealed = true;
                        document.getElementById('bjActions').style.display = 'none';
                        updateBlackjackDisplay();
                        
                        if (bjIsSplit) {
                            evaluateSplitResults();
                        } else {
                            endBlackjackRound('You busted! Dealer wins.');
                        }
                    }
                } else {
                    // Automatically stand after double down
                    document.getElementById('bjMessage').textContent = '';
                    stand();
                }
            }, 400);
        }

        function endBlackjackRound(message, winnings = 0) {
            // Calculate profit (winnings minus the original bet)
            const profit = winnings - bjCurrentBet;
            
            // Update message to include winnings if player won
            if (winnings > 0 && profit > 0) {
                message += ` Total win: 🪙 ${winnings}`;
            } else if (winnings > 0 && profit === 0) {
                message += ` (Push - returned 🪙 ${winnings})`;
            }
            
            document.getElementById('bjMessage').textContent = message;
            document.getElementById('bjReplayActions').style.display = 'flex';
            
            if (winnings > 0) {
                coins += winnings;
                localStorage.setItem('coins', coins);
                updateCoinDisplay();
                updateBlackjackDisplay();
                playCasinoWin();
            } else {
                playCasinoLose();
            }
        }

        function newBlackjackRound() {
            bjCurrentBet = 0;
            bjPlayerHand = [];
            bjPlayerSplitHand = [];
            bjDealerHand = [];
            bjGameActive = false;
            bjDealerRevealed = false;
            bjIsSplit = false;
            bjActiveHand = 'main';
            bjSplitBet = 0;
            
            document.getElementById('bjBetSection').style.display = 'block';
            document.getElementById('bjTable').style.display = 'none';
            document.getElementById('bjMessage').textContent = '';
            document.getElementById('splitHandContainer').style.display = 'none';
            document.getElementById('bjReplayActions').style.display = 'none';
            
            updateBlackjackDisplay();
        }

        // ===== BACCARAT GAME =====
        function calculateBaccaratScore(hand) {
            let total = hand.reduce((sum, card) => sum + card.numValue, 0);
            return total % 10; // Baccarat uses last digit only
        }

        function startBaccaratRound(betOn, amount) {
            if (coins < amount || amount <= 0) {
                alert('Invalid bet amount!');
                return;
            }

            bacCurrentBet = amount;
            bacBetOn = betOn;
            bacLastBet = amount; // Track this bet for rebet
            bacLastBetOn = betOn; // Track bet type for rebet
            coins -= amount;
            localStorage.setItem('coins', coins);
            updateCoinDisplay();

            bacDeck = createDeck();
            bacPlayerHand = [];
            bacBankerHand = [];

            document.getElementById('bacBetSection').style.display = 'none';
            document.getElementById('bacTable').style.display = 'block';
            document.getElementById('bacReplayActions').style.display = 'none';
            document.getElementById('bacMessage').textContent = 'Dealing cards...';
            
            if (betOn === 'player') document.getElementById('bacPlayerBet').textContent = amount;
            if (betOn === 'banker') document.getElementById('bacBankerBet').textContent = amount;

            // Deal initial 4 cards with animation
            setTimeout(() => {
                bacPlayerHand.push(bacDeck.pop());
                updateBaccaratDisplay();
                playCardSound();
            }, 300);

            setTimeout(() => {
                bacBankerHand.push(bacDeck.pop());
                updateBaccaratDisplay();
                playCardSound();
            }, 600);

            setTimeout(() => {
                bacPlayerHand.push(bacDeck.pop());
                updateBaccaratDisplay();
                playCardSound();
            }, 900);

            setTimeout(() => {
                bacBankerHand.push(bacDeck.pop());
                updateBaccaratDisplay();
                playCardFlip();
                evaluateBaccarat();
            }, 1200);
        }

        function evaluateBaccarat() {
            let playerScore = calculateBaccaratScore(bacPlayerHand);
            let bankerScore = calculateBaccaratScore(bacBankerHand);

            document.getElementById('bacMessage').textContent = 'Evaluating...';

            // Check for natural (8 or 9)
            if (playerScore >= 8 || bankerScore >= 8) {
                setTimeout(() => resolveBaccarat(), 800);
                return;
            }

            // Player third card rule
            if (playerScore <= 5) {
                setTimeout(() => {
                    bacPlayerHand.push(bacDeck.pop());
                    updateBaccaratDisplay();
                    playCardSound();
                    playerScore = calculateBaccaratScore(bacPlayerHand);
                    
                    const playerThird = bacPlayerHand[2]?.numValue || 0;
                    let bankerDraws = false;

                    if (bankerScore <= 2) bankerDraws = true;
                    else if (bankerScore === 3 && playerThird !== 8) bankerDraws = true;
                    else if (bankerScore === 4 && [2,3,4,5,6,7].includes(playerThird)) bankerDraws = true;
                    else if (bankerScore === 5 && [4,5,6,7].includes(playerThird)) bankerDraws = true;
                    else if (bankerScore === 6 && [6,7].includes(playerThird)) bankerDraws = true;

                    if (bankerDraws) {
                        setTimeout(() => {
                            bacBankerHand.push(bacDeck.pop());
                            updateBaccaratDisplay();
                            playCardSound();
                            setTimeout(() => resolveBaccarat(), 800);
                        }, 800);
                    } else {
                        setTimeout(() => resolveBaccarat(), 800);
                    }
                }, 800);
            } else {
                if (bankerScore <= 5) {
                    setTimeout(() => {
                        bacBankerHand.push(bacDeck.pop());
                        updateBaccaratDisplay();
                        playCardSound();
                        setTimeout(() => resolveBaccarat(), 800);
                    }, 800);
                } else {
                    setTimeout(() => resolveBaccarat(), 800);
                }
            }
        }

        function resolveBaccarat() {
            const playerScore = calculateBaccaratScore(bacPlayerHand);
            const bankerScore = calculateBaccaratScore(bacBankerHand);
            
            let message = '';
            let winnings = 0;

            if (playerScore === bankerScore) {
                if (bacBetOn === 'tie') {
                    message = `Tie! Player: ${playerScore}, Banker: ${bankerScore} - You win!`;
                    winnings = bacCurrentBet * 9; // 8:1 payout plus original bet
                } else {
                    message = `Tie! Player: ${playerScore}, Banker: ${bankerScore} - Push`;
                    winnings = bacCurrentBet;
                }
            } else if (playerScore > bankerScore) {
                if (bacBetOn === 'player') {
                    message = `Player wins ${playerScore} to ${bankerScore}! You win!`;
                    winnings = bacCurrentBet * 2;
                } else {
                    message = `Player wins ${playerScore} to ${bankerScore}. You lose.`;
                }
            } else {
                if (bacBetOn === 'banker') {
                    message = `Banker wins ${bankerScore} to ${playerScore}! You win!`;
                    winnings = Math.floor(bacCurrentBet * 1.95); // 5% commission
                } else {
                    message = `Banker wins ${bankerScore} to ${playerScore}. You lose.`;
                }
            }

            document.getElementById('bacMessage').textContent = message;
            document.getElementById('bacReplayActions').style.display = 'flex';

            if (winnings > 0) {
                // Add total win amount to message
                const profit = winnings - bacCurrentBet;
                if (profit > 0) {
                    document.getElementById('bacMessage').textContent += ` Total win: 🪙 ${winnings}`;
                } else if (profit === 0) {
                    document.getElementById('bacMessage').textContent += ` (Push - returned 🪙 ${winnings})`;
                }
                
                coins += winnings;
                localStorage.setItem('coins', coins);
                updateCoinDisplay();
                playCasinoWin();
            } else {
                playCasinoLose();
            }
        }

        function updateBaccaratDisplay() {
            document.getElementById('bacCoins').textContent = coins;
            
            // Render player cards with animation
            const playerCardsHTML = bacPlayerHand.map((card, i) => {
                const isNew = i >= bacPrevPlayerCount;
                return renderCard(card, false, isNew);
            }).join('');
            document.getElementById('bacPlayerCards').innerHTML = playerCardsHTML;
            document.getElementById('bacPlayerScore').textContent = `Score: ${calculateBaccaratScore(bacPlayerHand)}`;

            // Render banker cards with animation
            const bankerCardsHTML = bacBankerHand.map((card, i) => {
                const isNew = i >= bacPrevBankerCount;
                return renderCard(card, false, isNew);
            }).join('');
            document.getElementById('bacBankerCards').innerHTML = bankerCardsHTML;
            document.getElementById('bacBankerScore').textContent = `Score: ${calculateBaccaratScore(bacBankerHand)}`;
            
            // Update card counts after rendering
            bacPrevPlayerCount = bacPlayerHand.length;
            bacPrevBankerCount = bacBankerHand.length;
        }

        function newBaccaratRound() {
            bacCurrentBet = 0;
            bacPlayerHand = [];
            bacBankerHand = [];
            bacBetOn = '';
            
            // Reset card animation tracking
            bacPrevPlayerCount = 0;
            bacPrevBankerCount = 0;
            
            document.getElementById('bacBetSection').style.display = 'block';
            document.getElementById('bacTable').style.display = 'none';
            document.getElementById('bacMessage').textContent = '';
            document.getElementById('bacBetInput').value = '';
            document.getElementById('bacPlayerBet').textContent = '0';
            document.getElementById('bacBankerBet').textContent = '0';
            document.getElementById('bacReplayActions').style.display = 'none';
        }

        // ===== ROULETTE GAME =====
        // === ROULETTE: Canvas wheel ===
        const rouOrder = [0,32,15,19,4,21,2,25,17,34,6,27,13,36,11,30,8,23,10,5,24,16,33,1,20,14,31,9,22,18,29,7,28,12,35,3,26];
        const rouWheelCanvas = document.getElementById('rouWheelCanvas');
        const rouCtx = rouWheelCanvas.getContext('2d');
        let rouAngle = 0;
        let rouSpinning = false;
        let rouTargetAngle = 0;
        let rouSpinStart = 0;
        const ROU_SPIN_DURATION = 3500;
        let rouResultNum = -1;

        function rouColor(n) {
            if (n === 0) return '#0a7e2e';
            return rouReds.includes(n) ? '#b71c1c' : '#1a1a2e';
        }

        let rouBallAngle = null; // null = no ball shown
        let rouBallStartAngle = 0; // Starting angle for ball animation

        function drawRouWheel(angle) {
            const w = rouWheelCanvas.width, h = rouWheelCanvas.height;
            const cx = w / 2, cy = h / 2;
            const outerR = 110;
            const innerR = 36;
            const numR = 82;
            const sliceAngle = (Math.PI * 2) / 37;
            
            rouCtx.clearRect(0, 0, w, h);
            
            // Outer gold bezel
            rouCtx.beginPath();
            rouCtx.arc(cx, cy, outerR + 4, 0, Math.PI * 2);
            rouCtx.fillStyle = '#9a8520';
            rouCtx.fill();
            
            rouCtx.beginPath();
            rouCtx.arc(cx, cy, outerR + 1, 0, Math.PI * 2);
            rouCtx.fillStyle = '#222';
            rouCtx.fill();
            
            // Draw slices
            for (let i = 0; i < 37; i++) {
                const num = rouOrder[i];
                const a1 = angle + i * sliceAngle;
                const a2 = a1 + sliceAngle;
                
                rouCtx.beginPath();
                rouCtx.moveTo(cx, cy);
                rouCtx.arc(cx, cy, outerR, a1, a2);
                rouCtx.closePath();
                rouCtx.fillStyle = rouColor(num);
                rouCtx.fill();
                
                rouCtx.beginPath();
                rouCtx.moveTo(cx, cy);
                rouCtx.arc(cx, cy, outerR, a1, a2);
                rouCtx.closePath();
                rouCtx.strokeStyle = 'rgba(200,180,80,0.25)';
                rouCtx.lineWidth = 0.5;
                rouCtx.stroke();
                
                // Number text
                const textAngle = a1 + sliceAngle / 2;
                const tx = cx + Math.cos(textAngle) * numR;
                const ty = cy + Math.sin(textAngle) * numR;
                
                rouCtx.save();
                rouCtx.translate(tx, ty);
                rouCtx.rotate(textAngle + Math.PI / 2);
                rouCtx.fillStyle = '#fff';
                rouCtx.font = 'bold 10px Arial, sans-serif';
                rouCtx.textAlign = 'center';
                rouCtx.textBaseline = 'middle';
                rouCtx.fillText(String(num), 0, 0);
                rouCtx.restore();
            }
            
            // Inner dark ring
            rouCtx.beginPath();
            rouCtx.arc(cx, cy, innerR + 8, 0, Math.PI * 2);
            rouCtx.fillStyle = '#1a1a1a';
            rouCtx.fill();
            
            // Center hub
            rouCtx.beginPath();
            rouCtx.arc(cx, cy, innerR, 0, Math.PI * 2);
            rouCtx.fillStyle = '#0b6e22';
            rouCtx.fill();
            rouCtx.strokeStyle = 'rgba(255,215,0,0.3)';
            rouCtx.lineWidth = 2;
            rouCtx.stroke();
            
            rouCtx.beginPath();
            rouCtx.arc(cx, cy, 18, 0, Math.PI * 2);
            rouCtx.fillStyle = '#0d8a2c';
            rouCtx.fill();
            
            // Ball (spinning or resting)
            if (rouBallAngle !== null) {
                const ballR = outerR - 14;
                const bx = cx + Math.cos(rouBallAngle) * ballR;
                const by = cy + Math.sin(rouBallAngle) * ballR;
                rouCtx.beginPath();
                rouCtx.arc(bx, by, 6, 0, Math.PI * 2);
                rouCtx.fillStyle = '#f0f0f0';
                rouCtx.fill();
                rouCtx.strokeStyle = 'rgba(0,0,0,0.4)';
                rouCtx.lineWidth = 1.5;
                rouCtx.stroke();
            }
        }

        let rouStartAngle = 0;

        let rouLastTickAngle = 0;
        function animateRouWheel() {
            if (!rouSpinning) {
                drawRouWheel(rouAngle);
                return;
            }
            const elapsed = Date.now() - rouSpinStart;
            const t = Math.min(elapsed / ROU_SPIN_DURATION, 1);
            const ease = 1 - Math.pow(1 - t, 3);
            rouAngle = rouStartAngle + ease * (rouTargetAngle - rouStartAngle);
            
            // Tick sound as ball passes slots
            const sliceAngle = (Math.PI * 2) / 37;
            const angleDiff = Math.abs(rouAngle - rouLastTickAngle);
            if (angleDiff > sliceAngle * 0.9 && t < 0.9) {
                rouLastTickAngle = rouAngle;
                playRouletteTick();
            }
            
            // Ball: spins independently and lands in the winning slot at a fixed screen position
            const slotIndex = rouOrder.indexOf(rouResultNum);
            
            // Ball does its own fast orbit (opposite to wheel), then decelerates to land
            // Total ball travel: many rotations counter-clockwise
            const ballTotalSpin = -Math.PI * 16; // big counter-clockwise travel
            // Ball starts at a random position and ends at the final slot position
            const ballStart = rouBallStartAngle;
            const ballEase = 1 - Math.pow(1 - t, 2.5); // slightly different easing for ball
            
            // Calculate where the winning slot is in wheel-space
            const winningSlotAngleInWheel = slotIndex * sliceAngle + sliceAngle / 2;
            // At the end, ball angle in screen space = wheel angle + slot angle in wheel
            const finalBallAngle = rouAngle + winningSlotAngleInWheel;
            
            // Ball travels from start position to final position
            rouBallAngle = ballStart + ballEase * (finalBallAngle + ballTotalSpin - ballStart);
            
            drawRouWheel(rouAngle);
            
            if (t < 1) {
                requestAnimationFrame(animateRouWheel);
            } else {
                rouSpinning = false;
                rouAngle = rouTargetAngle;
                rouAngle = rouAngle % (Math.PI * 2);
                // Ball rests exactly on winning slot
                rouBallAngle = rouAngle + slotIndex * sliceAngle + sliceAngle / 2;
                drawRouWheel(rouAngle);
                resolveRoulette(rouResultNum);
            }
        }

        drawRouWheel(0);

        function initRouletteBoard() {
            const grid = document.getElementById('rouBetGrid');
            grid.innerHTML = '';
            
            // Zero spanning full row
            const zeroBtn = document.createElement('button');
            zeroBtn.setAttribute('data-number', '0');
            zeroBtn.textContent = '0';
            Object.assign(zeroBtn.style, {
                background: '#0a5e1e', color: '#4ade80', border: '2px solid #1a8a3e', borderRadius: '4px',
                padding: '5px 2px', fontSize: '11px', fontWeight: '800', cursor: 'pointer',
                gridColumn: 'span 12', fontFamily: 'inherit'
            });
            grid.appendChild(zeroBtn);
            
            // Numbers 1-36 in 3 rows of 12 (standard table layout)
            for (let i = 1; i <= 36; i++) {
                const isRed = rouReds.includes(i);
                const btn = document.createElement('button');
                btn.setAttribute('data-number', String(i));
                btn.textContent = i;
                Object.assign(btn.style, {
                    background: isRed ? '#7b1a1a' : '#1a1a2e',
                    color: isRed ? '#ffa0a0' : '#bbb',
                    border: isRed ? '1.5px solid #992a2a' : '1.5px solid #333',
                    borderRadius: '4px', padding: '4px 1px', fontSize: '11px', fontWeight: '800',
                    cursor: 'pointer', fontFamily: 'inherit', minWidth: '0'
                });
                grid.appendChild(btn);
            }

            grid.querySelectorAll('button').forEach(btn => {
                btn.addEventListener('click', () => {
                    const amount = parseInt(document.getElementById('rouBetInput').value);
                    if (!amount || amount <= 0 || amount > coins) return;
                    addRouletteBet('number', parseInt(btn.getAttribute('data-number')), amount);
                    // Highlight selected
                    btn.style.outline = '2px solid #FFD700';
                    btn.style.outlineOffset = '-2px';
                });
            });
        }

        function addRouletteBet(type, value, amount) {
            rouBets.push({type, value, amount});
            updateRouletteBets();
            playChipPlace();
        }

        function updateRouletteBets() {
            const total = rouBets.reduce((sum, bet) => sum + bet.amount, 0);
            const summary = document.getElementById('rouBetsSummary');
            if (rouBets.length === 0) { summary.innerHTML = ''; return; }
            const betNames = rouBets.map(b => b.type === 'number' ? `#${b.value} 🪙${b.amount}` : `${b.type} 🪙${b.amount}`);
            summary.innerHTML = `<span style="color:rgba(255,215,0,0.7)">${betNames.join(', ')} — Total: <b style="color:#FFD700">🪙${total}</b></span>`;
        }

        function clearRouletteBets() {
            rouBets = [];
            updateRouletteBets();
            // Remove highlights
            document.getElementById('rouBetGrid').querySelectorAll('button').forEach(btn => {
                btn.style.outline = 'none';
            });
        }

        function spinRoulette() {
            if (rouSpinning) return;
            if (rouBets.length === 0) {
                document.getElementById('rouMessage').textContent = 'Place a bet first!';
                return;
            }
            const totalBet = rouBets.reduce((sum, bet) => sum + bet.amount, 0);
            if (totalBet > coins) {
                document.getElementById('rouMessage').textContent = 'Not enough coins!';
                return;
            }

            coins -= totalBet;
            localStorage.setItem('coins', coins);
            updateCoinDisplay();
            document.getElementById('rouCoins').textContent = coins;
            document.getElementById('rouMessage').textContent = 'Spinning...';
            document.getElementById('rouResult').textContent = '';
            document.getElementById('rouSpin').disabled = true;

            // Pick result
            rouResultNum = Math.floor(Math.random() * 37);
            const slotIndex = rouOrder.indexOf(rouResultNum);
            const sliceAngle = (Math.PI * 2) / 37;
            
            // Random final angle for the wheel (no fixed pointer position)
            const randomFinalAngle = Math.random() * Math.PI * 2;
            
            // Add full rotations for visual spin
            const fullSpins = (5 + Math.random() * 3) * Math.PI * 2;
            
            rouStartAngle = rouAngle;
            rouTargetAngle = rouStartAngle + fullSpins + randomFinalAngle;
            
            // Ball starts at a random position
            rouBallStartAngle = Math.random() * Math.PI * 2;
            
            rouSpinning = true;
            rouSpinStart = Date.now();
            animateRouWheel();
        }

        function resolveRoulette(result) {
            const isRed = rouReds.includes(result);
            const colorEmoji = result === 0 ? '🟢' : (isRed ? '🔴' : '⚫');
            document.getElementById('rouResult').textContent = `${colorEmoji} ${result}`;
            playRouletteLand();
            
            let totalWin = 0;
            rouBets.forEach(bet => {
                if (bet.type === 'number' && bet.value === result) totalWin += bet.amount * 36;
                else if (bet.type === 'red' && isRed && result !== 0) totalWin += bet.amount * 2;
                else if (bet.type === 'black' && !isRed && result !== 0) totalWin += bet.amount * 2;
                else if (bet.type === 'even' && result % 2 === 0 && result !== 0) totalWin += bet.amount * 2;
                else if (bet.type === 'odd' && result % 2 === 1) totalWin += bet.amount * 2;
            });

            if (totalWin > 0) {
                coins += totalWin;
                localStorage.setItem('coins', coins);
                updateCoinDisplay();
                document.getElementById('rouCoins').textContent = coins;
                document.getElementById('rouMessage').innerHTML = `<span style="color:#4ade80">Won 🪙 ${totalWin}!</span>`;
                playCasinoWin();
            } else {
                document.getElementById('rouMessage').textContent = 'No luck this time.';
                playCasinoLose();
            }

            rouBets = [];
            updateRouletteBets();
            // Remove highlights
            document.getElementById('rouBetGrid').querySelectorAll('button').forEach(btn => {
                btn.style.outline = 'none';
            });
            document.getElementById('rouSpin').disabled = false;
        }

        // ===== SLOT MACHINE GAME =====
        const slotSymbols = ['🍒', '🍋', '🍊', '🔔', '💎', '🎰'];

        function spinSlots() {
            const bet = parseInt(document.getElementById('slotsBetInput').value);
            if (!bet || bet <= 0) {
                alert('Please enter a valid bet amount!');
                return;
            }
            
            if (bet > coins) {
                alert('Not enough coins!');
                return;
            }

            // Deduct coins BEFORE spinning
            coins -= bet;
            localStorage.setItem('coins', coins);
            updateCoinDisplay();
            document.getElementById('slotsCoins').textContent = coins;

            document.getElementById('slotsSpin').disabled = true;
            document.getElementById('slotsMessage').textContent = 'Spinning...';
            playSlotSpin();

            const reels = ['slot1', 'slot2', 'slot3'];
            const results = [];
            
            reels.forEach((reelId, index) => {
                let spins = 0;
                const maxSpins = 20 + (index * 5);
                const interval = setInterval(() => {
                    document.getElementById(reelId).textContent = slotSymbols[Math.floor(Math.random() * slotSymbols.length)];
                    spins++;
                    if (spins % 3 === 0) playSlotTick();
                    
                    if (spins >= maxSpins) {
                        clearInterval(interval);
                        const finalSymbol = slotSymbols[Math.floor(Math.random() * slotSymbols.length)];
                        document.getElementById(reelId).textContent = finalSymbol;
                        results.push(finalSymbol);
                        playSlotStop();
                        
                        if (results.length === 3) {
                            evaluateSlots(results, bet);
                        }
                    }
                }, 100);
            });
        }

        function evaluateSlots(results, bet) {
            let winnings = 0;
            let message = '';

            // Check for 3 of a kind
            if (results[0] === results[1] && results[1] === results[2]) {
                const symbol = results[0];
                const multipliers = {'🍒': 10, '🍋': 15, '🍊': 20, '🔔': 30, '💎': 50, '🎰': 100};
                const multiplier = multipliers[symbol];
                winnings = bet * multiplier;
                message = multiplier === 100 ? '🎉 JACKPOT! 🎉' : `${symbol}${symbol}${symbol} - ${multiplier}x WIN!`;
            }
            // Check for 2 of a kind
            else if (results[0] === results[1] || results[1] === results[2] || results[0] === results[2]) {
                winnings = bet * 2;
                message = 'Two matching - 2x!';
            }
            else {
                message = 'No match - Try again!';
            }

            if (winnings > 0) {
                coins += winnings;
                localStorage.setItem('coins', coins);
                updateCoinDisplay();
                document.getElementById('slotsCoins').textContent = coins;
                document.getElementById('slotsMessage').textContent = `${message} Won 🪙 ${winnings}!`;
                if (message.includes('JACKPOT')) playJackpot(); else playCasinoWin();
            } else {
                document.getElementById('slotsMessage').textContent = message;
                playCasinoLose();
            }

            document.getElementById('slotsSpin').disabled = false;
        }

        // Update coin display
        function updateCoinDisplay() {
            document.getElementById('coinCount').textContent = coinsThisRun;
            document.getElementById('shopCoins').textContent = coins;
            document.getElementById('shopCoinCount').textContent = coins;
            
            const bjCoinsElement = document.getElementById('bjCoins');
            if (bjCoinsElement) {
                bjCoinsElement.textContent = coins;
            }
        }
        
        function cheatCoins(amount) {
            coins += amount;
            localStorage.setItem('coins', coins);
            updateCoinDisplay();
        }

        // Draw mini bird for shop preview
        function drawMiniBird(skinKey, canvasId) {
            const canvas = document.getElementById(canvasId);
            if (!canvas) return;
            
            const ctx = canvas.getContext('2d');
            const skin = birdSkins[skinKey];
            const w = canvas.width, h = canvas.height;
            
            ctx.clearRect(0, 0, w, h);
            
            // Sky gradient background
            const skyGrad = ctx.createLinearGradient(0, 0, 0, h);
            skyGrad.addColorStop(0, '#5b9bd5');
            skyGrad.addColorStop(1, '#a8d8ea');
            ctx.fillStyle = skyGrad;
            ctx.fillRect(0, 0, w, h);
            
            // Tiny cloud
            ctx.fillStyle = 'rgba(255,255,255,0.5)';
            ctx.beginPath();
            ctx.arc(16, 14, 6, 0, Math.PI * 2);
            ctx.arc(23, 12, 8, 0, Math.PI * 2);
            ctx.arc(30, 14, 6, 0, Math.PI * 2);
            ctx.fill();
            
            // Ground strip
            ctx.fillStyle = '#7ec87e';
            ctx.fillRect(0, h - 8, w, 8);
            ctx.fillStyle = '#5da65d';
            ctx.fillRect(0, h - 8, w, 2);
            
            ctx.save();
            ctx.translate(w / 2, h / 2 - 2);
            ctx.scale(1.15, 1.15);
            
            // Shadow
            ctx.fillStyle = 'rgba(0,0,0,0.12)';
            ctx.beginPath();
            ctx.ellipse(1, 12, 13, 4, 0, 0, Math.PI * 2);
            ctx.fill();
            
            // Bird body
            ctx.fillStyle = skin.body;
            ctx.beginPath();
            ctx.ellipse(0, 0, 14, 10, 0, 0, Math.PI * 2);
            ctx.fill();
            
            // Body highlight
            ctx.fillStyle = skin.bodyGradient;
            ctx.beginPath();
            ctx.ellipse(-3, -3, 9, 6, -0.2, 0, Math.PI * 2);
            ctx.fill();
            
            // Belly
            ctx.fillStyle = skin.belly;
            ctx.beginPath();
            ctx.ellipse(2, 3, 8, 6, 0, 0, Math.PI * 2);
            ctx.fill();
            
            // Wing
            ctx.fillStyle = skin.wing;
            ctx.beginPath();
            ctx.ellipse(-5, 2, 8, 5, -0.3, 0, Math.PI * 2);
            ctx.fill();
            
            // Wing detail
            ctx.fillStyle = skin.wingDetail;
            ctx.beginPath();
            ctx.ellipse(-6, 3, 5, 3, -0.3, 0, Math.PI * 2);
            ctx.fill();
            
            // Eye white
            ctx.fillStyle = 'white';
            ctx.beginPath();
            ctx.arc(6, -4, 4.5, 0, Math.PI * 2);
            ctx.fill();
            
            // Eye pupil
            ctx.fillStyle = '#111';
            ctx.beginPath();
            ctx.arc(7.5, -4, 2.5, 0, Math.PI * 2);
            ctx.fill();
            
            // Eye shine
            ctx.fillStyle = 'white';
            ctx.beginPath();
            ctx.arc(8.5, -5, 1, 0, Math.PI * 2);
            ctx.fill();
            
            // Beak top
            ctx.fillStyle = skin.beak;
            ctx.beginPath();
            ctx.moveTo(10, -3);
            ctx.lineTo(17, -2);
            ctx.lineTo(11, 0);
            ctx.closePath();
            ctx.fill();
            
            // Beak bottom
            ctx.fillStyle = skin.beakBottom || skin.beak;
            ctx.beginPath();
            ctx.moveTo(10, 0);
            ctx.lineTo(15, 1);
            ctx.lineTo(11, 2);
            ctx.closePath();
            ctx.fill();
            
            // Special accessories
            if (skinKey === 'golden') {
                ctx.fillStyle = 'rgba(255, 255, 200, 0.7)';
                for (let s = 0; s < 4; s++) {
                    const sx = Math.sin(s * 1.5) * 14;
                    const sy = Math.cos(s * 2.1) * 10;
                    ctx.beginPath();
                    ctx.arc(sx, sy, 1.2, 0, Math.PI * 2);
                    ctx.fill();
                }
            }
            
            if (skinKey === 'dictator') {
                // Mini peaked cap
                ctx.fillStyle = '#2a2a1a';
                ctx.beginPath();
                ctx.ellipse(3, -9, 12, 3, -0.1, 0, Math.PI * 2);
                ctx.fill();
                ctx.fillStyle = '#3a3a28';
                ctx.beginPath();
                ctx.moveTo(-5, -9);
                ctx.quadraticCurveTo(-3, -18, 3, -19);
                ctx.quadraticCurveTo(10, -18, 12, -9);
                ctx.closePath();
                ctx.fill();
                ctx.fillStyle = '#8B0000';
                ctx.fillRect(-4, -11, 15, 2);
                ctx.fillStyle = '#FFD700';
                ctx.font = 'bold 5px sans-serif';
                ctx.textAlign = 'center';
                ctx.fillText('★', 3, -15);
                
                // Mini mustache
                ctx.fillStyle = '#1a1a0a';
                ctx.beginPath();
                ctx.ellipse(13, 1, 3, 1.2, 0.2, 0, Math.PI * 2);
                ctx.fill();
                
                // Mini medals
                ctx.fillStyle = '#FFD700';
                ctx.beginPath();
                ctx.arc(-1, 5, 1.8, 0, Math.PI * 2);
                ctx.fill();
                ctx.fillStyle = '#C0C0C0';
                ctx.beginPath();
                ctx.arc(3, 5, 1.5, 0, Math.PI * 2);
                ctx.fill();
            }
            
            ctx.restore();
        }

        // Render shop items
        let shopTab = 'skins';
        
        function renderShop() {
            const shopItems = document.getElementById('shopItems');
            const shopTrails = document.getElementById('shopTrails');
            
            // Tab switching
            document.querySelectorAll('.shop-tab').forEach(tab => {
                tab.classList.toggle('active', tab.dataset.tab === shopTab);
                tab.onclick = () => {
                    shopTab = tab.dataset.tab;
                    renderShop();
                };
            });
            
            shopItems.style.display = shopTab === 'skins' ? '' : 'none';
            shopTrails.style.display = shopTab === 'trails' ? '' : 'none';
            
            if (shopTab === 'skins') {
                renderShopSkins(shopItems);
            } else {
                renderShopTrails(shopTrails);
            }
        }
        
        function renderShopSkins(container) {
            container.innerHTML = '';
            Object.keys(birdSkins).forEach((skinKey) => {
                const skin = birdSkins[skinKey];
                const item = document.createElement('div');
                item.className = 'shop-item' + (skin.unlocked ? ' owned' : '');
                const canvasId = `shop-bird-${skinKey}`;
                item.innerHTML = `
                    <div class="shop-item-left">
                        <div class="shop-item-preview">
                            <canvas id="${canvasId}" width="80" height="64" class="shop-bird-mini"></canvas>
                        </div>
                        <div class="shop-item-info">
                            <div class="shop-item-name">${skin.name}</div>
                            <div class="shop-item-price">🪙 ${skin.price}</div>
                        </div>
                    </div>
                    ${skin.unlocked ? 
                        '<div class="owned-badge">OWNED</div>' : 
                        `<button class="shop-buy-btn" data-skin="${skinKey}" ${coins < skin.price ? 'disabled' : ''}>
                            ${coins >= skin.price ? 'Buy' : '🔒 Need more'}
                        </button>`
                    }
                `;
                container.appendChild(item);
                setTimeout(() => drawMiniBird(skinKey, canvasId), 10);
            });
            
            document.querySelectorAll('.shop-buy-btn').forEach(btn => {
                btn.addEventListener('click', () => {
                    const skinKey = btn.dataset.skin;
                    const skin = birdSkins[skinKey];
                    if (coins >= skin.price && !skin.unlocked) {
                        coins -= skin.price;
                        localStorage.setItem('coins', coins);
                        localStorage.setItem(`unlocked_${skinKey}`, 'true');
                        birdSkins[skinKey].unlocked = true;
                        updateCoinDisplay();
                        renderShop();
                        updateSkinSelector();
                        playScoreSound();
                    }
                });
            });
        }
        
        function renderShopTrails(container) {
            container.innerHTML = '';
            Object.keys(birdTrails).forEach((trailKey) => {
                const trail = birdTrails[trailKey];
                const item = document.createElement('div');
                const isEquipped = currentTrail === trailKey;
                item.className = 'shop-item' + (trail.unlocked && trailKey !== 'none' ? ' owned' : '') + (isEquipped ? ' equipped' : '');
                
                // Trail color preview
                let previewHTML = '';
                if (trail.color === null) {
                    previewHTML = '<div style="width:48px;height:48px;border-radius:50%;background:rgba(255,255,255,0.06);border:1px dashed rgba(255,255,255,0.15);display:flex;align-items:center;justify-content:center;font-size:20px;">✕</div>';
                } else if (trail.color === 'rainbow') {
                    previewHTML = '<div style="width:48px;height:48px;border-radius:50%;background:conic-gradient(#f00,#ff0,#0f0,#0ff,#00f,#f0f,#f00);opacity:0.8;"></div>';
                } else {
                    previewHTML = `<div style="width:48px;height:48px;border-radius:50%;background:radial-gradient(circle, rgba(${trail.color},0.8), rgba(${trail.color},0.2));box-shadow:0 0 12px rgba(${trail.color},0.3);"></div>`;
                }
                
                let actionHTML = '';
                if (isEquipped) {
                    actionHTML = '<div class="equipped-badge">EQUIPPED</div>';
                } else if (trail.unlocked) {
                    actionHTML = `<button class="shop-equip-btn" data-trail="${trailKey}">Equip</button>`;
                } else {
                    actionHTML = `<button class="shop-buy-trail-btn" data-trail="${trailKey}" ${coins < trail.price ? 'disabled' : ''}>
                        ${trail.price === 0 ? 'Free' : (coins >= trail.price ? `🪙 ${trail.price}` : '🔒 Need more')}
                    </button>`;
                }
                
                item.innerHTML = `
                    <div class="shop-item-left">
                        <div class="shop-item-preview">${previewHTML}</div>
                        <div class="shop-item-info">
                            <div class="shop-item-name">${trail.name}</div>
                            <div class="shop-item-price">${trail.price === 0 ? 'Free' : '🪙 ' + trail.price}</div>
                        </div>
                    </div>
                    ${actionHTML}
                `;
                container.appendChild(item);
            });
            
            // Buy trail listeners
            document.querySelectorAll('.shop-buy-trail-btn').forEach(btn => {
                btn.addEventListener('click', () => {
                    const trailKey = btn.dataset.trail;
                    const trail = birdTrails[trailKey];
                    if (coins >= trail.price && !trail.unlocked) {
                        coins -= trail.price;
                        localStorage.setItem('coins', coins);
                        localStorage.setItem(`trail_${trailKey}`, 'true');
                        birdTrails[trailKey].unlocked = true;
                        currentTrail = trailKey;
                        localStorage.setItem('birdTrail', currentTrail);
                        updateCoinDisplay();
                        renderShop();
                        playScoreSound();
                    }
                });
            });
            
            // Equip trail listeners
            document.querySelectorAll('.shop-equip-btn').forEach(btn => {
                btn.addEventListener('click', () => {
                    currentTrail = btn.dataset.trail;
                    localStorage.setItem('birdTrail', currentTrail);
                    renderShop();
                });
            });
        }

        // Start game function
        function startGame() {
            gameStarted = true;
            document.getElementById('startScreen').style.display = 'none';
            document.getElementById('coinCounter').classList.add('show');
            document.getElementById('volumeControl').classList.add('hidden');
        }

        // Restart game function
        function restartGame() {
            gameOver = false;
            gameStarted = true;
            firstJump = false;
            score = 0;
            frameCount = 0;
            lastPipeFrame = -120;
            pipes = [];
            feathers = [];
            jumpCount = 0;
            coinObjects = [];
            coinsThisRun = 0;
            trailParticles = [];
            eggs = [];
            lastEggScore = 0;
            bird.y = 250;
            bird.velocity = 0;
            
            document.getElementById('score').textContent = '0';
            document.getElementById('gameOver').style.display = 'none';
            document.getElementById('coinCounter').classList.add('show');
            document.getElementById('volumeControl').classList.add('hidden');
            updateCoinDisplay();
            
            playBackgroundMusic();
        }

        // End game function
        function endGame() {
            gameOver = true;
            stopBackgroundMusic();
            playGameOverSound();
            
            document.getElementById('finalScore').textContent = 'Score: ' + score;
            document.getElementById('finalHighScore').textContent = 'High Score: ' + highScore;
            document.getElementById('coinsThisGame').textContent = coinsThisRun;
            document.getElementById('totalCoinsDisplay').textContent = coins;
            document.getElementById('gameOver').style.display = 'block';
            document.getElementById('coinCounter').classList.remove('show');
            document.getElementById('volumeControl').classList.remove('hidden');
            
            updateCoinDisplay();
        }

        // Update skin selector to show only unlocked birds with previews
        function updateSkinSelector() {
            const container = document.getElementById('skinOptionsContainer');
            container.innerHTML = '';
            
            Object.keys(birdSkins).forEach(skinKey => {
                const skin = birdSkins[skinKey];
                if (skin.unlocked) {
                    const option = document.createElement('div');
                    option.className = 'skin-option';
                    option.dataset.skin = skinKey;
                    
                    if (skinKey === currentBirdSkin) {
                        option.classList.add('selected');
                    }
                    
                    const canvasId = `skin-preview-${skinKey}`;
                    option.innerHTML = `
                        <canvas id="${canvasId}" width="100" height="75"></canvas>
                        <div class="skin-option-name">${skin.name}</div>
                    `;
                    
                    container.appendChild(option);
                    
                    // Draw bird preview after element is added to DOM
                    setTimeout(() => drawMiniBird(skinKey, canvasId), 10);
                }
            });
        }

        // Initialize high score display
        document.getElementById('highScore').textContent = 'High Score: ' + highScore;
        updateCoinDisplay();
        renderShop();
        updateSkinSelector();

        // Skin selector functionality
        const skinSelector = document.getElementById('skinSelector');
        const skinButton = document.getElementById('skinButton');
        const skinButtonGameOver = document.getElementById('skinButtonGameOver');
        const closeSkinSelector = document.getElementById('closeSkinSelector');
        
        // Delegate event handling for dynamically created skin options
        document.getElementById('skinOptionsContainer').addEventListener('click', (e) => {
            // Find the skin-option element (could be the target or a parent)
            const skinOption = e.target.closest('.skin-option');
            
            if (skinOption) {
                const selectedSkin = skinOption.dataset.skin;
                
                // Check if skin is unlocked
                if (!birdSkins[selectedSkin].unlocked) {
                    alert('You need to buy this bird in the shop first!');
                    return;
                }
                
                // Remove selected from all
                document.querySelectorAll('.skin-option').forEach(o => o.classList.remove('selected'));
                
                // Add selected to clicked
                skinOption.classList.add('selected');
                
                // Update current skin
                currentBirdSkin = selectedSkin;
                localStorage.setItem('birdSkin', currentBirdSkin);
            }
        });
        
        // Shop functionality
        const shopMenu = document.getElementById('shopMenu');
        const shopButton = document.getElementById('shopButton');
        const shopButtonGameOver = document.getElementById('shopButtonGameOver');
        const closeShop = document.getElementById('closeShop');
        
        // Blackjack functionality
        const blackjackGame = document.getElementById('blackjackGame');
        const closeBlackjack = document.getElementById('closeBlackjack');
        
        // Gambling hub functionality
        const gamblingHub = document.getElementById('gamblingHub');
        const gamblingButton = document.getElementById('gamblingButton');
        const gamblingButtonGameOver = document.getElementById('gamblingButtonGameOver');
        const closeGamblingHub = document.getElementById('closeGamblingHub');
        
        // Baccarat functionality
        const baccaratGame = document.getElementById('baccaratGame');
        
        // Roulette functionality
        const rouletteGame = document.getElementById('rouletteGame');
        initRouletteBoard();
        
        // Slots functionality
        const slotsGame = document.getElementById('slotsGame');
        
        // Blackjack bet buttons
        document.querySelectorAll('.bj-bet-btn').forEach(btn => {
            btn.addEventListener('click', () => {
                const betAmount = btn.dataset.bet === 'all' ? coins : parseInt(btn.dataset.bet);
                if (betAmount > 0 && betAmount <= coins) {
                    startBlackjackRound(betAmount);
                }
            });
        });
        
        // Custom bet button
        document.getElementById('customBetBtn').addEventListener('click', () => {
            const customBet = parseInt(document.getElementById('customBetInput').value);
            if (isNaN(customBet) || customBet <= 0) {
                alert('Please enter a valid bet amount!');
                return;
            }
            if (customBet > coins) {
                alert('You don\'t have enough coins for that bet!');
                return;
            }
            startBlackjackRound(customBet);
            document.getElementById('customBetInput').value = ''; // Clear input
        });
        
        // Allow Enter key to place custom bet
        document.getElementById('customBetInput').addEventListener('keypress', (e) => {
            if (e.key === 'Enter') {
                document.getElementById('customBetBtn').click();
            }
        });
        
        document.getElementById('bjHit').addEventListener('click', hit);
        document.getElementById('bjDouble').addEventListener('click', doubleDown);
        document.getElementById('bjSplit').addEventListener('click', split);
        document.getElementById('bjStand').addEventListener('click', stand);
        document.getElementById('bjNewRound').addEventListener('click', newBlackjackRound);
        
        // Blackjack replay buttons
        document.getElementById('bjRebet').addEventListener('click', () => {
            if (bjLastBet > 0) {
                startBlackjackRound(bjLastBet);
            }
        });
        
        document.getElementById('bjRebet2x').addEventListener('click', () => {
            if (bjLastBet > 0) {
                startBlackjackRound(bjLastBet * 2);
            }
        });

        // Show skin selector from start screen
        skinButton.addEventListener('click', (e) => {
            e.stopPropagation();
            playButtonClick();
            skinSelector.classList.add('show');
            document.getElementById('volumeControl').classList.add('hidden');
        });

        skinButtonGameOver.addEventListener('click', (e) => {
            e.stopPropagation();
            playButtonClick();
            skinSelector.classList.add('show');
            document.getElementById('volumeControl').classList.add('hidden');
        });

        closeSkinSelector.addEventListener('click', () => {
            playButtonClick();
            skinSelector.classList.remove('show');
            document.getElementById('volumeControl').classList.remove('hidden');
        });

        shopButton.addEventListener('click', (e) => {
            e.stopPropagation();
            playButtonClick();
            renderShop();
            shopMenu.classList.add('show');
            document.getElementById('volumeControl').classList.add('hidden');
        });

        shopButtonGameOver.addEventListener('click', (e) => {
            e.stopPropagation();
            playButtonClick();
            renderShop();
            shopMenu.classList.add('show');
            document.getElementById('volumeControl').classList.add('hidden');
        });

        closeShop.addEventListener('click', () => {
            playButtonClick();
            shopMenu.classList.remove('show');
            document.getElementById('volumeControl').classList.remove('hidden');
        });

        gamblingButton.addEventListener('click', (e) => {
            e.stopPropagation();
            playButtonClick();
            document.getElementById('gamblingHubCoins').textContent = coins;
            gamblingHub.classList.add('show');
            document.getElementById('volumeControl').classList.add('hidden');
        });

        gamblingButtonGameOver.addEventListener('click', (e) => {
            e.stopPropagation();
            playButtonClick();
            document.getElementById('gamblingHubCoins').textContent = coins;
            gamblingHub.classList.add('show');
            document.getElementById('volumeControl').classList.add('hidden');
        });

        closeGamblingHub.addEventListener('click', () => {
            playButtonClick();
            gamblingHub.classList.remove('show');
            document.getElementById('volumeControl').classList.remove('hidden');
        });

        document.getElementById('openBlackjack').addEventListener('click', () => {
            playButtonClick();
            gamblingHub.classList.remove('show');
            updateBlackjackDisplay();
            blackjackGame.classList.add('show');
        });

        document.getElementById('openBaccarat').addEventListener('click', () => {
            playButtonClick();
            gamblingHub.classList.remove('show');
            newBaccaratRound();
            document.getElementById('bacCoins').textContent = coins;
            baccaratGame.classList.add('show');
        });

        document.getElementById('openRoulette').addEventListener('click', () => {
            playButtonClick();
            gamblingHub.classList.remove('show');
            clearRouletteBets();
            document.getElementById('rouCoins').textContent = coins;
            document.getElementById('rouResult').textContent = '';
            document.getElementById('rouMessage').textContent = '';
            rouBallAngle = null;
            drawRouWheel(rouAngle);
            rouletteGame.classList.add('show');
        });

        document.getElementById('openSlots').addEventListener('click', () => {
            playButtonClick();
            gamblingHub.classList.remove('show');
            document.getElementById('slotsCoins').textContent = coins;
            document.getElementById('slotsMessage').textContent = '';
            slotsGame.classList.add('show');
        });

        // Close games and return to hub
        closeBlackjack.addEventListener('click', () => {
            playButtonClick();
            blackjackGame.classList.remove('show');
            newBlackjackRound();
            document.getElementById('gamblingHubCoins').textContent = coins;
            gamblingHub.classList.add('show');
        });

        document.getElementById('closeBaccarat').addEventListener('click', () => {
            playButtonClick();
            baccaratGame.classList.remove('show');
            document.getElementById('gamblingHubCoins').textContent = coins;
            gamblingHub.classList.add('show');
        });

        document.getElementById('closeRoulette').addEventListener('click', () => {
            playButtonClick();
            rouletteGame.classList.remove('show');
            document.getElementById('gamblingHubCoins').textContent = coins;
            gamblingHub.classList.add('show');
        });

        document.getElementById('closeSlots').addEventListener('click', () => {
            playButtonClick();
            slotsGame.classList.remove('show');
            document.getElementById('gamblingHubCoins').textContent = coins;
            gamblingHub.classList.add('show');
        });

        // Baccarat event listeners
        document.getElementById('bacBetPlayer').addEventListener('click', () => {
            const amount = parseInt(document.getElementById('bacBetInput').value);
            if (amount) { playChipPlace(); startBaccaratRound('player', amount); }
        });

        document.getElementById('bacBetBanker').addEventListener('click', () => {
            const amount = parseInt(document.getElementById('bacBetInput').value);
            if (amount) { playChipPlace(); startBaccaratRound('banker', amount); }
        });

        document.getElementById('bacBetTie').addEventListener('click', () => {
            const amount = parseInt(document.getElementById('bacBetInput').value);
            if (amount) { playChipPlace(); startBaccaratRound('tie', amount); }
        });

        document.getElementById('bacNewRound').addEventListener('click', newBaccaratRound);
        
        // Baccarat replay buttons
        document.getElementById('bacRebet').addEventListener('click', () => {
            if (bacLastBet > 0 && bacLastBetOn) {
                playChipPlace();
                startBaccaratRound(bacLastBetOn, bacLastBet);
            }
        });
        
        document.getElementById('bacRebet2x').addEventListener('click', () => {
            if (bacLastBet > 0 && bacLastBetOn) {
                playChipPlace();
                startBaccaratRound(bacLastBetOn, bacLastBet * 2);
            }
        });

        // Roulette event listeners
        document.getElementById('rouBetRed').addEventListener('click', () => {
            const amount = parseInt(document.getElementById('rouBetInput').value);
            if (amount) addRouletteBet('red', null, amount);
        });

        document.getElementById('rouBetBlack').addEventListener('click', () => {
            const amount = parseInt(document.getElementById('rouBetInput').value);
            if (amount) addRouletteBet('black', null, amount);
        });

        document.getElementById('rouBetEven').addEventListener('click', () => {
            const amount = parseInt(document.getElementById('rouBetInput').value);
            if (amount) addRouletteBet('even', null, amount);
        });

        document.getElementById('rouBetOdd').addEventListener('click', () => {
            const amount = parseInt(document.getElementById('rouBetInput').value);
            if (amount) addRouletteBet('odd', null, amount);
        });

        document.getElementById('rouSpin').addEventListener('click', spinRoulette);
        document.getElementById('rouClearBets').addEventListener('click', clearRouletteBets);

        // Slots event listeners
        document.getElementById('slotsSpin').addEventListener('click', spinSlots);

        // Volume control
        let masterVolume = 0.5; // Default 50%
        const volumeSlider = document.getElementById('volumeSlider');
        const volumeValue = document.getElementById('volumeValue');
        const volumeIcon = document.getElementById('volumeIcon');
        
        // Load saved volume
        const savedVolume = localStorage.getItem('gameVolume');
        if (savedVolume !== null) {
            masterVolume = parseFloat(savedVolume);
            volumeSlider.value = Math.round(masterVolume * 100);
            volumeValue.textContent = Math.round(masterVolume * 100) + '%';
            masterGain.gain.value = masterVolume; // Apply to audio
        }
        
        // Update volume icon based on level
        function updateVolumeIcon(volume) {
            if (volume === 0) {
                volumeIcon.textContent = '🔇';
            } else if (volume < 0.33) {
                volumeIcon.textContent = '🔈';
            } else if (volume < 0.66) {
                volumeIcon.textContent = '🔉';
            } else {
                volumeIcon.textContent = '🔊';
            }
        }
        
        updateVolumeIcon(masterVolume);
        
        // Click volume icon to mute/unmute
        let previousVolume = masterVolume;
        volumeIcon.addEventListener('click', () => {
            if (masterVolume > 0) {
                // Mute
                previousVolume = masterVolume;
                masterVolume = 0;
                volumeSlider.value = 0;
                volumeValue.textContent = '0%';
                masterGain.gain.value = 0;
                updateVolumeIcon(0);
                localStorage.setItem('gameVolume', 0);
            } else {
                // Unmute to previous volume
                masterVolume = previousVolume || 0.5;
                volumeSlider.value = Math.round(masterVolume * 100);
                volumeValue.textContent = Math.round(masterVolume * 100) + '%';
                masterGain.gain.value = masterVolume;
                updateVolumeIcon(masterVolume);
                localStorage.setItem('gameVolume', masterVolume);
            }
        });
        
        volumeSlider.addEventListener('input', (e) => {
            masterVolume = e.target.value / 100;
            volumeValue.textContent = e.target.value + '%';
            updateVolumeIcon(masterVolume);
            masterGain.gain.value = masterVolume; // Apply to audio
            localStorage.setItem('gameVolume', masterVolume);
        });

        // Start game loop
        gameLoop();
    </script>
</body>
</html>
