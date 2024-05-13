# ISS Tracker 🛰️

This Python script tracks the International Space Station (ISS) and sends you an email notification when it is passing over your location during the night.

## Requirements

- Python 3.x
- Requests library
- smtplib library

## Configuration

1. Replace `___YOUR_EMAIL_HERE___` with your email address in the `MY_EMAIL` variable.
2. Replace `___YOUR_PASSWORD_HERE___` with your email password or generate an app password for your email provider.
3. Replace `__YOUR_SMTP_ADDRESS_HERE___` with your SMTP server address (e.g., smtp.gmail.com for Gmail).

## Usage

1. Run the script:

    ```bash
    python main.py
    ```

2. Keep the script running to continuously track the ISS.

## Explanation

- The script uses the Open Notify API to get the current location of the ISS.
- It also uses the Sunrise-Sunset API to check if it is night at your location.
- If the ISS is overhead and it is night, it sends you an email notification.

## Notes

- Make sure to enable less secure apps or generate an app password for your email provider.
- Ensure that your email provider allows SMTP connections.
- It's recommended to run the script in the background or as a scheduled task.

## License

This project is licensed under the MIT License.
