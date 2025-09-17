# Artificial Neural Network Project

This project implements an Artificial Neural Network (ANN) model designed for Optical Character Recognition (OCR). The architecture is built using Python for the server-side logic and JavaScript for the client-side interface.

## Project Structure

```
ann-project
├── client
│   ├── ocr.js          # JavaScript code for client-side functionality
│   └── ocr.html        # HTML interface for user input and results display
├── server
│   └── server.py       # Server-side application handling requests
├── ann
│   ├── ocr.py          # Implementation of the ANN trained via backpropagation
│   └── neural_network_design.py  # Design and architecture of the ANN
├── data
│   └── README.md       # Documentation regarding the data used in the project
├── tests
│   └── test_ann.py     # Unit tests for the ANN model
├── requirements.txt     # List of Python dependencies
└── README.md            # Overview of the project
```

## Setup Instructions

1. **Clone the repository**:
   ```
   git clone <repository-url>
   cd ann-project
   ```

2. **Install dependencies**:
   Use the following command to install the required Python packages:
   ```
   pip install -r requirements.txt
   ```

3. **Run the server**:
   Start the server by executing:
   ```
   python server/server.py
   ```

4. **Access the application**:
   Open `client/ocr.html` in a web browser to interact with the OCR application.

## Usage Guidelines

- The client-side JavaScript (`ocr.js`) handles user interactions and communicates with the server.
- The server (`server.py`) processes requests and utilizes the ANN model for OCR tasks.
- The ANN implementation (`ocr.py`) is trained using backpropagation, and its design can be modified in `neural_network_design.py`.
- Unit tests are provided in `tests/test_ann.py` to ensure the functionality of the ANN.

## Future Development

This project structure is designed to be scalable. Additional features, such as improved model architectures, enhanced user interfaces, or expanded testing frameworks, can be easily integrated into the existing framework.