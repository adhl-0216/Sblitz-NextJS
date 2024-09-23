# Functional Requirements

## Split Microservice

| ID  | Requirement Name                                                    | Category | Acceptance Criteria |
| --- | ------------------------------------------------------------------- | -------- | ------------------- |
| 01  | As a User, I want to view all my Bills                              | Split    |                     |
| 02  | As a User, I want to create a new Bill                              | Split    | -                   |
| 03  | As a User, I want to add an existing Friend to a Bill               | Split    | -                   |
| 04  | As a User, I want to add a custom Friend to a Bill                  | Split    | -                   |
| 05  | As a User, I want to add a new Item in a Bill                       | Split    | -                   |
| 06  | As a User, I want to assign an Item to any Friend added to the Bill | Split    | -                   |

## IAM Microservice

| ID  | Requirement Name                                 | Category | Acceptance Criteria                                                                                          |
| --- | ------------------------------------------------ | -------- | ------------------------------------------------------------------------------------------------------------ |
| 01  | As a User, I want to register to the application | IAM      | - User can register via email + password or Google Account<br />- Confirmation email sent                    |
| 02  | As a User, I want to log in to the application   | IAM      | - User can log in using registered credentials<br />- Successful login returns a JWT for subsequent requests |
| 03  | As a User, I want to reset my password           | IAM      | - User request a password reset email                                                                        |

## Social Microservice

| ID  | Requirement Name                                                            | Category | Acceptance Criteria                   |
| --- | --------------------------------------------------------------------------- | -------- | ------------------------------------- |
| 01  | As a User, I want to view my profile                                        | Social   | - User can access profile information |
| 02  | As a User, I want to update my profile                                      | Social   | - User can update profile details     |
| 03  | As a User, I want to find my Friend on the application with their email/tag | Social   | -                                     |
| 04  | As a User, I want to add my Friend to my Contacts                           | Social   | -                                     |
| 05  | As a User, I want to remove a Friend from my Contacts                       | Social   | -                                     |
| 06  | As a User, I want to view all my Contacts                                   | Social   | -                                     |
