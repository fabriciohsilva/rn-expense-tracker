# React Native Expense Tracker

A simple expense tracker app built with React Native and Expo.

## Features

- Add, edit, and delete expenses
- View all expenses or only recent (last 7 days) expenses
- Summary of expenses for selected period
- Modern UI with custom styles

## Project Structure

```
.
├── App.tsx
├── index.ts
├── components/
│   ├── ExpensesOutput/
│   ├── ManageExpense/
│   └── UI/
├── constants/
├── data/
├── screens/
├── store/
├── utils/
├── assets/
├── package.json
└── tsconfig.json
```

## Getting Started

1. **Install dependencies:**

   ```sh
   npm install
   ```

2. **Start the Expo development server:**

   ```sh
   npm start
   ```

3. **Run on your device:**
   - For Android: `npm run android`
   - For iOS: `npm run ios`
   - For Web: `npm run web`

## Dependencies

- React Native
- Expo
- React Navigation

## Customization

- Edit dummy data in [`data/dummy-data.tsx`](data/dummy-data.tsx)
- Change global styles in [`constants/styles.tsx`](constants/styles.tsx)

## License

MIT
