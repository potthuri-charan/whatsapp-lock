# WhatsApp Lock

A secure system to lock and unlock WhatsApp using facial recognition and password authentication.

## Features

- **Facial Recognition:** Uses the camera to authenticate the user.
- **Password Authentication:** Secondary layer of security with a password.
- **Easy Setup:** Simple steps to get started quickly.

## Requirements

Before you begin, ensure you have met the following requirements:

- Python 3.x installed on your system.
- Required Python packages listed in `requirements.txt`.
- WhatsApp must be installed and open on your system.

## Installation and Setup

Follow these steps to set up the WhatsApp Lock system:

1. **Clone the repository:**

   ```bash
   git clone https://github.com/your-username/whatsapp-lock.git
   ```

2. **Navigate to the project directory:**

   ```bash
   cd "D:\New folder\Final Year Project\whatsapp-lock"
   ```

3. **Install the required dependencies:**

   Make sure you have `pip` installed, then run:

   ```bash
   pip install -r requirements.txt
   ```

4. **Run the password generation script:**

   ```bash
   python3 password_gen_cam.py
   ```

   This script will set up the initial password and facial recognition data.

5. **Open WhatsApp on your system:**

   Ensure WhatsApp is running and open on your computer before proceeding.

## Usage

Once the setup is complete, the system will monitor for attempts to access WhatsApp and require authentication through both facial recognition and password entry.

## Troubleshooting

- **Cannot access WhatsApp:** Make sure WhatsApp is open and running on your system.
- **Dependencies not installing:** Check that you have `pip` installed and try running the installation command again.
- **Facial recognition not working:** Ensure your camera is properly set up and the correct drivers are installed.

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

This project is licensed under the MIT License.
```

Copy and paste this code into your `README.md` file in the root directory of your project. Make sure to replace `"https://github.com/your-username/whatsapp-lock.git"` with the actual URL of your GitHub repository.
