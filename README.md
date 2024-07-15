# hello
# Средний вес одной сахаринки в граммах
sugar_grain_weight = 0.0002  # 0.2 миллиграмма

# Вес сахара в килограммах
sugar_weight_kg = 1

# Переводим вес сахара в граммы
sugar_weight_g = sugar_weight_kg * 1000

# Рассчитываем количество сахаринок
number_of_sugar_grains = sugar_weight_g / sugar_grain_weight

print(f"Примерное количество сахаринок в одном килограмме сахара: {number_of_sugar_grains:.0f}")
