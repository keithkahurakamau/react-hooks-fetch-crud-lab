# Quiz App CRUD Implementation Plan

## Steps to Complete:

### 1. App.js Updates
- [x] Add useState for questions array
- [x] Pass questions and setQuestions to child components

### 2. QuestionList.js Updates  
- [x] Add useEffect to fetch questions on mount
- [x] Import and render QuestionItem components
- [x] Pass delete and update handlers to QuestionItem

### 3. QuestionForm.js Updates
- [x] Modify handleSubmit to POST new question
- [x] Format data correctly for API
- [x] Update parent state with new question

### 4. QuestionItem.js Updates
- [x] Add delete handler with DELETE request
- [x] Add change handler for dropdown with PATCH request
- [x] Update parent state after operations

### 5. Testing
- [x] Install dependencies
- [x] Start JSON server
- [x] Start React app
- [x] Test all CRUD operations
