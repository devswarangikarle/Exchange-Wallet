# Exchange-Wallet
Tia and Raj find themselves bored, so they decide to engage in a wallet game. Tia starts with a wallet containing 'a' coins, while Raj has 'b' coins in his wallet.    The game proceeds with each player taking turns, and Tia makes the initial move. 

def find_winner(a, b):
    total_coins = a + b

    # Determine the winner based on the total number of coins
    if total_coins % 2 == 0:
        return "Raj"
    else:
        return "Tia"


a, b = map(int, input().split())
result = find_winner(a, b)
print(result)
