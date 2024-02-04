# Traveling.py
def cheapest_flight(destination, flexibility_day,budget,perfered_airlines):
    cheapest_flight = {
    "airline1": {
        "airline_name": "Thai airline",
        "price": 800,
        "date": ["1_Feb_2024", "15_Feb_2024"]
    },
    "airline2": {
        "airline_name": "Garuda Indonesia",
        "price": 3000,
        "date": ["2_March_2023", "16_March_2023"]
    },
    "airline3": {
        "airline_name": "Singapore airline",
        "price": 2000,
        "date": ["4_April_2023", "17_April_2023"]
    },
    "airline4": {
        "airline_name": "Oman airline",
        "price": 971,
        "date": ["12_May_2023", "20_May_2023"]
    }
}
preferred_airline_departure={"Tai airline":880,"Garuda Indonesia":3000,"singapora airline":2000,"Oman airline":971}
preferred_airline_return={"Tai airline":880,"Garuda Indonesia":3000,"singapora airline":2000,"Oman airline":971}
if preferred_airline_departure["Garuda Indonesia"] < preferred_airline_departure["singapora airline"]:
    print("go with singapora airline it cheaper")
if preferred_airline_departure["Garuda Indonesia"] < preferred_airline_departure["Oman airline"]:
    print("go with Oman airline it cheapest")
if preferred_airline_departure["Garuda Indonesia"] < preferred_airline_departure["Tai airline"]:
    print(" go with Tai airline it cheapest")
if preferred_airline_departure["singapora airline"] < preferred_airline_departure["Oman airline"]:
    print(" go with Oman airline it cheapest")
if preferred_airline_departure["singapora airline"] < preferred_airline_departure["Tai airline"]:
    print(" go with Tai airline it cheapest")
else:
    print("go with Tai airline")
#Return flight 
Preferred_airline_return={"Tai airline":880,"Garuda Indonesia":3000,"singapora airline":2000,"Oman airline":971}
if preferred_airline_return["Tai airline"] < Preferred_airline_return["Garuda Indonesia"] > preferred_airline_return["Oman airline"]:
      print("Oman airline")
if preferred_airline_return["Garuda Indonesia"] < preferred_airline_return["singapora airline"] > preferred_airline_return["Tai airline"]:
    print("Tai airline")
elif  preferred_airline_return["singapora airline"] < preferred_airline_return["Garuda Indonesia"]:
    print("singapora airline")
    
for airline in   preferred_airline_departure:
    print(min(Preferred_airline_departure.value()))
print ([key for key, value in preferred_air_departure.items() if values== min(preferred_airline_departure.values())])
budget = 2000
print ((budget))
for airline in preferred_airline_return:
    if airline <= budget:
        print(airline)
