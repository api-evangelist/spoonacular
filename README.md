# Spoonacular (spoonacular)

The Spoonacular Recipe and Food API provides programmatic access to thousands of recipes, thousands of ingredients, 800,000+ food products, and 100,000+ menu items, plus nutrition analysis, meal planning, wine pairing, and food classification. Authentication is via an API key sent in the x-api-key header.

**URL:** [Visit APIs.json URL](https://spoonacular.com/food-api)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - Restaurant, Food And Drink, Recipes, Nutrition, Meal Planning, Public APIs

## Timestamps

- **Created:** 2026-05-28
- **Modified:** 2026-06-03

## APIs

### Spoonacular

The Spoonacular Recipe and Food API — recipes, ingredients, grocery products, menu items, meal planning, wine pairing, and food classification across 97 endpoints. OpenAPI 3 sourced from the official ddsky client generator spec. API key auth via the x-api-key header.

**Human URL:** [https://spoonacular.com/food-api](https://spoonacular.com/food-api)

**Base URL:** https://api.spoonacular.com

#### Tags:

 - Food And Drink, Recipes, Nutrition, Meal Planning

#### Properties

- [Documentation](https://spoonacular.com/food-api/docs)
- [APIReference](https://spoonacular.com/food-api/docs)
- [OpenAPI](openapi/spoonacular-openapi.yml)
- [Authentication](https://spoonacular.com/food-api/docs#Authentication)
- [Quickstart](https://spoonacular.com/food-api/docs#Getting-Started)
- [SDK — Python](https://github.com/ddsky/spoonacular-api-clients/tree/master/python)
- [SDK — JavaScript](https://github.com/ddsky/spoonacular-api-clients/tree/master/javascript)
- [SDK — Java](https://github.com/ddsky/spoonacular-api-clients/tree/master/java)
- [SDK — PHP](https://github.com/ddsky/spoonacular-api-clients/tree/master/php)
- [SDK — Ruby](https://github.com/ddsky/spoonacular-api-clients/tree/master/ruby)
- [SDK — Go](https://github.com/ddsky/spoonacular-api-clients/tree/master/go)

## Common Properties

- [Website](https://spoonacular.com/food-api)
- [DeveloperPortal](https://spoonacular.com/food-api)
- [Console](https://spoonacular.com/food-api/console)
- [SignUp](https://spoonacular.com/food-api/console#Dashboard)
- [Pricing](https://spoonacular.com/food-api/pricing)
- [SDK — API Clients (22 languages)](https://spoonacular.com/food-api/sdk)
- [GitHubOrganization](https://github.com/ddsky)
- [GitHubRepository — API Clients](https://github.com/ddsky/spoonacular-api-clients)
- [Tutorials](https://github.com/ddsky/spoonacular-api-tutorials)
- [CodeExamples — Widgets](https://github.com/ddsky/spoonacular-widgets)
- [Tools — MCP Server](https://github.com/ddsky/spoonacular-mcp)
- [Tools — MCP Server (npm)](https://www.npmjs.com/package/spoonacular-mcp)
- [PublicAPIsListing](https://github.com/public-apis/public-apis)

## Features

| Name | Description |
|------|-------------|
| Recipe Search and Information | Complex multi-filter search, search by ingredients or nutrients, full recipe information, similar/random recipes, autocomplete, and analyzed instructions. |
| Nutrition Analysis | Compute and visualize nutrition for recipes, ingredients, products, and menu items including macro- and micronutrient breakdowns. |
| Ingredient Intelligence | Search ingredients, get information and substitutes, parse ingredient strings, compute conversions, and look up glycemic load. |
| Grocery Products | Search 800,000+ packaged food products by name or UPC, retrieve product information, compare products, and classify them. |
| Menu Items | Search and retrieve 100,000+ restaurant menu items with nutrition and autocomplete. |
| Meal Planning | Generate daily and weekly meal plans, build shopping lists, and manage meal plan templates. |
| Wine Pairing | Recommend wine pairings for dishes and recipes and return wine descriptions and recommendations. |
| Food Classification and Media | Classify food in images, search recipe videos, extract recipes from web pages, and return food jokes and trivia. |

## Use Cases

| Name | Description |
|------|-------------|
| Recipe and Cooking Apps | Power consumer cooking apps with searchable recipes, step-by-step instructions, and ingredient-based discovery. |
| Diet and Nutrition Tracking | Analyze meals and products for calories and nutrients to drive diet, fitness, and health applications. |
| Grocery and Shopping List Tools | Build shopping lists from meal plans and look up packaged products by name or UPC. |
| AI Cooking Assistants | Expose recipe, nutrition, and meal-planning operations to LLM agents through the official MCP server. |

## Integrations

| Name | Description |
|------|-------------|
| Model Context Protocol | Official spoonacular-mcp server exposes the API as MCP tools for AI assistants. |
| OpenAPI Generator | Official multi-language client SDKs are generated from the OpenAPI 3 spec with OpenAPI Generator. |
| RapidAPI | The Spoonacular API is also available through the RapidAPI marketplace. |

## Artifacts

Machine-readable API specifications organized by format.

### OpenAPI

- [Spoonacular API](openapi/spoonacular-openapi.yml) — OpenAPI 3.0.0, 97 paths / 99 operations across 7 tags

### JSON Schema

- [Recipe Information](json-schema/spoonacular-recipe-information-schema.json)
- [Search Result](json-schema/spoonacular-search-result-schema.json)
- [Ingredient Information](json-schema/spoonacular-ingredient-information-schema.json)
- [Ingredient Basics](json-schema/spoonacular-ingredient-basics-schema.json)
- [Product Information](json-schema/spoonacular-product-information-schema.json)
- [Comparable Product](json-schema/spoonacular-comparable-product-schema.json)
- [Menu Item](json-schema/spoonacular-menu-item-schema.json)
- [Taste Information](json-schema/spoonacular-taste-information-schema.json)

### JSON Structure

- 8 JSON Structure files mirroring the JSON Schemas in [json-structure/](json-structure/)

### JSON-LD

- [Spoonacular Context](json-ld/spoonacular-context.jsonld)

### Examples

- 8 example payloads in [examples/](examples/)

## Capabilities

Naftiko capabilities — one self-contained file per business surface (OpenAPI tag), each exposing both a REST and an MCP adapter.

| Capability | API | Operations | MCP Tools |
|------------|-----|-----------|-----------|
| [Recipes](capabilities/spoonacular-recipes.yaml) | Spoonacular | 42 | 42 |
| [Meal Planning](capabilities/spoonacular-meal-planning.yaml) | Spoonacular | 14 | 14 |
| [Products](capabilities/spoonacular-products.yaml) | Spoonacular | 11 | 11 |
| [Misc](capabilities/spoonacular-misc.yaml) | Spoonacular | 11 | 11 |
| [Ingredients](capabilities/spoonacular-ingredients.yaml) | Spoonacular | 9 | 9 |
| [Menu Items](capabilities/spoonacular-menu-items.yaml) | Spoonacular | 8 | 8 |
| [Wine](capabilities/spoonacular-wine.yaml) | Spoonacular | 4 | 4 |

## Vocabulary

- [Spoonacular Vocabulary](vocabulary/spoonacular-vocabulary.yaml) — Unified taxonomy mapping 7 resources, 30 actions, 7 workflows, and 3 personas across operational (OpenAPI) and capability (Naftiko) dimensions

## Rules

- [Spoonacular Spectral Rules](rules/spoonacular-spectral-rules.yml) — 20 rules across info, servers, paths, operations, tags, parameters, responses, security, and quality categories enforcing Spoonacular API conventions

## Commercial

- [Plans / Pricing](plans/spoonacular-plans-pricing.yml) — API Commons Plans 0.1: Free, Cook, Culinarian, Chef, Enterprise tiers
- [Rate Limits](rate-limits/spoonacular-rate-limits.yml) — API Commons Rate Limits 0.1: per-key request rate, concurrency, and daily points quota
- [FinOps](finops/spoonacular-finops.yml) — FOCUS-aligned FinOps Framework 1.0: points-based usage metering

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
