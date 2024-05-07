import math

points = [(5, 5), (3, 2), (3, 3)]

def euclideanDistance(point_1, point_2):
    return math.sqrt((point_2[0] - point_1[0]) ** 2 + (point_2[1] - point_1[1]) ** 2)
    
distances = []

for i in range(len(points)):
    for j in range(i + 1, len(points)):
        dist = euclideanDistance(points[i], points[j])
        distances.append(dist)
        
min_distance = min(distances)
print("Minimum mesafe:", min_distance)
