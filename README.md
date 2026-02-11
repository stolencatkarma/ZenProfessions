# Zen Professions

A comprehensive Project Zomboid mod that adds 19 unique professions to the character creation screen, each with thematic skills, recipes, and traits.

## 📋 Overview

Zen Professions expands your character creation options with professionally-themed occupations that provide unique gameplay advantages. Each profession comes with carefully balanced skill boosts, granted recipes, and profession-specific traits that enhance roleplaying and survival strategies.

## 🎯 Features

- **19 Unique Professions** - From journalists to paramedics, each with real-world inspiration
- **Balanced Gameplay** - Professions range from -4 to +4 point costs for fair character creation
- **Thematic Recipes** - Each profession grants recipes that fit their occupational background
- **Profession Traits** - Unique traits that provide additional skills and recipes
- **Build 42 Compatible** - Fully compatible with Project Zomboid's latest modding framework

## 👥 Professions Included

### Media & Communication
- **Journalist** (-0 points): Investigative skills, stealth bonuses, hollow book crafting
- **DJ** (+2 points): Electronics expertise, radio crafting, speaker building
- **VCR Technician** (-2 points): Advanced electronics, radio communications
- **Switchboard Operator** (+2 points): Communications skills, walkie-talkie crafting
- **Photographer** (+2 points): Precision aiming, camera and scope crafting
- **Video Rental Clerk** (+2 points): Entertainment knowledge, media device crafting

### Service & Administrative
- **Minister** (+2 points): Spiritual guidance, mental health bonuses
- **Secretary** (+4 points): Administrative skills, organizational recipes
- **Postman** (-0 points): Delivery fitness, packaging expertise
- **Teacher** (+2 points): Educational skills, writing supplies

### Technical & Maintenance
- **Arcade Technician** (-2 points): Electricity and mechanics, advanced repairs
- **Bus Driver** (-2 points): Vehicle knowledge, basic repair skills
- **Cab Driver** (-2 points): Driving expertise, vehicle maintenance
- **Janitor** (+4 points): Maintenance mastery, cleaning supplies
- **Plumber** (-4 points): Repair specialization, plumbing tools

### Health & Safety
- **Lifeguard** (-0 points): Athletic fitness, water survival skills
- **Paramedic** (-4 points): Medical expertise, emergency response

### Culinary & Outdoor
- **Baker** (-2 points): Cooking mastery, baking recipes
- **Hunter** (-4 points): Marksmanship and trapping, survival recipes

## 🛠️ Installation

1. **Download** the repository as a ZIP file using the **Code** button above
2. **Extract** the ZIP file to your Project Zomboid workshop folder:
   - Usually: `C:\Users\[YourName]\Zomboid\Workshop`
3. **Launch** Project Zomboid
4. **Enable** the mod in the main menu under "Mods"
5. **Create** a new character and select from the 19 new professions!

## 📊 Profession Details

### Skill Bonuses & Recipes

| Profession | Cost | XP Boosts | Granted Recipes | Trait Bonus |
|------------|------|-----------|-----------------|-------------|
| Journalist | 0 | Sneak+1, Lightfoot+1 | - | Investigative (+1 Sneak, Hollow Books) |
| Minister | 2 | Doctor+1 | - | Spiritual (+1 Doctor, Paper) |
| DJ | 2 | Electricity+1 | CraftMakeshiftRadio | Electronics Specialist (+1 Electricity, Speakers) |
| VCR Technician | -2 | Electricity+2, Maintenance+1 | CraftMakeshiftRadio, CraftMakeshiftHAMRadio | Tech Savvy (+1 Electricity/+1 Mechanics) |
| Arcade Technician | -2 | Electricity+2, Mechanics+1 | - | Mechanic Specialist (+1 Mechanics, Suspension Repair) |
| Switchboard Operator | 2 | Electricity+1 | CraftMakeshiftWalkieTalkie | Communications (+1 Electricity) |
| Secretary | 4 | Maintenance+1 | MakeSheetPaper, MakePencil | Organized (+1 Maintenance, Notebooks) |
| Postman | 0 | Sprinting+2, Fitness+1 | MakeSheetPaper, MakeEnvelope | Delivery Expert (+1 Sprinting, Tarps) |
| Bus Driver | -2 | Mechanics+2 | BasicRepairCarEngine, BasicRepairCarBattery | Road Savvy (+1 Mechanics) |
| Cab Driver | -2 | Mechanics+1, Sprinting+1 | BasicRepairCarTire, BasicRepairCarBrake | Road Savvy (+1 Mechanics) |
| Janitor | 4 | Maintenance+2 | MakeCleaningLiquid, MakeBleach | Maintenance Pro (+1 Maintenance, Metal Drums) |
| Photographer | 2 | Aiming+1 | CraftMakeshiftCamera | Marksman (+1 Aiming, Scopes) |
| Video Rental Clerk | 2 | Electricity+1 | CraftMakeshiftRemote, CraftMakeshiftVHS | Entertainment Buff (+1 Electricity, Microphones) |
| Plumber | -4 | Maintenance+2 | - | Leak Repair (+1 Maintenance, Pipe Wrenches) |
| Teacher | 2 | Teaching+1, Maintenance+1 | MakeSheetPaper, MakeNotebook | Educator (+1 Teaching, Pencils) |
| Baker | -2 | Cooking+2 | Multiple baking recipes | Culinary Artist (+1 Cooking) |
| Hunter | -4 | Aiming+2, Trapping+1 | Multiple trap recipes | Tracker (+1 Trapping) |
| Lifeguard | 0 | Sprinting+1, Fitness+1 | MakeFishingRod | Swimmer (+1 Fitness, Fishing Nets) |
| Paramedic | -4 | Doctor+2, Sprinting+1 | MakeBandage, MakeSterilizedRag | First Responder (+1 Doctor/+1 Sprinting) |

## 🎮 Gameplay Tips

- **Point Costs**: Negative costs give you extra points for other traits, positive costs require spending points
- **Recipe Synergy**: Many professions have recipes that work well together (e.g., DJ + VCR Technician for full electronics setup)
- **Trait Bonuses**: Profession traits provide additional recipes and skills beyond the base profession
- **Roleplaying**: Each profession encourages different playstyles - stealthy journalists, technical DJs, survivalist hunters

## 🔧 Mod Structure

```
ZenProfessions/
├── mod.info                 # Mod metadata
├── media/
│   ├── scripts/
│   │   ├── professions.txt  # Profession definitions
│   │   └── traits.txt       # Trait definitions
│   └── lua/
│       └── shared/
│           ├── registries.lua    # Registration script
│           └── Translate/EN/     # Translation files
│               ├── UI_EN.txt     # UI translations
│               └── IG_UI_EN.txt  # In-game translations
```

## 🐛 Troubleshooting

- **Professions not appearing**: Ensure the mod is enabled in the main menu
- **Missing recipes**: Check that you have the required materials and skill levels
- **Translation issues**: Verify the translation files are in the correct location
- **Conflicts**: This mod should be compatible with most others, but disable if issues occur

## 📝 Modding Notes

This mod demonstrates proper Project Zomboid build 42 modding practices:
- Uses the modular profession registration system
- Implements profession-specific traits
- Provides comprehensive translations
- Maintains balance with the base game

## 🤝 Contributing

Feel free to suggest new professions or balance changes! This mod is designed to be expandable.

## 📜 License

This mod is provided as-is for Project Zomboid. Please respect the game's terms of service.

## 🙏 Credits

Created for the Project Zomboid community to enhance character creation and roleplaying opportunities.

---

**Compatible with Project Zomboid Build 42** | **Workshop ID: ZenProfessions**</content>
<parameter name="filePath">c:\Users\enjia\Zomboid\Workshop\ZenProfessions\README.md