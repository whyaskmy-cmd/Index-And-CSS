# Index-And-CSS
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>ChatGPT Clone</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f0f0f0;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            margin: 0;
        }

        .chat-container {
            width: 100%;
            max-width: 700px;
            height: 90vh;
            background-color: #fff;
            border-radius: 10px;
            box-shadow: 0 0 15px rgba(0, 0, 0, 0.1);
            display: flex;
            flex-direction: column;
            overflow: hidden;
        }

        .chat-window {
            flex-grow: 1;
            padding: 20px;
            overflow-y: scroll;
            display: flex;
            flex-direction: column;
            gap: 15px;
        }

        .chat-message {
            padding: 10px 15px;
            border-radius: 18px;
            max-width: 70%;
            word-wrap: break-word;
            box-shadow: 0 1px 2px rgba(0, 0, 0, 0.05);
        }

        .incoming {
            background-color: #e5e5ea;
            align-self: flex-start;
        }

        .outgoing {
            background-color: #0b93f6;
            color: white;
            align-self: flex-end;
        }

        .chat-input-area {
            display: flex;
            padding: 15px;
            border-top: 1px solid #ccc;
            background-color: #f7f7f7;
        }

        .chat-input-area textarea {
            flex-grow: 1;
            border: 1px solid #ddd;
            border-radius: 20px;
            padding: 10px 15px;
            resize: none;
            font-size: 16px;
            line-height: 1.5;
            outline: none;
            transition: all 0.2s ease;
            min-height: 40px;
            box-sizing: border-box;
        }

        .chat-input-area textarea:focus {
            border-color: #0b93f6;
            background-color: #fff;
        }

        .send-button {
            background-color: #0b93f6;
            color: white;
            border: none;
            border-radius: 20px;
            padding: 10px 20px;
            margin-left: 10px;
            cursor: pointer;
            font-size: 16px;
            font-weight: bold;
            transition: background-color 0.2s ease;
        }

        .send-button:hover {
            background-color: #0077c2;
        }

        /* Responsive design for smaller screens */
        @media (max-width: 600px) {
            .chat-container {
                height: 100vh;
                border-radius: 0;
            }
            .chat-message {
                max-width: 80%;
            }
        }
    </style>
</head>
<body>
    <div class="chat-container">
        <div class="chat-window">
            <div class="chat-message incoming">
                <p>Hello! How can I assist you today?</p>
            </div>
            <div class="chat-message outgoing">
                <p>Can you help me design a simple chat interface?</p>
            </div>
        </div>
        <div class="chat-input-area">
            <textarea placeholder="Type your message..." rows="1"></textarea>
            <button class="send-button">Send</button>
        </div>
    </div>
</body>
</html>
https://github.com/whyaskmy-cmd/Index-And-CSS.git
