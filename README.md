# ATM System (Python)

This is a basic ATM system built using Python.
It allows users to perform simple banking operations through the terminal.

## Features

* Display account balance
* Deposit money
* Withdraw money
* View transaction history (statement)

## Project Structure

```
Atmsystem/
│── main.py
│── utils.py
│── deposit.py
│── withdraw.py
│── display.py
│── statement.py
```

## How to Run

1. Make sure Python is installed
2. Open terminal in the project folder
3. Run:

```
python main.py
```

## How It Works

* The program shows a menu with options
* User selects an option by entering a number
* Based on input, the corresponding function is called
* Transactions are stored in a list

## Notes

* Initial balance is stored in `utils.py`
* Transactions are not saved permanently (they reset when program restarts)
* Input should be numeric to avoid errors

## Future Improvements

* Add PIN authentication
* Store data in files
* Improve UI
* Add timestamps to transactions

---

Simple ATM project for learning Python basics and logic building.

