def calculate_league_points(wins, draws, losses):
    # Complete this function
    output = (wins*4)+(draws*2)-(losses*1)
    print(output)


statistics = input().split(",")
wins = int(statistics[0])
draws = int(statistics[1])
losses = int(statistics[2])
new_league_points = calculate_league_points(wins, draws, losses)
# Call the calculate_league_points function
