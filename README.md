# Helper Message Application (Fork)

This web application is a fork of Mojang’s Mojira Helper Message Application. It aggregates and provides copy-paste templates to help users respond consistently to common support requests.

⚠ This fork is **not affiliated with Mojang or the Mojira team**. It is intended for general users (“lambda users”) and community support contexts outside the official bug tracker moderation workflow.

---

## How to use the tool

To run this project locally, you need Node.js installed.

### 1. Clone the repository

```bash
git clone https://github.com/aegislunarian/user-messages.git
cd user-messages 
``` 

### 2. Install dependencies

```bash
npm install  
``` 

### 3. Edit helper messages

All helper messages are stored in:

messages.yml  

You can modify this file to:
- add new request templates
- edit existing messages
- update categories or projects

Make sure to keep the YAML structure valid, otherwise the application may fail to load.

### 4. Build the project

```bash
npm run build  
``` 

This will generate the production-ready files.

---

## Deployment

This project is intended to be deployed via GitHub Pages. Any push to the main branch may trigger an automatic build and deployment depending on the repository configuration.

---

## Contribute

Issues and pull requests are welcome. Please clearly explain any changes made to `messages.yml` in your PR.

This fork is maintained independently and does not follow Mojira’s internal contribution rules.

---

## Found a bug in Minecraft?

Please go to https://bugs.mojang.com, search for your issue, and create a new report if it hasn’t already been submitted.

---

## License

This project remains under the MIT License (https://opensource.org/licenses/MIT). See the LICENSE file for details.