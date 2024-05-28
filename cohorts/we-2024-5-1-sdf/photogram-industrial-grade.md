# Industrial Grade Application: Photogram

**Prerequisites**:
- Scaffolding and Helper Methods

**Requirements**:
- must complete all of these requirements
- must move through requirements in sequential order

## Overview
```md
This module focuses on developing a robust, industrial-grade application called Photogram. You will work through various stages of building this application, implementing user accounts, associations, validations, and user interfaces. The module also includes lessons on code reviews, pull requests, and authorization with Pundit.

## Learning Outcomes
By the end of this module, you will be able to:

- Implement user authentication using Devise.
- Scaffold resources and manage data using ActiveRecord.
- Create and manage associations and validations.
- Develop user interfaces and refactor code for better maintainability.
- Conduct code reviews and manage pull requests.
- Implement authorization using Pundit.
```

## Photogram Industrial Part 1: Devise accounts and photos scaffold 📸 🏭
- **Points**: 10
- **Requirements**: Score at least 2.0
- **Due**: end of week 5
  - [Learn](https://learn.firstdraft.com/lessons/197-photogram-industrial-part-1)
  - [GitHub](https://github.com/appdev-lessons/photogram-industrial-part-1)

## Photogram Industrial Part 2: Associations, validations, and sample data 📸 🏭
- **Points**: 0
- **Requirements**:  mark as done
- **Due**: end of week 5
- [Learn](https://learn.firstdraft.com/lessons/198-photogram-industrial-part-2)
- [GitHub](https://github.com/appdev-lessons/photogram-industrial-part-2)

### Pull Request URL for Photogram Industrial: photogram-industrial > main 📥📋
- **Points**: 5
- **Requirements**:  score at least 5.0
- **Due**: end of week 5
```md
IMPORTANT: Please make sure to submit a pull request to merge into the `main` branch of <u>your own repository</u>. We do not want to submit requests to pull into the `appdev-projects` repository! 😵‍💫

<!-- todo: swap out TA -->
Please invite a fellow trainee AND <name> (@<username> on Github) to collaborate on your repository. Also, be sure to have them both review your pull request.
```

#### Pull Request URL for Photogram Industrial: photogram-industrial > main 📥📋 (giving a code review)
- **Points**: 2
- **Requirements**:  submit
- **Due**: end of week 5
  **If possible, please try to give a code review to someone who has not yet received a review on this branch!**

## Photogram Industrial Part 3: Starting user interface 📸 🏭
- **Points**: 2
- **Requirements**: mark as done
- **Due**: end of week 5
- [Learn](https://learn.firstdraft.com/lessons/199-photogram-industrial-part-3)
- [GitHub](https://github.com/appdev-lessons/photogram-industrial-part-3)


### Pull Request URL for Photogram Industrial: starting-on-ui > main 📥📋
- **Points**: 5
- **Requirements**:  score at least 5.0
- **Due**: end of week 5
```md
<!-- todo: swap out TA -->
Please invite a fellow trainee AND <name> (@<username> on Github) to collaborate on your repository. Also, be sure to have them both review your pull request.
```

#### Pull Request URL for Photogram Industrial: starting-on-ui > main  📥📋 (giving a code review)
- **Points**: 2
- **Requirements**:  submit
- **Due**: end of week 5
```md
**If possible, please try to give a code review to someone who has not yet received a review on this branch!**
```

## Photogram Industrial Part 4: Profile page 📸 🏭
- **Points**: 0
- **Requirements**:  mark as done
- **Due**: end of week 5
- [Learn](https://learn.firstdraft.com/lessons/200-photogram-industrial-part-4)
- [GitHub](https://github.com/appdev-lessons/photogram-industrial-part-4)


### Pull Request URL for Photogram Industrial: profile-page > main  📥📋
- **Points**: 5
- **Requirements**:  score at least 5.0
- **Due**: end of week 5
```md
<!-- todo: swap out TA -->
Please invite a fellow trainee AND <name> (@<username> on Github) to collaborate on your repository. Also, be sure to have them both review your pull request.
```
#### Pull Request URL for Photogram Industrial: profile-page > main  📥📋 (giving a code review)
- **Points**: 2
- **Requirements**:  submit
- **Due**: end of week 5
```md
**If possible, please try to give a code review to someone who has not yet received a review on this branch!**
```

### Pull Request URL for Photogram Industrial: tabbed-interface > main  📥📋
- **Points**: 5
- **Requirements**:  score at least 5.0
- **Due**: end of week 5
```md
<!-- todo: swap out TA -->
Please invite a fellow trainee AND <name> (@<username> on Github) to collaborate on your repository. Also, be sure to have them both review your pull request.
```

#### Pull Request URL for Photogram Industrial: tabbed-interface > main  📥📋 (giving a code review)
- **Points**: 2
- **Requirements**:  submit
- **Due**: end of week 5
```md
**If possible, please try to give a code review to someone who has not yet received a review on this branch!**
```

## Photogram Industrial Authorization 🔒
- **Points**: 0
- **Requirements**:  mark as done
- **Due**: end of week 5
- [Learn](https://learn.firstdraft.com/lessons/201-photogram-industrial-authorization)
- [GitHub](https://github.com/appdev-lessons/photogram-industrial-authorization)


### Pull Request URL for Photogram Industrial Authorization: add-authorization > main 📥📋
- **Points**: 5
- **Requirements**:  score at least 5.0
- **Due**: end of week 5
```md
<!-- todo: swap out TA -->
Please invite a fellow trainee AND <name> (@<username> on Github) to collaborate on your repository. Also, be sure to have them both review your pull request.
```

#### Pull Request URL for Photogram Industrial Authorization: add-authorization > main 📥📋 (giving a code review)
- **Points**: 2
- **Requirements**:  submit
- **Due**: end of week 5
```md
**If possible, please try to give a code review to someone who has not yet received a review on this branch!**
```

## Reading: Authorization with Pundit 🔒
- **Points**: 0
- **Requirements**:  mark as done
- **Due**: end of week 5
- [Learn](https://learn.firstdraft.com/lessons/202-pundit-authorization)
- [GitHub](https://github.com/appdev-lessons/pundit-authorization)


### Pull Request for Pundit Policies: add-pundit > main 📥📋
- **Points**: 5
- **Requirements**:  submit
- **Due**: end of week 5
```md
- Set up policies for the `Photos`, `Users`, `Comments`, and `FollowRequests` controllers.
- We are not requiring a policy for Likes at this point since it's not fully implemented.
- Ask a fellow trainee to review your PR as part of their "giving a code review" assignment.

Check list:
- Have you "secured by default"? E.g. calling `verify_authorized` and `verify_policy_scoped` after each action in the application controller.
- Have you called `authorize` for each action in each controller?
- Have you set up policies for each action in each controller?
- Have you made sure everything is working in the live preview?
- **Please assign <name> (@<username>) to review your pull request**.
```

#### Pull Request for Pundit Policies: add-pundit > main 📥📋 (giving a code review)
- **Points**: 2
- **Requirements**:  submit
- **Due**: end of week 5
```md
**If possible, please try to give a code review to someone who has not yet received a review on this branch!**
```
