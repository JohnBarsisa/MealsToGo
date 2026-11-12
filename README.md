# MealsToGo — Restaurant Discovery Mobile App

**Status:** legacy React Native / Expo learning project. Not a currently published restaurant-booking or food-delivery service.

MealsToGo explores a mobile restaurant-discovery journey with list/map discovery, restaurant details, menu browsing, favourites and user-profile concepts.

## User journey

1. Search for restaurants by location.
2. Browse results in a list or map-oriented view.
3. Open a restaurant to inspect its details and menu.
4. Save preferred restaurants and return to them later.
5. Explore profile and order-related demonstration screens where present in the implementation.

## Stack represented in this repository

- React Native and Expo (legacy **Expo SDK 40** project)
- JavaScript and React Hooks
- React Navigation, React Native Paper and styled-components
- React Native Maps, Lottie-style animation patterns and AsyncStorage dependencies

`src/features/`, `src/components/`, `src/services/` and `src/infrastructure/` organise app screens, reusable UI, service adapters and shared concerns.

## Local development

```bash
git clone https://github.com/JohnBarsisa/MealsToGo.git
cd MealsToGo
npm install
npm start
```

This project targets older dependencies and may **not run unmodified** on current versions of Node, Expo Go or modern mobile OSs. If setup fails, use a compatible historical toolchain or plan an Expo migration.

## Limitations

This is a learning/prototype application. Restaurant listings, orders, payments, maps and user accounts depend on their configured data sources and integration credentials. Do **not** infer live restaurant affiliations, real payment processing, or app-store publication from the UI or original tutorial references.

### Potential improvements

Update Expo and navigation libraries, replace legacy services, add test coverage, document API configuration and use non-production sandbox payment systems for demonstrations.

Maintained in the [JohnBarsisa portfolio](https://github.com/JohnBarsisa).
