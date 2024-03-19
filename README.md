## Kod
### Namnstruktur
Använd snake case på variabelnamn för att underlätta läsningen. 
Det blir mycket lättare att läsa långa variabelnamn.
```csharp
// Lättare att läsa (snake_case)
float y_position = 0.32
float height_of_player = 1.64

// Svårare att läsa (camelCase)
float yPosition = 0.32
float heightOfPlayer = 1.64
```

Använd tydliga variabelnamn. Det gör inget om de blir långa när man använder snake case, men man behöver inte överdriva.
```csharp
// Tydligt 
float current_player_rotation_y = 0.32
float target_player_rotation_y = 1.64

// Otydligt 
float c_play_rot_y = 0.32
float t_play_rot_y = 1.64

// Jobbigt att att använda
float current_player_rotation_around_y_axis = 0.32
float target_player_rotation_around_y_axis = 1.64
```

