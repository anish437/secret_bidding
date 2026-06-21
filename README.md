# 🤫 Secret Bidding Auction (CLI)

A command-line Python program designed for private, blind bidding. The program clears the console screen after each turn so participants cannot see previous offers, and announces the highest bidder at the conclusion.

## 🚀 Features
* **Blind Bidding:** Keeps individual inputs hidden from successive participants.
* **Cross-Platform Console Clearing:** Automatically detects OS to clear screens seamlessly.
* **Winner Calculation:** Reviews all dictionary records to output the highest value.

## 🛠️ Requirements
* Python 3.x

## 💻 How to Run
1. Clone this repository:
   ```bash
   git clone https://github.com
   ```
2. Navigate into the project folder:
   ```bash
   cd secret_bidding
   ```
3. Run the application:
   ```bash
   python main.py
   ```

## 📝 Example Flow
```text
Welcome to the secret auction program.
What is your name?: Alice
What's your bid?: \$150
Are there any other bidders? Type 'yes' or 'no': yes

[--- Screen Automatically Clears ---]

What is your name?: Bob
What's your bid?: \$200
Are there any other bidders? Type 'yes' or 'no': no

The winner is Bob with a bid of \$200.
```
