class Rectangle:
    def __init__(self, width, height):
        self.width = width
        self.height = height

    @property
    def area(self):
        return self.width * self.height

    @area.setter
    def area(self, new_area):
        self.width = new_area / self.height



rect = Rectangle(5, 10)
print(f"Dastlabki maydon: {rect.area}")

rect.area = 200
print(f"Yangilangan maydon: {rect.area}")
print(f"Yangi width: {rect.width}, height: {rect.height}")
