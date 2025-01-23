# Web Application Project

This repository contains the source code for a Clinic Connect web application. The project follows a **DevOps approach** with proper source code management to ensure collaboration and maintain code quality as the team expands.

## Branching Strategy

The project uses a simplified **Branch Workflow** to manage code development effectively.

### Key Branches

1. **`main` branch**  
   - Contains production-ready code.  

2. **`develop` branch**  
   - Used for integrating all ongoing development.  
   - All feature and bugfix branches are merged here after review and testing.

3. **Feature branches (`feature_<featureName>_<devName>`)**  
   - Created for developing specific features or tasks.  
   - Examples: `feature/login`, `feature/dashboard`.  
   - Created from `develop` and merged back after completion and testing.

4. **Bugfix branches (`bugfix_<bugDescription><devName>`)**  
   - Created for fixing bugs in the `develop` branch.  
   - Examples: `bugfix/login-error`, `bugfix/payment-issue`.  


5. **Hotfix branches (`hotfix_<issue_description>_<devName>`)**  
   - Created for critical fixes in the `main` branch.  
   - Example: `hotfix/payment-bug`.  
   - Merges back into both `main` and `develop`.


## Workflow

1. Clone the repository:
   ```bash
   git clone https://github.com/abdulRahman1093/maven-git-exercise.git

   
