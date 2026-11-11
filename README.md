# Flower Auction House & Bid Tracking Dashboard

A relational database app (Python, SQLite, Tkinter) for tracking flower
auction houses, lots and bids. Deleting a house removes its lots and bids,
and deleting a lot removes its bids.

## Features
- Add a record: reuses the house if it exists, then adds one lot and one bid
- Delete a house, lot or bid from dropdowns
- Four tabs: combined JOIN view plus the three raw tables
- Input validation for blank, non-numeric and negative values

## How to run
1. Install Python 3 (Tkinter is included).
2. Open `Flower Auction App.ipynb` in Jupyter on your own computer
   and run the cell. The app opens in a separate window.
   (It will not work in Colab.)

## Tech
Python 3, SQLite, Tkinter
