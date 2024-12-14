# LA-25

from abc import ABC, abstractmethod
class GameCharacter(ABC):
    @abstractmethod
    def special_move(self):
        pass
class warrior(GameCharacter):
    def special_move(self, move):
        print("Swing Sword")
        
class mage(GameCharacter):
    def special_move(self, move):
        print("Casts a Fireball")

class archer(GameCharacter):
    def special_move(self, move):
        print("Shoots an arrow")
      
warrior = warrior()
mage = mage()
archer = archer()

warrior.special_move("")
mage.special_move("")
archer.special_move("")
