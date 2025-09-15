# App Dev Club – Frontend Interview 

## Getting started

- Clone the repo to your local system
  - Create a new branch called `firstname-lastname` with your name
  - Then checkout to this branch
- Install dependencies with `npm i`
- Run the app with `npm run dev`, then go to `http://localhost:3000` to see it
- Edit your code in `src/app/page.tsx`

## Main Tasks

1. **Create a Todo List**
   - Users should be able to **add todos** with a simple input and button
   - Users should be able to **mark todos as complete or incomplete** using a checkbox

2. **Todo Counter**
   - Show the total number of **completed** todos at the bottom of the list

## Notes

- Focus on getting the **core functionality** working first, while creating clean, readable code
- Don't worry about styling unless asked to
- Walk us through your thought process as you go, we want to understand how you approach problems, not just see the final result

## Additional Requirements (if time allows)

1. **Connect to a Dummy Backend**
   - Use a local backend at **`http://localhost:5000`**
   - On first load, **GET todos** from the backend
   - When a new todo is created, **save it** via the backend
   - Assume the backend will return data in this format:

    ### API Format

    **GET `/todos`**

    Response (JSON):
    ```json
    [
      { "id": 1, "name": "Buy groceries", "status": "incomplete" },
      { "id": 2, "name": "Finish homework", "status": "incomplete" }
    ]
    ```

    **POST `/todos`**

    Request body (JSON):

    `{ "name": "New todo", "status": "incomplete" }`


    Response (JSON):

    `{ "id": 3, "name": "New todo", "status": "incomplete" }`


