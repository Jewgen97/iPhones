# iPhones
# Initialize the number of iPhones sold
number_of_iPhones_sold = 0

# Function to sell iPhones
def sell_iPhone(quantity):
    global number_of_iPhones_sold
    number_of_iPhones_sold += quantity
    print(f"Sold {quantity} iPhone(s). Total iPhones sold: {number_of_iPhones_sold}")

# Example usage:
sell_iPhone(10)  # Sell 10 iPhones


