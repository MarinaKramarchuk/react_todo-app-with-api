# React Todo App with API

A full-featured Todo application built with **React** and **TypeScript**, fully synchronized with a remote API.  
The app allows users to create, rename, toggle, and delete todos, manage all items at once, and interact with the UI through smooth loading states and error handling.

🔗 **Demo:** https://MarinaKramarchuk.github.io/react_todo-app-with-api/  
💻 **GitHub Code:** https://github.com/MarinaKramarchuk/react_todo-app-with-api

---

## Features

### ✅ Create todos
- Add new tasks with API synchronization  
- Show a loader overlay during requests  
- Display error notifications in case of failed requests  

### ✅ Toggle todo status
- Mark a task as completed or active  
- Apply a loader on the updated todo  
- Update the UI only after API success  
- Show `Unable to update a todo` on failure  

### ✅ Toggle all todos
- "Toggle all" checkbox marks **all** todos completed or active  
- Has `active` class only when all tasks are completed  
- Sends requests only for todos whose status has changed  
- Behaves the same as multiple individual updates  

### ✅ Rename todos
- Double-click to edit a todo title  
- Save changes with **Enter** or on input **blur**  
- Cancel editing with **Esc**  
- Delete the todo if the new title is empty  
- Show loader while updating  
- Display error messages for update/delete failures  

### ✅ Delete todos
- Remove single items with API request  
- Show loader during deletion  
- Notification on API errors  

### Optional UI Features (if implemented)
- Filters: All / Active / Completed  
- Active items counter  
- Clear completed button  

---

## Tech Stack

- **React**
- **TypeScript**
- **JavaScript (ES6+)**
- **CSS / SASS**
- **BEM Methodology**
- **REST API**

---

## Installation & Setup

### 🔧 Requirements
- Node.js (LTS recommended)  
- npm or yarn  

### 📦 Install

```bash
git clone https://github.com/your_account/react_todo-app-with-api.git
cd react_todo-app-with-api
npm install


