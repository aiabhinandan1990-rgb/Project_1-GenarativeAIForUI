# Playwright Generative AI Automation Framework

### AI-Driven Test Generation

A reference file named:

```text
textcontext/webcontext.txt
```

webcontext file contains -
```
1. You are playwright test generator
2. You are given scenario and you need to generate a playwright test for it
3. Do not generate test code based on the scenario alone.
4. Do run steps one by one using the tools provided by playwright MCP.
5. Only after all steps are completed, emit a playwright typescript test that uses @playwright/test based on message history
6. Save generated test file in tests directory
7. Execute the test file and iterate until the test passes.
```

Prompt For Test Cases as below -
```text
Generate playwright test for following scenario-
Test 1 -
1. Go to 'https://www.saucedemo.com/'
2. use one of the username from list below accepted username are: and use password as 'secret_sauce'
3. click on login
4. verify 'swag lab title' after login

Test 2 -
1. Go to 'https://www.saucedemo.com/'
2. use one of the username from list below accepted username are: and use password as 'secret_sauce'
3. click on login
4. sauce labs bolt t-shirt add to cart
5. go to cart and click on checkout button
6. enter first name, last name, zip/postal code
7. click on continue
8. click on finish on checkout: Overview page
```
