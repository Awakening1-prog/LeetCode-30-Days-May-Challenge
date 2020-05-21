class Solution:
    def checkStraightLine(self, coordinates: List[List[int]]) -> bool:
        x1=coordinates[0][0]
        x2=coordinates[1][0]
        y1=coordinates[0][1]
        y2=coordinates[1][1]
        for i in range(2,len(coordinates)):
            x=coordinates[i][0]
            y=coordinates[i][1]
            if (y2-y1)*(x1-x)!=(x2-x1)*(y1-y):
                return 0
        else:
            return 1
