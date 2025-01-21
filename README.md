# Projet MCP - Système de Mémoire

## Description
Ce projet implémente un système de mémoire basé sur le Model Context Protocol (MCP) permettant de gérer des entités, relations et observations dans un graphe de connaissances.

## Fonctionnalités
- Création et gestion d'entités
- Établissement de relations entre entités
- Ajout d'observations aux entités
- Recherche et exploration du graphe de connaissances
- Intégration avec d'autres services MCP

## Installation
1. Cloner le dépôt
2. Installer les dépendances : `pip install -r requirements.txt`
3. Configurer les variables d'environnement
4. Lancer les serveurs MCP

## Utilisation
```python
from mcp import MemoryServer

# Initialisation du serveur
server = MemoryServer()

# Création d'une entité
server.create_entity("Personne", "Jean Dupont")

# Ajout d'une observation
server.add_observation("Jean Dupont", "Aime le chocolat")

# Création d'une relation
server.create_relation("Jean Dupont", "Marie Curie", "connait")
```

## Structure du projet
- `MCP/` : Serveurs MCP principaux
- `site-packages/` : Packages Python nécessaires
- `progress.md` : Suivi de l'avancement du projet
