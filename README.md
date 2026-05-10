# Smart Expense Leak Tracker Walkthrough

The **Smart Expense Leak Tracker** is a full-stack MERN application designed to help users track their spending and identify "money leaks" using intelligent data analysis.

## Key Features

### 1. Modern Dashboard
- **Visual Analytics**: Interactive Bar and Pie charts powered by Recharts.
- **Financial Summary**: Instant view of total spending, average transactions, and top categories.
- **Recent Activity**: Quick access to the latest transactions.

### 2. Intelligent Insights
- **Leak Detection**: Automatically identifies frequent small expenses (e.g., daily coffee or small subscriptions) that add up to significant amounts.
- **Spending Alerts**: Notifies users when current monthly spending significantly exceeds their average.
- **Smart Recommendations**: Provides actionable financial advice based on category breakdowns and spending habits.

### 3. Comprehensive Expense Management
- **Full CRUD**: Add, Edit, and Delete expenses with ease.
- **Advanced Filtering**: Search by notes or filter by category.
- **Clean Forms**: Intuitive modal-based input with validation.

### 4. Secure Authentication
- **JWT Protection**: Secure login and registration.
- **User Isolation**: Users only see their own financial data.
- **Protected Routes**: Frontend and backend protection ensuring data privacy.

## Technical Architecture

- **Backend**: Node.js & Express with an MVC structure.
- **Database**: MongoDB for scalable expense storage.
- **Frontend**: React (Vite) with a premium glassmorphic UI.
- **Styling**: Vanilla CSS with CSS variables for a consistent design system.
- **Animations**: Framer Motion for smooth layout transitions and interactions.

## Verification & Testing

- **Auth Flow**: Verified registration, login, and token persistence.
- **Insights Logic**: Tested with mock data to ensure "Leaks" and "Spikes" trigger correctly.
- **Responsiveness**: UI scales gracefully from desktop to mobile screens.

---

### How to Run

1. **Backend**:
   ```bash
   cd server
   npm install
   npm start
   ```
   *Ensure MongoDB is running at `mongodb://localhost:27017/expense-tracker`*

2. **Frontend**:
   ```bash
   cd client
   npm install
   npm run dev
   ```
