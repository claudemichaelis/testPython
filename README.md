# testPython
testgame
import pygame

# Инициализация игрового окна
pygame.init()
screen = pygame.display.set_mode((800, 600))
pygame.display.set_caption("Моя игра")

# Основной цикл игры
running = True
while running:
    # Обработка событий
    for event in pygame.event.get():
        if event.type == pygame.QUIT:
            running = False

    # Обновление игровой логики

    # Отрисовка графики
    screen.fill((255, 255, 255))
    pygame.display.update()

# Завершение игры
pygame.quit()
