TravelItinerary:
    def __init__(self):
        self.destinations = []

    def add_destination(self, destination):
        self.destinations.append(destination)

    def print_itinerary(self):
        print("Travel Itinerary:")
        for i, destination in enumerate(self.destinations, start=1):
            print(f"{i}. {destination}")

# Example usage:
itinerary = TravelItinerary()
itinerary.add_destination("Paris, France")
itinerary.add_destination("Rome, Italy")
itinerary.add_destination("Tokyo, Japan")
itinerary.print_itinerary()**# travel
