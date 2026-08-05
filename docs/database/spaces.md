# Spaces

## Purpose

Represents any physical or logical location capable of containing objects.

## Responsibilities

- Organize physical locations.
- Provide hierarchical relationships.
- Serve as the primary location reference for Items.
- Support future maintenance and inventory modules.

## Primary Entity

Space

## Relationships

- Space → Space (Parent)
- Space → Item (One-to-Many)
- Space → Project (One-to-Many)

## Current Status

Draft