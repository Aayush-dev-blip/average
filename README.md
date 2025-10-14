def calculate_due_amount(total_bill, amount_paid):
    if amount_paid >= total_bill:
        print("No due amount. The bill is fully paid.")
        return 0
    else:
        due = total_bill - amount_paid
        print(f"Due amount: ${due:.2f}")
        return due

# Example usage
total_bill = float(input("Enter the total bill amount: $"))
amount_paid = float(input("Enter the amount paid by the customer: $"))

calculate_due_amount(total_bill, amount_paid)
