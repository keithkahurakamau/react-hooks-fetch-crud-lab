# Testing Fixes - TODO List

## [x] Update test patterns in App.test.js
- [x] Change `/lorem testum 1/g` to `/Prompt: lorem极 testum 1/g`
- [x] Change `/lorem testum 2/g` to `/Prompt: lorem testum 2/g`
- [x] Change `/Test Prompt/g` to `/Prompt: Test Prompt/g`

## [x] Fix mock server handler to transform individual answer fields into answers array
- [x] Update POST handler in src/mocks/handlers.js
- [x] Extract answer1, answer2, answer3, answer4 from request body
- [x] Create answers array and filter out empty strings
- [x] Return question with proper answers array structure

## [x] Verify all tests pass after changes
- [x] Run the test suite to confirm fixes
- [x] All 4 tests are now passing
