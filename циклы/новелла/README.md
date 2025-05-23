# Монтажер-анимешник: Пробой реальности

## О проекте
Интерактивная текстовая новелла на C# о приключениях электромонтажника Кая Ито, попавшего в параллельный Токио, где законы физики смешались с аниме-логикой.

```csharp
public class Hero {
    public int Wires { get; set; } = 15;  // Основной ресурс
    public int AnimePower { get; set; } = 5;  // Уровень магических способностей
}
```

##  Основной сюжет
После замыкания на подстанции №7 вы:
- 🔍 Обрели электромагическое зрение
- 💬 Научились понимать язык техники
- ⚡ Обнаружили порталы в аниме-вселенную

**Ключевые решения:**
- Чинить разрушающуюся инфраструктуру
- Исследовать аномалии
- Выбрать между реальностью и мечтой

##  Игровые механики

###  Система ресурсов
| Ресурс | Назначение | Способ получения |
|--------|------------|------------------|
| Wires | Ремонт оборудования | Успешные задания |
| AnimePower | Магические действия | Цитаты, артефакты |

###  Основные локации
1. **Подстанция №7** - исходная точка с секретным артефактом
2. **Район Акихабара** - магазин аниме-товаров
3. **Токийская башня** - финальный выбор пути

## Концовки

### 1. Мастер-электрик (Истинная)
- **Условия:** Починить 7 объектов + найти оберег
- **Финал:** Становление хранителем энергобаланса миров

### 2. Отаку-изгой (Секретная)
- **Условия:** Собрать все фигурки + произнести клятву
- **Финал:** Перенос в аниме-вселенную

### 3. Карьерист (Нейтральная)
- **Условия:** Игнорировать аномалии
- **Финал:** Позиция начальника, но пустота внутри

##  Установка
1. Требования:
   ```bash
   winget install Microsoft.DotNet.SDK.6
   ```
2. Запуск:
   ```bash
   git clone https://github.com/Tednet-flame/anime-electrician.git
   cd anime-electrician
   dotnet run
   ```

##  Советы
- Используйте комбинации клавиш для бонусов
- Экспериментируйте с разными путями прохождения
- Ищите скрытые отсылки к популярным аниме

