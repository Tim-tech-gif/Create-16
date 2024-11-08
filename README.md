# Create-16
def draw_tree(levels):     # Генеруємо трикутники для ялинки     def triangles():         for level in range(levels):             width = 2 * level + 1             height = level + 1             for i in range(height):                 yield ' ' * (width // 2 - i) + '*' * (2 * i + 1)      # Виводимо ялинку     for line in triangles():         
