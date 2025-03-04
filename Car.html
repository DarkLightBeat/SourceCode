<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Source Code</title>
<style>
  body {
    background-color: black;
    margin: 0;
    padding: 20px; /* Add padding for better readability */
    display: flex;
    justify-content: center;
    align-items: center;
    color: white; /* Adding white color for better readability */
    font-family: Arial, sans-serif; /* Adding a font family for better readability */
    font-size: 18px; /* Larger font size */
    line-height: 1.6; /* Improved line height for readability */
  }
  pre {
    white-space: pre-wrap; /* Preserve white spaces */
    font-size: 16px; /* Adjusting code font size */
    background-color: #333; /* Adding a dark background for code block */
    padding: 20px; /* Adding padding for code block */
    border-radius: 8px; /* Rounded corners for code block */
    overflow-x: auto; /* Allow horizontal scrolling if needed */
  }
</style>
</head>
<body>
  <div style="max-width: 800px;">
    <h1>Fuel PseudoCode</h1>
    <pre><code>
import heapq

def minRefuelStops(target, startFuel, stations):
    max_heap = []  # Max heap to store available fuel amounts (negated for max heap behavior)
    fuel = startFuel
    refuel_count = 0
    index = 0
    n = len(stations)
    
    while fuel < target:
        # Add all reachable stations to the max heap
        while index < n and stations[index][0] <= fuel:
            heapq.heappush(max_heap, -stations[index][1])  # Negate fuel to simulate max heap
            index += 1
        
        # If no more stations can be reached and fuel is insufficient, return -1
        if not max_heap:
            return -1
        
        # Refuel with the maximum available fuel
        fuel += -heapq.heappop(max_heap)
        refuel_count += 1

    return refuel_count

# **User Input Section**
target = int(input("Enter target distance (miles): "))
startFuel = int(input("Enter starting fuel (liters): "))

# Getting stations input from the user
n = int(input("Enter number of gas stations: "))
stations = []
for _ in range(n):
    pos, fuel = map(int, input("Enter station position and fuel (space-separated): ").split())
    stations.append([pos, fuel])

# **Calling the function and printing result**
result = minRefuelStops(target, startFuel, stations)
print(f"Minimum refueling stops needed: {result}")
    </code></pre>
  </div>
</body>
</html>
