---
title: Welcome to Quartz ^^
---

This is a blank Quartz installation. ^^' 😅
See the [documentation](https://quartz.jzhao.xyz) for how to get started.
```py
import os
from datetime import datetime

class ForestEcosystem:
    """A simple class representing a woodland environment."""
    
    def __init__(self, name: str, region_code: int = 1):
        self.name = name
        self.trees = []
        self.is_active = True
        
    @property
    def tree_count(self):
        # Calculate the total number of trees
        return len(self.trees)

    def plant_tree(self, species="Oak"):
        if not species:
            raise ValueError("Species cannot be empty.")
            
        self.trees.append(species)
        print(f"[{datetime.now()}] Planted a beautiful {species} in {self.name}!")

# Initialize and test
my_forest = ForestEcosystem("Whispering Pines")
my_forest.plant_tree("Cedar")
```

> [!note]

> [!tip] Tip

> [!success] Success

> [!warning] Warning

> [!danger] Danger / Error

> [!example] Example

> [!quote] Quote