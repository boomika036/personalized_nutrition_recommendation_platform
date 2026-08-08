# 1. Title

**Personalized Nutrition Recommendations Platform**

## 2. Domain

**Health & Nutrition / Food Technology**

## 3. Who is the User?

### 1. User

* Creates and manages their profile.
* Enters nutrition details and personal goals.
* Views personalized meal and food recommendations.

### 2. Admin

* Manages users and food information.
* Adds, updates, or removes food and nutrition data.
* Manages meal recommendations.

### 3. Nutritionist *(Optional)*

* Reviews user nutrition information.
* Provides or manages suitable meal recommendations.

## 4. What Problem Are We Solving?

Many people find it difficult to maintain a balanced diet because their nutritional requirements differ based on their age, weight, lifestyle, preferences, and goals. General diet plans may not be suitable for everyone and can lead to confusion when choosing daily meals.

**Real-life example:** A person who wants to gain weight may follow a general diet plan that does not provide enough calories or protein for their needs. Our platform analyzes the user's information and provides suitable personalized food and meal recommendations.

## 5. Proposed Solution

The application will:

* Allow users to register and create a profile.
* Collect age, height, weight, activity level, and dietary preferences.
* Allow users to select goals such as weight loss, weight gain, or healthy eating.
* Calculate basic nutritional requirements.
* Provide personalized food and meal recommendations.
* Display calorie and nutrient information for recommended foods.
* Allow users to track their progress.
* Allow admins to manage users, foods, and recommendations.

## 6. Core Entities / Database Tables

1. **User**
2. **UserProfile**
3. **Food**
4. **Nutrition**
5. **MealPlan**
6. **Recommendation**
7. **Goal**
8. **Progress**
9. **Admin**

## 7. User Roles & Permissions

| Role      | Permissions                                                                                  |
| --------- | -------------------------------------------------------------------------------------------- |
| **User**  | Register, manage profile, enter goals, view recommendations, view meal plans, track progress |
| **Admin** | Manage users, foods, nutrition data, meal plans, and recommendations                         |

## 8. Success Criteria

* A user should be able to **register and create a profile in under 2 minutes**.
* A user should be able to enter their nutrition details easily.
* The system should generate personalized recommendations based on the user's selected goal.
* Users should be able to view recommended meals and their nutritional values.
* Admin should be able to add, update, and delete food information.
* User progress should be stored and displayed correctly.

## 9. Out of Scope

The following features will **not** be included in the initial version:

* Medical diagnosis or treatment.
* Direct consultation with doctors.
* Online food ordering or delivery.
* Payment processing.
* Real-time calorie tracking from wearable devices.
* Advanced medical nutrition planning.
* AI-based disease prediction.

## 10. Chosen Track

**Java – Spring Boot**

### Technology Stack

* **Backend:** Java + Spring Boot
* **Database:** MySQL
* **Frontend:** HTML, CSS, JavaScript
* **API:** REST API
* **Version Control:** Git & GitHub
* **IDE:** VS Code / IntelliJ IDEA
